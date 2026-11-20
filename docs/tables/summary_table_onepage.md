| metric | source | authentic reference | SADA v4 (context) | SADA v4.1 | SADA-final (preliminary) |
|---|---|---|---|---|---|
| synthetic rows | ArS | 2296 | 4353 | 2828 | 4438 |
| synthetic rows | iSa | 747 | 568 | 637 | 894 |
| C2ST AUC [95 % CI] | both | 0.501 [0.478, 0.521] | 0.931 [0.923, 0.940] | 0.873 [0.855, 0.891] | 0.873 [0.859, 0.884] |
| C2ST AUC [95 % CI] | ArS | 0.502 [0.476, 0.523] | 0.916 [0.904, 0.926] | 0.879 [0.867, 0.894] | 0.882 [0.860, 0.901] |
| C2ST AUC [95 % CI] | iSa | 0.509 [0.471, 0.556] | 0.950 [0.925, 0.971] | 0.801 [0.729, 0.879] | 0.803 [0.746, 0.855] |
| MAUVE | both | 0.951 | 0.310 | 0.593 | 0.667 |
| MMD^2 [95 % CI] | ArS | 0.0000 [-0.0002, 0.0002] | 0.0169 [0.0155, 0.0186] | 0.0099 [0.0087, 0.0113] | 0.0088 [0.0076, 0.0101] |
| MMD^2 [95 % CI] | iSa | 0.0001 [-0.0006, 0.0009] | 0.0337 [0.0292, 0.0385] | 0.0076 [0.0041, 0.0119] | 0.0067 [0.0039, 0.0102] |
| precision (k = 5) | both | 0.915 | 0.935 | 0.867 | 0.906 |
| recall (k = 5) | both | 0.931 | 0.642 | 0.888 | 0.852 |
| density (k = 5) | both | 1.013 | 0.922 | 0.630 | 0.800 |
| coverage (k = 5) | both | 0.974 | 0.754 | 0.797 | 0.867 |
| C2ST AUC | both | 0.500 | 0.896 | 0.858 | 0.832 |
| distinct-1 (matched n) | ArS | 0.400 | 0.282 | 0.320 | 0.333 |
| distinct-1 (matched n) | iSa | 0.606 | 0.430 | 0.506 | 0.554 |
| Self-BLEU (x100, lower = more diverse) | ArS | 4.69 | 5.21 | 5.28 | 5.06 |
| Self-BLEU (x100, lower = more diverse) | iSa | 8.18 | 5.97 | 9.61 | 9.44 |
| top-20 openings share | ArS | 0.034 | 0.131 | 0.051 | 0.067 |
| top-20 openings share | iSa | 0.079 | 0.125 | 0.102 | 0.130 |
| rows per anchor (mean) | ArS | 1 (by definition) | 2.25 | 1.93 | 2.50 |
| rows per anchor (mean) | iSa | 1 (by definition) | 1.38 | 1.76 | 1.99 |
| ALDi KS D | ArS | 0.022 | 0.373 | 0.058 | 0.049 |
| ALDi KS D | iSa | 0.040 | 0.227 | 0.061 | 0.055 |
| length KS D | ArS | 0.024 | 0.292 | 0.029 | 0.038 |
| length KS D | iSa | 0.054 | 0.618 | 0.088 | 0.073 |
| TVD dialect (classifier) | ArS | 0.021 | 0.102 | 0.053 | 0.030 |
| TVD dialect (classifier) | iSa | 0.030 | 0.069 | 0.040 | 0.022 |
| TVD sentiment (classifier) | ArS | 0.005 | 0.096 | 0.057 | 0.010 |
| TVD topic clusters (matched n vs half B) | ArS | 0.124 | 0.351 | 0.254 | 0.172 |
| TVD topic clusters (matched n vs half B) | iSa | 0.176 | 0.430 | 0.214 | 0.148 |
| cue rates with parity shift <= 0.02 | ArS | - | 0/6 | 6/6 | 6/6 |
| cue rates with parity shift <= 0.02 | iSa | - | 1/6 | 6/6 | 6/6 |
| max LaBSE cosine to authentic train, p99 | ArS | 0.912 | 0.830 | 0.851 | 0.847 |
| max LaBSE cosine to authentic train, p99 | iSa | 0.839 | 0.718 | 0.801 | 0.820 |
| share sharing >= 8 consecutive words with authentic train | ArS | 1.4 % | 1.5 % | 0.0 % | 0.0 % |
| share sharing >= 8 consecutive words with authentic train | iSa | 0.3 % | 0.7 % | 0.0 % | 0.0 % |
| share copying >= 8 consecutive words from its prompt seeds | ArS | - | 1.5 % | 0.0 % | 0.0 % |
| share copying >= 8 consecutive words from its prompt seeds | iSa | - | 0.7 % | 0.0 % | 0.0 % |
| judge "sarcastic" rate [95 % CI] | both | TPR 0.787 / FPR 0.303 (authentic calibration) | 0.914 [0.899, 0.927] (n = 1614) | 0.887 [0.876, 0.897] (n = 3465) | 0.879 [0.868, 0.888] (n = 3862) |
| label precision range (teacher q to judge Rogan-Gladen, clipped) | both | - | 0.61 to 1.00 | 0.60 to 1.00 | 0.61 to 1.00 |
