# kraken_grantha

Baseline based model for Grantha script for Kraken.

Example Usage

```
for i in tam.Noto_Sans_Grantha.0001000.exp0.png  ; do kraken -i "$i" "${i%.*}"-grantha_best.txt binarize ocr -s -m grantha_best.mlmodel ; done
```

