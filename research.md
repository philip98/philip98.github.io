---
layout: default
title: Philip Schlösser — Research
permaling: /research
---
# Research
I am researching matrix spherical functions for symmetric pairs (of Lie groups)
and quantum symmetric pairs (of a quantum group and a coideal subalgebra).

## Matrix Spherical Functions for Symmetric Pairs
More concretely, if \\(G\\) is a Lie group and \\(K\le G\\) is a subgroup such that
there is an involutive automorphism \\(\Theta\\) of \\(G\\) with
\\[
    (G^\Theta)_0 \le K\le G^\Theta,
\\]
then \\((G,K)\\) is a symmetric pair. Given two finite-dimensional \\(K\\)-modules
\\(V,W\\), we can then consider functions \\(f: G\to\operatorname{Hom}(V,W)\\)
satisfying
\\[
    \forall g\in G, k,k'\in K:\quad
    f(kgk') = \pi_W(k) f(g) \pi_V(k').
\\]
These functions are called *matrix spherical functions* and we can equivalently
view them as equivariant sections of the associated vector bundle for the
principal \\(K\\)-bundle \\(G\to G/K\\) over the symmetric space \\(G/K\\) and the 
\\(K\\)-representation \\(\operatorname{Hom}(V,W)\\) (only considering the right
action).

In the case of \\(V,W\\) being the trivial representation, these functions are
known[^heckman] to be Heckman–Opdam hypergeometric functions (and in particular
Jacobi polynomials for compact symmetric pairs), and similar statements hold
true for other one-dimensional representations[^casimir]. For higher-dimensional 
representations, however, it is unclear how and if matrix spherical functions
are connected to Heckman–Opdam theory.

In my upcoming preprint[^casimir] with Mikhail Isachenkov we undertake steps towards this
question by devising a radial part decomposition for invariant differential
operators even for cases where \\(K\\) is non-compact.

## Matrix Spherical Functions for Quantum Symmetric Pairs
It can be shown that on the Lie algebra side there is a classification of all
possible symmetric pairs in terms of Satake diagrams. Given such a
Satake diagram, it is possible[^kolb] to construct a Drin'feld–Jimbo quantum group
\\(U\\) and a parameter-dependent coideal subalgebra \\(B\\) that in the \\(q\to1\\)
limit specialise to \\(U(\mathfrak{g}),U(\mathfrak{k})\\), respectively. Such
a pair \\((U,B)\\) is called a *quantum symmetric pair*.

We can follow the same definition as for symmetric pairs to define
matrix spherical functions for quantum symmetric pairs (now using two 
finite-dimensional \\(B\\)-modules). For the case of \\(V,W\\) being trivial
representations, it is known[^letzter] that the matrix spherical functions are
symmetric Macdonald polynomials, and similarly, for other one-dimensional 
representations, my colleague [Stein Meereboer][stein] recently showed the same.

Furthermore, I managed to show that matrix spherical functions for the quantum
symmetric pair associated with \\((SO(2n+2), SO(2n+1))\\) 
(non-commutative \(2n+1\)-sphere) and the spin representation can be interpreted
as non-symmetric Macdonald polynomials for an affine root system of type \\(A_1\\).

----

[^heckman]: Gerrit Heckman and Henrik Schlichtkrull: *Harmonic analysis 
    and special functions on symmetric spaces*, 1994

[^casimir]: Philip Schlösser and Mikhail Isachenkov: *Casimir Radial Parts via 
    Matsuki Decomposition*, 2024. To appear.

[^kolb]: Stefan Kolb: *Quantum symmetric Kac-Moody pairs*, 2014.
    [arXiv](https://arxiv.org/abs/1207.6036)

[^letzter]: Gail Letzter: *Quantum zonal spherical functions and 
    Macdonald polynomials*, 2004. [arXiv](https://arxiv.org/abs/math/0210447)

[stein]: https://sites.google.com/view/steinmeereboer/stein "Stein's homepage"
