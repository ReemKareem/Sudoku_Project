### Experiment 3: NN-guided vs no vs random correction

5 seeds x 20 puzzles per cell, 30 givens, random baseline: 200 tries, max 3 changed cells, team seed 0.

| method | misreads | exact_recovery | solved_but_wrong | unreadable |
|---|---|---|---|---|
| NN-guided (UCS) | 0 | 1.000 ± 0.000 | 0.000 ± 0.000 | 0.000 ± 0.000 |
| NN-guided (UCS, unique goal) | 0 | 1.000 ± 0.000 | 0.000 ± 0.000 | 0.000 ± 0.000 |
| No correction | 0 | 1.000 ± 0.000 | 0.000 ± 0.000 | 0.000 ± 0.000 |
| Random correction | 0 | 1.000 ± 0.000 | 0.000 ± 0.000 | 0.000 ± 0.000 |
| NN-guided (UCS) | 1 | 0.860 ± 0.042 | 0.120 ± 0.057 | 0.020 ± 0.027 |
| NN-guided (UCS, unique goal) | 1 | 0.950 ± 0.050 | 0.030 ± 0.027 | 0.020 ± 0.027 |
| No correction | 1 | 0.000 ± 0.000 | 0.090 ± 0.065 | 0.910 ± 0.065 |
| Random correction | 1 | 0.120 ± 0.091 | 0.560 ± 0.108 | 0.320 ± 0.091 |
| NN-guided (UCS) | 2 | 0.660 ± 0.108 | 0.310 ± 0.074 | 0.030 ± 0.045 |
| NN-guided (UCS, unique goal) | 2 | 0.840 ± 0.089 | 0.130 ± 0.057 | 0.030 ± 0.045 |
| No correction | 2 | 0.000 ± 0.000 | 0.010 ± 0.022 | 0.990 ± 0.022 |
| Random correction | 2 | 0.000 ± 0.000 | 0.230 ± 0.076 | 0.770 ± 0.076 |
| NN-guided (UCS) | 3 | 0.580 ± 0.125 | 0.380 ± 0.104 | 0.040 ± 0.042 |
| NN-guided (UCS, unique goal) | 3 | 0.820 ± 0.091 | 0.140 ± 0.065 | 0.040 ± 0.042 |
| No correction | 3 | 0.000 ± 0.000 | 0.020 ± 0.027 | 0.980 ± 0.027 |
| Random correction | 3 | 0.000 ± 0.000 | 0.080 ± 0.027 | 0.920 ± 0.027 |
