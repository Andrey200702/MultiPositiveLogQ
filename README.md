# MultiPositiveLogQ

| Model Name | hit_rate@100 | recall@100 | ndcg@100 |
|---|---:|---:|---:|
| **SasRec(MultiPositive: L1)** | **0.415247** | **0.149186** | **0.058068** |
| SasRec(Two Tower + BatchLogQ) | 0.409544 | 0.146159 | 0.054784 |
| SasRec(Two Tower) | 0.399469 | 0.141203 | 0.053843 |
| SasRec(MultiPositive: L2) | 0.399166 | 0.140376 | 0.054784 |
| SasRec(GPT Style) | 0.371360 | 0.126227 | 0.049077 |
| SasRec(Two Tower + LogQ) | 0.367790 | 0.124880 | 0.048201 |
| ALS(TimeScaled) | 0.294282 | 0.092734 | 0.03294 |
| TfIDF(TimeScaled) | 0.238296 | 0.079488 | 0.026717 |
| ALS | 0.232565 | 0.070308 | 0.023201 |
| TopPopular(LastWeekend) | 0.218597 | 0.071321 | 0.029366 |
| TfIDF | 0.210889 | 0.068277 | 0.022775 |
| MarkovChains | 0.188026 | 0.057564 | 0.024964 |
| TopPopular | 0.110879 | 0.030551 | 0.010684 |
| HistoryLookUp | 0.076738 | 0.031291 | 0.010227 |
| Random | 0.00036 | 0.000043 | 0.000014 |
