### Few-shot

|                                     | Has-Quant | Has-Quant-All | Has-Quant-CompScope | Has-Compar | Has-Compar-More | Has-GroupBy | Has-Logic | Has-Logic-And | Has-Num-3 | Has-Num3-Ans-3 | Ans-Num | Average |
| :---------------------------------: | :-------: | :-----------: | :-----------------: | :--------: | :-------------: | :---------: | :-------: | :-----------: | :-------: | :------------: | :-----: | :-----: |
|  ViLBERT (Bogin et al., EMNLP'21)   |   65.6    |     60.9      |        67.5         |    64.2    |      79.8       |    55.6     |   72.1    |     70.9      |   67.7    |      27.5      |  38.5   |  60.9   |
| VisualBERT (Bogin et al., EMNLP'21) |   55.8    |     69.2      |        60.4         |    57.5    |      79.8       |    56.5     |   69.3    |     74.8      |   68.8    |      25.8      |  32.2   |  59.1   |

### Zero-shot

|                                     | Program Split | Lexical Split | Has-Quant-CompScope & Has-Quant-All | Has-Count & Has-Attr | Has-Count & RM/V/C | Has-SameAttr-Color | TPL-ChooseObject | TPL-VerifyQuantAttr | TPL-VerifyAttr | TPL-VerifyCount + TPL-VerifyCountGroupBy | Average |
| :---------------------------------: | :-----------: | :-----------: | :---------------------------------: | :------------------: | :----------------: | :----------------: | :--------------: | :-----------------: | :------------: | :--------------------------------------: | :-----: |
| VisualBERT (Bogin et al., EMNLP'21) |     49.5      |     71.5      |                57.7                 |         58.7         |        74.1        |         66         |       1.6        |        71.2         |       0        |                   41.7                   |  49.2   |
|  ViLBERT (Bogin et al., EMNLP'21)   |      49       |     71.5      |                64.7                 |         57.4         |        71.4        |        64.7        |        2         |        61.2         |       0        |                   29.5                   |  47.1   |
