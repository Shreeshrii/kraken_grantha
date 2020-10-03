# kraken_grantha

Baseline based model for [Grantha script](https://en.wikipedia.org/wiki/Grantha_script) for [Kraken](https://github.com/mittagessen/kraken/tree/master/kraken).

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

TRAINED ALPHABET 

```
[523.8546] Training set 3123 lines, validation set 348 lines, alphabet 108 symbols 
[523.8548] alphabet mismatch: chars in training set only: {'_', '5', '6', '0', '3', '7', '9', '1', '4', '*', '2'} (not included in accuracy test during training) 
[523.8550] grapheme	count 
[523.8551] SPACE	27739 
[523.8552] GRANTHA SIGN VIRAMA	19701 
[523.8553] GRANTHA VOWEL SIGN AA	9398 
[523.8554] 	𑌤	7881 
[523.8554] 	𑌰	7489 
[523.8555] GRANTHA VOWEL SIGN I	6179 
[523.8556] 	𑌮	5876 
[523.8556] 	𑌵	5837 
[523.8557] 	𑌨	5706 
[523.8557] 	𑌯	5587 
[523.8558] 	𑌸	4580 
[523.8559] GRANTHA VOWEL SIGN EE	4017 
[523.8559] DEVANAGARI STRESS SIGN ANUDATTA	4016 
[523.8560] 	𑌕	3607 
[523.8561] 	𑌪	3497 
[523.8561] GRANTHA VOWEL SIGN U	3486 
[523.8562] 	𑌦	3362 
[523.8563] VEDIC TONE CANDRA ABOVE	2669 
[523.8563] GRANTHA SIGN ANUSVARA	2618 
[523.8564] 	।	2524 
[523.8564] 	𑌶	2514 
[523.8565] GRANTHA VOWEL SIGN OO	2467 
[523.8566] GRANTHA SIGN VISARGA	2422 
[523.8566] 	𑌷	2274 
[523.8567] 	𑌚	2210 
[523.8568] 	𑌹	2022 
[523.8568] 	𑌣	1944 
[523.8569] GRANTHA VOWEL SIGN II	1840 
[523.8569] 	𑌭	1817 
[523.8570] 	𑌜	1674 
[523.8571] 	𑌗	1619 
[523.8571] 	𑌲	1591 
[523.8572] 	𑌧	1540 
[523.8573] 	॥	1419 
[523.8573] 	𑌅	1344 
[523.8574] 	-	1227 
[523.8575] GRANTHA VOWEL SIGN VOCALIC R	1226 
[523.8575] 	𑌬	1086 
[523.8576] GRANTHA VOWEL SIGN UU	1054 
[523.8576] 	.	1035 
[523.8577] 	𑌥	939 
[523.8578] GRANTHA VOWEL SIGN AI	775 
[523.8578] 	𑌟	741 
[523.8579] 	௧	694 
[523.8580] 	𑌞	621 
[523.8580] 	,	575 
[523.8581] 	𑌙	510 
[523.8582] 	)	510 
[523.8582] 	𑌇	501 
[523.8583] 	௦	465 
[523.8583] 	(	461 
[523.8584] 	𑌡	458 
[523.8585] 	௨	457 
[523.8585] 	𑌆	453 
[523.8586] 	𑌖	446 
[523.8587] GRANTHA AU LENGTH MARK	403 
[523.8587] 	𑌠	383 
[523.8588] 	𑌛	375 
[523.8588] 	௩	374 
[523.8589] 	𑌽	361 
[523.8590] 	𑍐	352 
[523.8590] 	𑌉	351 
[523.8591] 	𑌏	325 
[523.8591] 	௪	315 
[523.8592] 	௫	307 
[523.8593] DEVANAGARI STRESS SIGN UDATTA	274 
[523.8593] 	𑌘	270 
[523.8594] GRANTHA SIGN NUKTA	268 
[523.8595] 	௮	265 
[523.8595] 	𑌫	264 
[523.8596] 	௭	262 
[523.8596] 	/	258 
[523.8597] 	௬	249 
[523.8598] 	௯	248 
[523.8598] 	:	232 
[523.8599] 	=	220 
[523.8600] 	;	217 
[523.8600] 	𑌢	202 
[523.8601] 	'	189 
[523.8601] 	𑌳	183 
[523.8602] GRANTHA SIGN COMBINING ANUSVARA ABOVE	139 
[523.8603] 	𑌝	89 
[523.8603] 	𑌓	85 
[523.8604] 	𑌋	82 
[523.8605] 	𑌈	75 
[523.8605] 	𑌊	66 
[523.8606] 	𑍡	63 
[523.8606] GRANTHA VOWEL SIGN AU	59 
[523.8607] GRANTHA SIGN CANDRABINDU	49 
[523.8608] 	𑍠	49 
[523.8608] 	𑍝	36 
[523.8609] GRANTHA VOWEL SIGN VOCALIC RR	34 
[523.8610] 	^	32 
[523.8610] GRANTHA VOWEL SIGN VOCALIC L	31 
[523.8611] 	1	23 
[523.8611] 	*	22 
[523.8612] 	2	16 
[523.8613] 	_	11 
[523.8613] 	𑌐	10 
[523.8614] 	𑌔	7 
[523.8615] 	3	5 
[523.8615] 	4	4 
[523.8616] 	6	4 
[523.8616] 	5	4 
[523.8617] 	7	4 
[523.8618] 	9	3 
[523.8618] 	8	3 
[523.8619] 	0	3 
```

BEST MODEL

```
[47906.5020] Moving best model grantha_9.mlmodel (0.9393690912598881) to grantha_best.mlmodel 
```
