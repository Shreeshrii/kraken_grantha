# kraken_grantha

Baseline based model for Grantha script for Kraken.

Example Usage

```
for i in tam.Noto_Sans_Grantha.0001000.exp0.png  ; do 
    kraken -i "$i" "${i%.*}"-grantha_best.txt binarize ocr -s -m grantha_best.mlmodel ; 
done
```

INPUT

![INPUT IMAGE](https://github.com/Shreeshrii/kraken_grantha/raw/master/tam.Noto_Sans_Grantha.0001000.exp0.png)

OUTPUT

𑌮𑍁𑌰𑍈𑌂𑌪𑌂𑌟 𑌵𑌥 𑌪𑌬 𑌦𑍍𑌰𑌾𑌵𑌿𑌡𑍍𑌯𑌾𑌂 𑌪𑌚𑌿

https://github.com/Shreeshrii/kraken_grantha/raw/master/tam.Noto_Sans_Grantha.0001000.exp0-grantha_best.txt

