# Syntax-Tree-Profiles
Reproduction of Tschuggnall, M., &amp; Specht, G. (2014, April): Enhancing Authorship Attribution By Utilizing Syntax Tree Profiles


# Classification Results


**set c (8 authors, 8 unknown documents)**

| unknown id | predicted author | ground truth |
| ---------- | ---------------- |------------- |
| 1          |        5         |       6      |
| 2          |        5         |       1      |
| 3          |        1         |       5      |
| 4          |        3         |       3      |
| 5          |        7         |       7      |
| 6          |        2         |       2      |
|    7       |        5         |       8      |
|    8       |        3         |       4      |


**set a (3 authors, 6 unknown documents)**

| unknown id |  predicted author| ground truth |
| ---------- | ---------------- | ------------ |
| 1          | 3                | 3            |
| 2          | 1                | 2            |
| 3          | 3                | 3            |
| 4          | 1                |  1           |
| 5          | 1                | 1            |
| 6          | 2                | 2            |

Accuracy = 0.83333 (5/6)
Macro-F1 = 0.86022
Macro-Recall = 0.83333
Macro-Precision = 0.88889

**set i (14 authors, 14 unknown documents)**

| unknown id | predicted author | ground truth |
| ---------- | ---------------- |------------- |
| 1          |                 |        14     |
| 2          |                 |       13      |
| 3          |                 |       4      |
| 4          |                 |       10      |
| 5          |                 |       1      |
| 6          |                 |       6      |
|    7       |                 |       5      |
|    8       |                 |       7      |
| 9          |                 |        12    |
| 10         |                 |        11      |
| 11         |                 |         8     |
| 12         |                 |        9      |
| 13         |                 |         2     |
| 14         |                 |         3     |

**Classification on pan11 - large data set:**
Accuracy = 0.053077 (69/1300)
Macro-F1 = 0.044853
Macro-Recall = 0.045639
Macro-Precision = 0.044094

**Classification on C10*
Accuracy = 0.262 (131/500)
Macro-F1 = 0.25662
Macro-Recall = 0.262
Macro-Precision = 0.25145


# References
Augsten, N., Böhlen, M., & Gamper, J. (2010). The pq-gram distance between ordered labeled trees. ACM Transactions on Database Systems (TODS), 35(1), 4.

Tschuggnall, M., & Specht, G. (2014, April). Enhancing Authorship Attribution By Utilizing Syntax Tree Profiles. In EACL (pp. 195-199).

Frantzeskou, G., Stamatatos, E., Gritzalis, S., & Katsikas, S. (2006, May). Effective identification of source code authors using byte-level information. In Proceedings of the 28th international conference on Software engineering (pp. 893-896). ACM.
