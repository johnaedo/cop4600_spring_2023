ALGORITHM: lru
FRAME SIZE: 5
PAGE FAULTS: 10
| 3*   | 2*   | 10*   | 5*   |   8* |   3 |   5 |   6* |   7* |   1* |   1 |   8* |   3* |   8 |   1 |   6 |   7 |   6 |   3 |
|------|------|-------|------|------|-----|-----|------|------|------|-----|------|------|-----|-----|-----|-----|-----|-----|
| 3    | 3    | 3     | 3    |    3 |   3 |   3 |    3 |    3 |    3 |   3 |    8 |    8 |   8 |   8 |   8 |   8 |   8 |   8 |
|      | 2    | 2     | 2    |    2 |   2 |   2 |    6 |    6 |    6 |   6 |    6 |    6 |   6 |   6 |   6 |   6 |   6 |   6 |
|      |      | 10    | 10   |   10 |  10 |  10 |   10 |    7 |    7 |   7 |    7 |    7 |   7 |   7 |   7 |   7 |   7 |   7 |
|      |      |       | 5    |    5 |   5 |   5 |    5 |    5 |    5 |   5 |    5 |    3 |   3 |   3 |   3 |   3 |   3 |   3 |
|      |      |       |      |    8 |   8 |   8 |    8 |    8 |    1 |   1 |    1 |    1 |   1 |   1 |   1 |   1 |   1 |   1 |