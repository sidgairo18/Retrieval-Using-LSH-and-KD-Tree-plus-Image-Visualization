# Neighbours

## Accuracy
| Neighbour / k | 0.0    | 0.8    | 0.9               | 0.95              |
|---------------|--------|--------|-------------------|-------------------|
| Top 15        | 70.342 | 39.364 | 46.81666666666667 | 55.94             |
| Bottom 15     | 91.38  | 91.228 | 90.79933333333334 | 87.01733333333334 |

We get the highest accuracy without normalization

Use k = 0.9 for bottom neighbours, so the neighbour's set has different values.

## Union Size

We get the following sizes of the unions of top/bottom k neighbours out of 121000.

| Neighbour / k | 0.0             | 0.8            | 0.9             | 0.95            |
|---------------|-----------------|----------------|-----------------|-----------------|
| Top 15        | 114864 (94.92%) | 87575 (72.37%) | 102132 (84.40%) | 114624 (94.73%) |
| Bottom 15     | 33 (0.02%)      | 87 (0.07%)     | 1344 (1.11%)    | 37024 (30.59%)  |
