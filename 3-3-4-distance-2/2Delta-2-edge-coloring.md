# Problem

    A B CD
    A C D
    B C D

    ABCD BCD CD
    ABCD CD D
    BCD CD D

# Restriction

    A B CD
    A C D
    B C D

    A B CD
    A C D
    B C D

# Fixed point

    A B B

    B AB AB

# Cross-reference
[3-3-2/sinkless-orientation](../3-3-2/sinkless-orientation.md)

# Intuition

Start from 2Delta-2 edge coloring on bipartite 2 colored graphs, assign a total order on the labels.
A < B < C < D
Relax the passive constraint as follows: each time a label is allowed, allow all the larger ones as well.
This operation forces the diagram to be a directed path.
The obtained problem is not a fixed point, but a fixed point is obtained in few steps of round elimination.

# Credits
- Alkida Balliu
- Sebastian Brandt
- Juho Hirvonen
- Dennis Olivetti
- Jukka Suomela
