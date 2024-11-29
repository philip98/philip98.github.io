---
layout: default
title: Philip Schlösser — Education
permalink: /education
---
# Education
## Primary and Secondary Education
I underwent German primary and secondary education at 84. Grundschule Dresden-Hellerau, Marie-Curie-Gymnasium Dresden, and Michaeli Gymnasium München.
I graduated in 2016.

## Bachelor
I obtained a Bachelor of Science in physics at the [University of Konstanz][kn],
where I studied 2016–2019 and graduated in 2019.

Throughout my studies I took numerous maths courses: those that were required
for physicists (analysis 1–3, linear algebra 1, and one more which is chose to
be functional analysis) but also a lot more that I took out of interest.
In the end I decided against also attaining a bachelor's in maths because I had
already been admitted to the maths MSc programme in Amsterdam.

I wrote my bachelor thesis under supervision of [Guido Burkard][burkard]. It is
entitled ["Geometrische Phasen in exchange-only Qubits"][bthesis] 
('Geometric Phases in Exchange-Only Qubits') 
and I sought to realise quantum gates as Berry phases.

For that you view a parameter-dependent Hamilton operator on a
finite-dimensional state space \\(V\\) as a matrix function 
\\(\mathcal{H}:\mathcal{M}\to\operatorname{End}(V)\\)
on the manifold \\(\mathcal{M}\\) of parameters, and consider a subbundle
\\(E\to\mathcal{M}\\) of the trivial vector bundle with fibre \\(V\\) such that for
each \\(\lambda\in\mathcal{M}\\), the fibre \\(E_\lambda\\) is an eigenspace of
\\(\mathcal{H}(\lambda)\\).
If we now consider a system that starts out in a state in \\(E_\lambda\\) and
slowly change the parameter, then according to the adiabatic theorem and
ignoring dynamic phases, the time evolution of that system is described using
parallel transport with the projection of the trivial connection. Since the
vector bundle is not trivial, the projection of the trivial connection may have
monodromy or even curvature, which are referred to as *geometric* or
*Berry phase*.

## Master
I obtained two Masters of Science: one in physics, one in maths from the
[University of Amsterdam][uva], where I studied 2019–2022 and graduated in 2022.

During my studies I took numerous courses focussing on condensed matter,
quantum field theory, general relativity, string theory, geometry, functional
analysis, topology, and stochastics.

I wrote my master thesis under supervision of [Mikhail Isachenkov][isachenkov]
and [Hessel Posthuma][posthuma]. It is entitled 
['Spinorial Conformal Blocks: Dirac Action and Integrability'][mthesis]. 
In it I considered the symmetric pair
\\((G,H)=(SO(p+1,q+1)_0, SO(p,q)_0)\times SO(1,1)_0)\\) 
(note that neither \\(G\\) nor \\(K\\) are usually compact) and its matrix-spherical
functions, i.e. those functions \\(f: G\to \operatorname{Hom}(V,W)\\) for \\(H\\)-modules \\(V,W\\)
such that
\\[ \forall k,h\in H, g\in G: \quad f(kgh) = \pi_W(k)f(g)\pi_V(h). \\]
This question is relevant to physics as 4-point functions in CFT, i.e.
correlation functions of four conformal fields, can be described using such
functions. Here the \\(H\\)-modules \\(V,W\\) correspond to the Lorentz
representations describing the four fields. Describing/finding the
eigenfunctions of invariant differential operators corresponds to finding the
fundamental matrix-spherical functions (i.e. those obtained by projecting a
\\(G\\)-representation). In the language of physics these are called *conformal 
blocks* and have been an active field of study for a while.

In the case that \\(V\\) is one-dimensional, I computed the radial part of the
quadratic Casimir element and linked (as has first been established
[by Isachenkov and Schomerus][superintegrability]) it to the modified Lagrangian
of Heckman–Opdam theory, which usually appears as the radial part of the
quadratic Casimir element in the setting of a symmetric pair \\((G,K)\\) where
\\(K\\) *is* compact. I explore and explain this correspondence in an upcoming
preprint with Isachenkov. This shows that conformal blocks are Heckman–Opdam 
hypergeometric functions.

Additionally, I considered the case of spherical functions mapping not to
\\(\operatorname{Hom}(V,W)\\) for finite-dimensional \\(H\\)-module \\(V,W\\), but to
\\(\operatorname{Hom}(V,W)\otimes S\\), where \\(S\\) carries the spin
representation of an appropriate Clifford algebra. We can then consider the
action of Kostant's cubic Dirac operator on such spherical functions and obtain
a radial part that can also be related to Dunkl operators acting on
Weyl-(anti)invariant functions.

[kn]: https://uni.kn "Webpage of Uni Konstanz"
[burkard]: https://orcid.org/0000-0001-9053-2200 "ORCID of Guido Burkard"
[bthesis]: /assets/pdf/Geometrische_Phasen_in_eo_Qubits.pdf "PDF of my bachelor thesis"
[uva]: https://uva.nl "Webpage of UvA"
[isachenkov]: https://www.uva.nl/en/profile/i/s/m.isachenkov/m.isachenkov.html "Staff homepage of Mikhail Isachenkov"
[posthuma]: https://orcid.org/0000-0001-5164-7355 "ORCID of Hessel Posthuma"
[mthesis]: /assets/pdf/Spinorial_Conformal_Blocks.pdf "PDF of my master thesis"
[superintegrability]: https://arxiv.org/abs/1602.01858 "Superintegrability of \\(d\\)-dimensional Conformal Blocks"
