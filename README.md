# MultiPositiveLogQ

| Model Name | hit_rate@100 | recall@100 | ndcg@100 |
|---|---:|---:|---:|
| **SasRec(MultiPositive: L1) + BatchLogQ** | **0.425860** | **0.154506** | **0.060451** |
| SasRec(MultiPositive: L1) | 0.415247 | 0.149186 | 0.058068 |
| SasRec(Two Tower + BatchLogQ) | 0.410103 | 0.146749 | 0.055974 |
| SasRec(Two Tower + CountW) | 0.406228 | 0.144716 | 0.055805 |
| SasRec(Two Tower) | 0.400922 | 0.141965 | 0.053843 |
| SasRec(MultiPositive: L2) | 0.399166 | 0.140376 | 0.054784 |
| SasRec(GPT Style) | 0.385714 | 0.133549 | 0.052191 |
| SasRec(Two Tower + LogQ) | 0.367544 | 0.124716 | 0.048048 |
| ALS(TimeScaled) | 0.294282 | 0.092734 | 0.03294 |
| TfIDF(TimeScaled) | 0.238296 | 0.079488 | 0.026717 |
| ALS | 0.232565 | 0.070308 | 0.023201 |
| TopPopular(LastWeekend) | 0.218597 | 0.071321 | 0.029366 |
| TfIDF | 0.210889 | 0.068277 | 0.022775 |
| MarkovChains | 0.188026 | 0.057564 | 0.024964 |
| TopPopular | 0.110879 | 0.030551 | 0.010684 |
| HistoryLookUp | 0.076738 | 0.031291 | 0.010227 |
| Random | 0.00036 | 0.000043 | 0.000014 |
