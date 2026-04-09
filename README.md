This repository contains the source of the **O27 Cosmochrony paper**  
[*Quaternionic Rigidity of Admissible Morphisms:
Every Admissible $\Phi_{q,\rho}$ Necessarily Factors through $\mathfrak{su}(2)$*](out/SpectralO27.pdf). :contentReference[oaicite:0]{index=0}

This work extends the **spectral admissibility sub-programme** by resolving the
main structural hypothesis left open in **O26**.

It addresses the next question after the quadratic completion of the pair observable:

> Given the pair observable $\sigma_{\mathrm{pair}}$ and its quadratic interpretation,
> does there exist a canonical admissible morphism
> \[
> \Phi_{q,\rho}: V_q \to V_\rho
> \]
> and, if so, is its target structure uniquely determined?

## Quick Summary

O27 proves that the answer is yes, and stronger than expected.

The admissible morphism is not merely existent or convenient.

It is **rigid**.

More precisely:

- every admissible $\Phi_{q,\rho}$ factors through the admissible quotient
- the intermediate target is forced to be the three-dimensional real Lie algebra
  $\mathfrak{su}(2)$
- the quaternionic structure is not optional, but uniquely imposed by the three
  defining constraints
- the canonical factorisation
  \[
  \Phi_{q,\rho} = \rho \circ \iota \circ \pi
  \]
  is proved unique up to unitary equivalence

This turns the representation-theoretic layer of the programme from a conjectural
embedding into a **rigidity theorem**. :contentReference[oaicite:1]{index=1}

## Context

**O16–O26** established that:

- the correct observable is the canonical pair quantity
  $\sigma_{\mathrm{pair}}^{\mathrm{can}}(n)$
- the exponent $\delta_{\mathrm{pair}} \approx 7.44$ lies in the admissible window
  $[7.4, 10.6]$
- the transfer chain $c_\chi \to \delta_{\mathrm{pair}} \to \beta^*$
  holds unconditionally (**O24**)
- $\delta_{\mathrm{pair}}$ is numerically stable and structurally invariant (**O25**)
- $\sigma_{\mathrm{pair}}$ behaves as a quadratic object, consistent with a
  Hilbert–Schmidt norm (**O26**)

However:

- the admissible morphism $\Phi_{q,\rho}$ was still only a hypothesis in **O26**
- the target structure of that morphism was not yet derived
- the role of the quaternionic / $SU(2)$ sector was still interpretative rather than
  rigidly forced

This defines the scope of **O27**. :contentReference[oaicite:2]{index=2}

## Core Result

The paper establishes that:

> Any morphism $\Phi_{q,\rho}$ satisfying involution equivariance, quadratic
> compatibility with $\sigma_{\mathrm{pair}}$, and naturality with respect to
> admissibility necessarily factors through $\mathfrak{su}(2)$.

Equivalently:

- admissibility forces factorisation through the quotient
  $\pi: V_q \twoheadrightarrow H_{\mathrm{eff}}$
- O23 identifies
  $H_{\mathrm{eff}} \simeq \mathfrak{su}(2)$
- any admissible target representation must therefore be an $SU(2)$-representation
  space

Thus the quaternionic sector is not one admissible realisation among others.

It is the **unique minimal admissible target**. :contentReference[oaicite:3]{index=3}

## Main Structural Results

### 1. Universality of the admissible quotient

*Result.* Any morphism natural with respect to admissibility must vanish on
$\ker \Pi_{\mathrm{adm}}$, hence factors uniquely through the admissible quotient:

$\pi: V_q \twoheadrightarrow H_{\mathrm{eff}} = V_q / \ker \Pi_{\mathrm{adm}}$.

Thus:

- non-admissible directions are invisible to any admissible morphism
- naturality becomes an exact factorisation principle
- the quotient is universal for the problem

This is the key categorical step of the paper. :contentReference[oaicite:4]{index=4}

### 2. Elimination of non-quaternionic candidates

*Result.* No abelian target and no generic Hilbert target can satisfy the three constraints
simultaneously unless it carries a compatible quaternionic structure.

Thus:

- abelian targets are excluded by the non-commutativity of the admissible neutral
  traceless sector
- arbitrary complex Hilbert spaces may realise norm and conjugation, but fail
  naturality unless they contain the correct $SU(2)$ structure
- the only surviving candidate is the quaternionic one

The comparison is explicit in the paper through the compatibility table for
$\mathbb{R}^n$, $\mathbb{C}^n$, arbitrary Hilbert spaces, and
$\mathbb{H} / \mathfrak{su}(2)$. :contentReference[oaicite:5]{index=5}

### 3. Quaternionic rigidity theorem

*Result.* Any admissible morphism satisfies:

$\Phi_{q,\rho}: V_q \to V_\rho \quad \Longrightarrow \quad V_q \xrightarrow{\;\pi\;} H_{\mathrm{eff}} \xrightarrow{\;
\iota\;} \mathfrak{su}(2) \xrightarrow{\;\rho\;} V_\rho.$

Thus:

- the morphism necessarily factors through the admissible quotient
- the intermediate real structure is necessarily $\mathfrak{su}(2)$
- the target $V_\rho$ must be an $SU(2)$-representation space

This upgrades O23 from a dimension statement to a universality statement:
the integer $3$ is not merely observed, but structurally forced. :contentReference[oaicite:6]{index=6}

### 4. Canonical construction and uniqueness

*Result.* The canonical admissible morphism is:

\[
\Phi_{q,\rho} = \rho \circ \iota \circ \pi.
\]

It satisfies all three defining constraints:

- involution equivariance
- quadratic compatibility
- naturality with respect to admissibility

Moreover, it is unique up to unitary equivalence.

Thus:

- the admissible morphism is canonical
- the remaining ambiguity is only representation-theoretic conjugacy
- no pipeline-dependent freedom remains at the structural level

This closes the main open hypothesis of O26. :contentReference[oaicite:7]{index=7}

### 5. Representation-theoretic meaning of $\beta^*$

*Result.* Once $\Phi_{q,\rho}$ is rigidly fixed, the pair observable is interpreted as a
Hilbert–Schmidt norm along a trajectory in $\mathrm{End}(V_\rho)$, and
$\beta^*$ acquires a representation-theoretic meaning.

Thus:

- $\delta_{\mathrm{pair}}$ is no longer only a scaling exponent of an observable
- $\beta^*$ becomes the effective norm-growth exponent in the minimal admissible
  non-abelian sector
- the chain $c_\chi \to \delta_{\mathrm{pair}} \to \beta^*$
  gains a representation-theoretic interpretation

This is the conceptual completion delivered by O27. :contentReference[oaicite:8]{index=8}

## Foundational Chain from the Substrate

The derivation is fully internal:

Born–Infeld admissibility  
$\to$ pair observable (**O16–O21**)  
$\to$ projection locking (**O22**)  
$\to$ quaternionic structure (**O23**)  
$\to$ rank stability (**O24**)  
$\to$ numerical validation (**O25**)  
$\to$ quadratic completion (**O26**)  
$\to$ quaternionic rigidity of admissible morphisms (**O27**)

No external symmetry principle is imposed by hand.

The $\mathfrak{su}(2)$ structure appears as the unique fixed point of the admissibility
constraints. :contentReference[oaicite:9]{index=9}

## Mathematical Role of O27

**O27** provides the structural completion of the representation-theoretic layer:

- defines naturality in admissibility-theoretic terms
- proves universality of the admissible quotient
- excludes non-quaternionic target structures
- proves that every admissible morphism factors through $\mathfrak{su}(2)$
- constructs the canonical morphism explicitly
- proves uniqueness up to unitary equivalence
- gives $\beta^*$ a representation-theoretic interpretation

More precisely, the paper:

- turns the O26 hypothesis on $\Phi_{q,\rho}$ into a theorem
- upgrades O23 from dimension to universality
- closes the structural gap between quadratic observables and admissible
  representation theory
- makes the $SU(2)$ thread mathematically necessary rather than suggestive

## Epistemic Structure of the Paper

### Established input

- pair observable (**O16–O21**)
- fibre structure and normalisation (**O17–O19**)
- projection locking (**O22**)
- quaternionic admissibility (**O23**)
- rank stability (**O24**)
- numerical validation (**O25**)
- quadratic interpretation (**O26**)

### New results

- formal definition of naturality
- universality of the admissible quotient
- exclusion of non-quaternionic targets
- quaternionic rigidity theorem
- canonical factorisation
- uniqueness up to unitary equivalence
- representation-theoretic interpretation of $\beta^*$

### Remaining open problems

- identification of the correct irreducible sector $\rho$ from O25 data
- verification of the effective dimension $r_{\mathrm{eff}} = d_\rho^2$
- explicit numerical selection between admissible irreducible sectors
- analytical derivation of the realised sector from admissibility alone

## Interpretation of the Result

The conceptual shift is:

- previous view: the $SU(2)$ thread was the best admissible candidate
- O27: the quaternionic / $\mathfrak{su}(2)$ structure is **forced**

Thus:

- the representation-theoretic layer is no longer conjectural at the structural level
- the admissible morphism is not chosen, but derived
- the non-abelian sector is not optional, but necessary
- $\mathfrak{su}(2)$ becomes the unique minimal target compatible with emergence,
  non-injectivity, pair structure, and quadratic admissibility

## Structural Role of O27

**O27** completes the representation-theoretic hierarchy:

- **O16**: pair observable
- **O17–O19**: fibre structure
- **O20–O21**: persistence and shell-level saturation
- **O22**: projection locking
- **O23**: quaternionic structure
- **O24**: rank stability
- **O25**: numerical validation
- **O26**: quadratic completion
- **O27**: rigidity of admissible morphisms

Thus:

- the observable is identified
- its scaling is validated
- its quadratic structure is established
- its admissible target is derived uniquely

## What O27 Adds

- formal admissibility-based naturality
- universal quotient formulation
- rigidity of admissible morphisms
- derivation of the $\mathfrak{su}(2)$ target
- canonical factorisation
- uniqueness up to unitary equivalence
- representation-theoretic interpretation of $\beta^*$

## Outcome

The spectral admissibility framework is now:

- structurally grounded (**O24**)
- numerically validated (**O25**)
- quadratically completed (**O26**)
- representation-theoretically rigid (**O27**)

The admissible morphism is:

- canonical
- intrinsic
- quotient-induced
- quaternionically forced
- unique up to unitary equivalence

## Residual Open Problems

### Irreducible sector selection

Identify which irreducible sector $\rho$ of $2I$ is realised by the O25 covariance data.

### Effective dimension test

Determine whether:
\[
r_{\mathrm{eff}} = d_\rho^2
\]
and identify the realised value of $d_\rho$.

### Sector derivation

Derive the realised representation sector directly from admissibility, rather than from
post hoc covariance testing.

### Large-$q$ regime

Verify stability of the effective dimension and sector selection at larger primes.

## Status

The programme is now:

- structurally closed at the observable-rank level (**O24**)
- numerically consolidated at the pair level (**O25**)
- quadratically interpreted (**O26**)
- rigidly lifted to $\mathfrak{su}(2)$ (**O27**)

The remaining problem is no longer structural existence.

It is **sector identification inside the now-forced admissible representation class**.

## Repository Structure

```text
paper/
├── out/      # Compiled O27 PDF
├── tex/      # LaTeX sources
└── README.md
```
# Citation

If you reference this work, please cite:

J. Beau: Quaternionic Rigidity of Admissible Morphisms:
Every Admissible $\Phi_{q,\rho}$ Necessarily Factors through $\mathfrak{su}(2)$
Zenodo, 2026.

# Acknowledgements

Portions of the conceptual synthesis, structural organisation, and editorial refinement
benefited from iterative interactions with large language models used as analytical assistants.

All theoretical results, computations, and interpretations remain the sole responsibility
of the author.

# Contributions

This repository is intended as a research reference.

Critical feedback, independent verification, and further analysis of:

- admissible morphisms
- quaternionic rigidity
- quotient factorisation
- irreducible sector selection
- covariance dimension tests
- representation-theoretic admissibility

are welcome.

Please open an issue to discuss conceptual points, technical details, or possible
extensions.
