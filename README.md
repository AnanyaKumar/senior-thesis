Proposal, ideas and writeups for my (ongoing) senior thesis computer science research at Carengie Mellon. Thanks a lot to Prof. Avrim Blum for advising me, and to Lin, Harry, and Vova for collaborations!

Abstract: Given a set of points P, an approximate convex hull is a subset of points in P that approximately covers the original set. More formally, every point in P is within distance epsilon from the convex closure of the subset. The optimal approximate convex hull is the smallest such subset. Approximate convex hulls are intimately tied to the notion of coresets, which are used in computational geometry, machine learning, and approximation algorithms.

Existing streaming (one-pass) algorithms for this problem give bounds that only depend on epsilon but that ignore the structure of the data. A natural question is whether we can do better than state-of-the-art when the data is well structured, in particular, when the optimal approximate convex hull is small. 

We show lower bounds for this problem to justify that it is hard. We then propose two interesting relaxations of the problem. In the first relaxation the data is randomly permuted before the algorithm runs. In the second relaxation our approximation only needs to be correct in “most” directions. We  come up with new streaming algorithms and theorems for these relaxations.

