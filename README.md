# SOTA-semi

- CIFAR10

|             | 250   | 1000  | 4000  |
|-------------|-------|-------|-------|
| MeanTeacher | -     | 21.55 | 12.31 |
| VAT+EntMin  | -     | -     | 10.55 |
| Π-model     | -     | -     | 12.36 |
| Temporal Ensembling | - | - | 12.16 |
| MA-DNN      |       |       | 11.91 |
| Interpolation Consistency Training |   38.60 |       | 6.81 |
| MixMatch    | 11.80 | -     | 6.00  |

https://arxiv.org/pdf/1804.09170.pdf

- CIFAR100

|             | 250   | 1000  | 10,000  |
|-------------|-------|-------|-------|
| MeanTeacher | -     | -      |  |
| VAT+EntMin  | -     | -      |  |
| Π-model     | -     | -     | 39.19 |
| Temporal Ensembling | - | - | 37.34 |
| MA-DNN      | -     | -      | 34.51 |
| Interpolation Consistency Training |   -  |  -     |  |
| MixMatch    | - | -     |   |
