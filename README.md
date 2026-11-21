This repository contains the source of the **O27 Cosmochrony paper**  
*Admissible Morphisms on the Weil Pair Sector:
The $\mathfrak{su}(2)$ Action on $\mathrm{End}(V_\rho)$ and the Open Vector Lift*.

This work belongs to the **spectral admissibility sub-programme**.
It addresses the question raised by the quadratic completion of the pair observable in **O26**:

> Given the pair observable $\sigma_{\mathrm{pair}}$ and its quadratic interpretation,
> what is forced about a morphism out of the Weil pair space, and what is not?

## Quick Summary

The paper separates what the admissibility constraints prove from what they leave open.

What is proved:

- a morphism whose kernel contains $\ker \Pi_{\mathrm{adm}}$ factors uniquely, **as a real-linear
  map**, through the admissible quotient
  $\pi : V_q \twoheadrightarrow \mathcal{Q} = V_q / \ker \Pi_{\mathrm{adm}}$
- under the spinor carrier supplied by **O23**, the complex intertwiner space
  $\mathrm{Hom}_{\mathfrak{su}(2)}(\mathbf{3}_{\mathbb{C}}, \mathrm{End}(V_\rho))$ is
  one-dimensional. Adding the saturation hypothesis below, an equivariant map is then unique
  **up to a scalar** that the quadratic condition, being a proportionality, does not fix
- there is no non-zero $\mathfrak{su}(2)$-equivariant map from the adjoint to the fundamental:
  $\dim \mathrm{Hom}_{\mathfrak{su}(2)}(\mathbf{3}_{\mathrm{ad}}, \mathbf{2}_{\mathrm{fund}}) = 0$

What is not proved, and is stated as such:

- the three constraints do **not** impose $\mathfrak{su}(2)$-equivariance; an explicit countermodel
  $\Phi_T = \rho \circ T \circ \iota \circ \pi$ satisfies them and is not a scalar multiple of the
  canonical map
- reaching $H_{\mathrm{eff}} = \mathrm{Im}\,\Pi_{\mathrm{adm}} \cap \mathrm{Ntrl}$ from the
  quotient, and carrying O23's dimension count over to it, are together **one hypothesis**,
  $\mathrm{Im}\,\Pi_{\mathrm{adm}} = \mathrm{Ntrl}$ (*admissible saturation*), assumed and
  derived nowhere.
  O23 proves $\dim_{\mathbb{R}} \mathfrak{su}(V_\rho) = 3$ for $\mathrm{Ntrl}$; it never
  mentions $H_{\mathrm{eff}}$, $\Pi_{\mathrm{adm}}$ or the admissible quotient
- that the parity involution descends to $H_{\mathrm{eff}}$ and acts there by $\mathrm{Ad}(g_0)$,
  for a non-central $g_0$, is a **second hypothesis** (*parity transport*). It presupposes
  saturation in order to be stated at all, but does not follow from it
- the quadratic condition is **not** established for the canonical map: nothing here makes $\pi$ an
  isometry
- **O26** Hypothesis 4.4, which asks for a canonical linear map
  $\mathcal{V}_q \to V_\rho$ into the spin-$\tfrac{1}{2}$ space, **remains open**

## Context

**O16--O26** provide:

- the pair observable $\sigma_c(n)\,\sigma_{q-c}(n)$ used here, uncorrected (the canonical
  normalisation proposed in **O19** has open tests)
- the reference value $\delta_{\mathrm{pair}} \approx 7.44$ lies in the historical
  phenomenological window $[7.4, 10.6]$
- vertical fibre structure does not change the observable rank (**O24**)
- the pair statistic concentrates across conjugate pairs at fixed $q$ (**O25**)
- $\sigma_{\mathrm{pair}}$ behaves as a quadratic object, consistent with a
  Hilbert--Schmidt norm (**O26**)

**O26** left the existence of a canonical assignment
$\Phi_{q,\rho} : \mathcal{V}_q \to V_\rho$ as its Hypothesis 4.4.
That hypothesis is the subject of this paper, and it is not resolved by it.

## The Three Conditions

The paper works with three conditions on a morphism out of $V_q$.
They are this paper's reading, and they are not verbatim the clauses of O26 Hypothesis 4.4:

- **(a) Involution equivariance** under $c \leftrightarrow q-c$, the involution acting on $V_q$ by
  complex conjugation.
  That it descends to $H_{\mathrm{eff}}$, and that the descended map is $\mathrm{Ad}(g_0)$ for some
  $g_0 \in \mathrm{SU}(2)$, are the **parity transport hypothesis**; neither is derived.
  A general linear involution of a real three-dimensional space is not of that form: a reflection
  with a one-dimensional $(-1)$-eigenspace has determinant $-1$.
  What is settled is what the transported involution cannot be. It is not $X \mapsto -X$: on a
  non-abelian Lie algebra negation is an anti-automorphism, since $[-X,-Y] = [X,Y]$.
  And the lift has order four, not two: $g_0^2 = -\mathrm{Id}$, for instance $g_0 = i\sigma_2$.
- **(b) Quadratic compatibility** with $\sigma_{\mathrm{pair}}$, in the Hilbert--Schmidt norm carried
  by the target $\mathrm{End}(V_\rho)$.
- **(c) Factorisation through admissibility**: $\ker \Pi_{\mathrm{adm}} \subseteq \ker \Phi_{q,\rho}$.
  This is a statement about the kernel and nothing more.
  It does not imply frame independence, and it does not imply equivariance.

O26's naturality clause asks instead for independence of the pair $\{c, q-c\}$ and of the shell
index $n$.
Condition (c) replaces that clause; the two are different requirements, and neither is derived from
the other here.

## Main Results

### 1. Universality of the admissible quotient

Condition (c) is exactly $\ker \Pi_{\mathrm{adm}} \subseteq \ker \Phi$, so $\Phi$ descends uniquely
to $\mathcal{Q} = V_q / \ker \Pi_{\mathrm{adm}}$.
The lemma restates condition (c) in usable form and adds nothing to it.
Its target is $\mathcal{Q}$, not $H_{\mathrm{eff}}$.

### 2. Factorisation and the equivariant Schur counts

Under (a)--(c), $\Phi_{q,\rho}$ factors uniquely as a real-linear map through
$\pi : V_q \to \mathcal{Q}$; this carries no equivariance.

Assuming in addition the O23 carrier, so $V_\rho \cong \mathbb{C}^2$ and
$\mathrm{Ntrl} = \mathfrak{su}(V_\rho)$:

- $\rho : \mathfrak{su}(2) \to \mathrm{End}(V_\rho)$ is equivariant
- $\mathrm{Hom}_{\mathfrak{su}(2)}(\mathbf{3}_{\mathbb{C}}, \mathrm{End}(V_\rho))$ is
  one-dimensional over $\mathbb{C}$, since
  $\mathrm{End}(\mathbb{C}^2) \cong \mathbf{3} \oplus \mathbf{1}$; the corresponding space of
  real-linear intertwiners has real dimension two, by the adjunction
  $\mathrm{Hom}_{\mathbb{R}}(W,U) \cong \mathrm{Hom}_{\mathbb{C}}(W \otimes_{\mathbb{R}}
  \mathbb{C}, U)$
- $\dim \mathrm{Hom}_{\mathfrak{su}(2)}(\mathbf{3}_{\mathrm{ad}}, \mathbf{2}_{\mathrm{fund}}) = 0$

The last two are statements about **equivariant** maps only.
They do not classify the maps that merely satisfy (a)--(c).
The intertwiner counts hold for every non-trivial irreducible $\rho$, that is every
$d_\rho \geq 2$, by Clebsch--Gordan multiplicity one; they fail for the trivial representation
$d_\rho = 1$, where $\rho|_{\mathfrak{su}(2)} = 0$.

### 3. The constraints do not impose equivariance

Assume parity transport, so $P = \mathrm{Ad}(g_0)$. Equip $\mathfrak{su}(2)$ with the form
$X \mapsto \|\rho(X)\|_{\mathrm{HS}}^2$, positive definite and $\mathrm{Ad}$-invariant for
$d_\rho \geq 2$, hence proportional to the Euclidean form and invariant under reflections too.
Being $\mathrm{Ad}$-invariant it makes $P$ orthogonal, so the $(-1)$-eigenspace of a non-trivial
$\mathrm{Ad}(g_0)$ is a two-dimensional orthogonal summand.
Let $T$ be a reflection inside it, extended by the identity: orthogonal, non-scalar, commuting with
$P$.
Then $\Phi_T = \rho \circ T \circ \iota \circ \pi$ has the same kernel, the same Hilbert--Schmidt
norm and the same parity equivariance as $\rho \circ \iota \circ \pi$, and is not a scalar multiple
of it.

Consequently the uniqueness statement requires $\mathfrak{su}(2)$-equivariance **of the descended
map** $\bar\Phi : H_{\mathrm{eff}} \to \mathrm{End}(V_\rho)$ as an explicit hypothesis, stated
there because no $\mathfrak{su}(2)$-action on $V_q$ is defined anywhere.
The impossibility count excludes an equivariant adjoint-factorising realisation of O26 Hypothesis
4.4, not every quotient-factorising linear lift.

### 4. What the three constraints do not determine

A three-dimensional real **non-abelian** Lie algebra carrying a positive-definite
$\mathrm{Ad}$-invariant form is the compact form $\mathfrak{su}(2)$.
The non-abelian hypothesis is not decorative: $\mathbb{R}^3$ carries such a form as well, its
adjoint action being trivial.
Condition (b) supplies a positive-definite quadratic form; whether that form is
$\mathrm{Ad}$-invariant is not established, and neither is non-abelianness of the carrier.

### 5. Canonical construction and its conditional consequence

The canonical map is
$\Phi_{q,\rho} = \rho \circ \iota \circ \pi : V_q \to \mathrm{End}(V_\rho)$.
It satisfies (c) unconditionally, and (a) under the parity transport hypothesis.
Whether it satisfies (b) is **not** settled: neither kernel factorisation nor the universal
property makes $\pi$ an isometry.

Subject to (b), $\delta_{\mathrm{pair}}$ is the decay exponent of a Hilbert--Schmidt trajectory in a
representation space factoring through $\mathfrak{su}(2)$.
This does not imply $\beta^* = 1/(\delta_{\mathrm{pair}} + \tfrac{1}{2})$: that reciprocal requires a
distinct cross-substrate growth hypothesis, refuted for the two native realisations in the frozen
corpus.

## Type of the Implication Chain

The representation-side chain

$$\text{emergence} \Rightarrow \text{non-injectivity} \Rightarrow \text{pair structure}
\Rightarrow \text{quadratic form} \Rightarrow \mathfrak{su}(2)$$

has arrows of unequal type:

- the first is the no-go theorem of paper L
- the second is partly open: **O18** proves Born--Infeld parity as a response-family covariance, but
  the identification of the parity orbit with a fibre of O18's non-injective projection is a
  structurally motivated hypothesis (O18 Problem 2.8)
- the third is established in **O26**
- the last is the carrier supplied conditionally by **O23**, not a derivation from (a)--(c)

## Epistemic Structure

### Established input

- pair observable (**O16--O21**)
- conjugation identity (**O17**); the canonical normalisation of **O19** is an open proposal (the pair
  observable used here is uncorrected); fibre identification open (**O18**)
- projection locking (**O22**)
- conditional rank-three carrier (**O23** Theorem 3.1, supplied spinor carrier)
- rank stability (**O24**)
- numerical campaign (**O25**)
- quadratic interpretation (**O26**)

### Proved here

- unique real-linear factorisation through the admissible quotient $\mathcal{Q}$
- one-dimensionality of the complex intertwiner space, under the supplied carrier
- vanishing of $\mathrm{Hom}_{\mathfrak{su}(2)}(\mathbf{3}_{\mathrm{ad}}, \mathbf{2}_{\mathrm{fund}})$
- a countermodel showing that (a)--(c) do not impose equivariance

### Open

- **the vector lift.** O26 Hypothesis 4.4 remains open.
  The Schur count excludes an equivariant adjoint-factorising realisation; it excludes neither a
  non-equivariant quotient-factorising lift nor a map that does not factor through the quotient at
  all.
- **admissible saturation**, $\mathrm{Im}\,\Pi_{\mathrm{adm}} = \mathrm{Ntrl}$.
  Neither inclusion is established. Without $\subseteq$, the quotient $\mathcal{Q}$ is not the
  sector $H_{\mathrm{eff}}$; without $\supseteq$, O23's dimension count does not transfer to it.
  Every statement mentioning $H_{\mathrm{eff}}$ passes through this hypothesis, its own
  presupposition in the parity-transport hypothesis and in condition (a) included; the factorisation
  and the two Schur counts do not.
- **parity transport**, that the involution descends and acts by $\mathrm{Ad}(g_0)$ for a
  non-central $g_0$.
  Only the countermodel and condition (a) of the canonical map depend on it.
- **$\mathrm{Ad}$-invariance of the quadratic form**, together with a non-abelianness input for the
  carrier.
  Both would be needed to identify the carrier without the one supplied by O23.
- **realisation of $\pi$.** Approximating $\pi$ by the leading Gram--Schmidt basis vectors is not a
  realisation of it: **O25** reports $r_{\mathrm{eff}} = 2$ universally at $q \in \{29, 61\}$, an
  artefact of the DC mode dominating the projection.

## Repository Structure

```text
o27/
├── out/      # Compiled PDF, generated by compile.sh, git-ignored
├── tex/      # LaTeX sources and bibliography
├── compile.sh
└── README.md
```

Build with:

```bash
bash compile.sh
```

# Citation

If you reference this work, please cite the Zenodo concept DOI, which always resolves to the latest
version:

J. Beau: *Admissible Morphisms on the Weil Pair Sector: The $\mathfrak{su}(2)$ Action on
$\mathrm{End}(V_\rho)$ and the Open Vector Lift*, Zenodo, 2026,
[10.5281/zenodo.19489296](https://doi.org/10.5281/zenodo.19489296).

# Acknowledgements

Portions of the conceptual synthesis, structural organisation, and editorial refinement
benefited from iterative interactions with large language models used as analytical assistants.

All theoretical results, computations, and interpretations remain the sole responsibility
of the author.

# Contributions

This repository is intended as a research reference.

Critical feedback, independent verification, and further analysis of:

- admissible morphisms and quotient factorisation
- the open vector lift of O26 Hypothesis 4.4
- $\mathrm{Ad}$-invariance of the $\sigma_{\mathrm{pair}}$ form
- frame-independent realisations of $\pi$

are welcome.

Please open an issue to discuss conceptual points, technical details, or possible
extensions.
