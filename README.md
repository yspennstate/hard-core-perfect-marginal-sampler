# Constant-time perfect marginal sampling for the hard-core model below the tree threshold

Yitzchak Shmalo

Fix Δ ≥ 3 and a rational activity λ below the uniqueness threshold λ_c(Δ) of the infinite Δ-regular tree. On any finite graph of maximum degree Δ with any feasible pinning, the algorithm in this paper outputs the spin of a given vertex with exactly its conditional hard-core marginal law, in O(1) expected time, where the constant depends on Δ and λ. It runs a branching recursion on the self-avoiding-walk tree, and it resolves each node by an exact rejection step between the endpoints of a short interval around an approximate value of the node's ratio. The Li–Lu–Yin potential makes the expected number of recursive calls of each node less than one. Combined with the reduction of Chen, Chen, Liu and Zhang, this approximates the hard-core partition function to any fixed relative accuracy in expected time n^(2−x), up to polylogarithmic factors, for some x = x(Δ, λ) > 0.

## Contents

- `main.tex`, `main.pdf`: the paper (11 pages).
