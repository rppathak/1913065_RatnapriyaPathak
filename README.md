# 1913065_RatnapriyaPathak
Implementation of Apriori Algorithm using python

INPUT: .csv file containing items separated by ','

ITEMS [A, C, D, E], [B, C, E], [A, B, C, E], [B, E, A], [C, D]

MINIMUM SUPPORT: 0.6 (60%)

CANDIDATE ITEMSET: [C1, C2, C3]

C1:
['A']: 3
['B']: 3
['C']: 4
['D']: 2
['E']: 4


C2:
['A', 'E']: 3
['B', 'A']: 2
['B', 'E']: 3
['C', 'B']: 2
['C', 'E']: 3
['C', 'A']: 2


C3:
['C', 'A', 'E']: 2
['C', 'B', 'E']: 2
['B', 'A', 'E']: 2


FREQUENT ITEMSET:[L1, L2]


L1:
['A']: 3
['B']: 3
['C']: 4
['E']: 4

L2:
['A', 'E']: 3
['B', 'E']: 3
['C', 'E']: 3
