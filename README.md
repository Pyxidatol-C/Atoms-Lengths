A structure 𝔸:
- is _oligomorphic_ if $\text{ 𝔸}^d$ has finitely many orbits under the automorphism group of 𝔸 for $d = 1, 2, \dots$;
- is _finitely homogeneous_ if it is a first-order reduct of a homogeneous structure in a finite relational vocabulary.
- has the _ascending chain property (ACP)_ if $\text{Lin}_F\text{ 𝔸}^d$ is Noetherian for $d = 1, 2, \dots$ over any field $F$;
- has the _finite length property (FLP)_ if $\text{Lin}_F\text{ 𝔸}^d$ has finite length for $d = 1, 2, \dots$ over any field $F$;
- has _FLP/fin_ (resp., _FLP/0_) if it has the finite length property over all finite fields (resp., fields of characteristic 0).

![the length-scape](Lengthscape.png)

**Conjectures:**
1. oligomorphic => ACP

2. finitely homogeneous (blurred in figure above) => FLP

3. oligomorphic => FLP/0

Conjecture 1 was raised [by Evans and Camina in 1991](https://doi.org/10.1093/qmath/42.1.15) and [by Bojańczyk et al. in 2021](https://arxiv.org/abs/2104.02438).
Positive answers can be obtained by providing [Ahlbrandt–Ziegler enumerations](https://doi.org/10.1016/0168-0072(86)90037-0) for $\text{ 𝔸}^d$ or by showing 𝔸 is [ω-well-structured (Ghosh and Lasota'24)](https://arxiv.org/abs/2402.17604).

Conjecture 2 can — through the manipulation of _cogs_ — be confirmed for free amalgamation classes, in a binary vocabulary, expanded with a generic total order.
David Evans pointed out in 2025 that a failure of "finitely homogeneous => FLP/fin" would refute Simon Thomas's conjecture on first-order reducts. 
Using a Ramsey-theoretic technique, he also proved $\text{Lin}_F\text{ 𝔸}^2$ has finite length without our arity assumption. 
(To show cogs span balanced vectors, he shows a finitely supported cog-killer kills balanced vectors.) 

Conjecture 3 appears to be new. 
We have positive results for a generalisation of smoothly approximated structures: 
by using Maschke's Theorem, we can bound the length of chains by the number of orbits.
In particular, we establish FLP/0 for some structures that are not finitely homogeneous and indeed do not have FLP/fin.

Below is a selection of concrete structures and the length-scape.

| class of finite structures | Fraïssé limit | ACP | FLP | FLP/0 |
| --- | --- | --- | :--: | --- |
| sets | (ℕ, =) | ✅ | ✅ | ✅ |
| total orders | (ℚ, ≤) | ✅ | ✅ | ✅ |
| partial orders | (ℙ, ⊑) |  |  |  |
| equivalence relations | (⨆<sub>∞</sub> K<sub>∞</sub>, E) | ✅ | ✅ | ✅ |
| graphs | (Rado graph, E) | ✅ | ✅ | ✅ |
| △-free graphs | (Henson graph, E) | ✅ | ✅ | ✅ |
| ordered graphs | (ordered Rado graph, ≤, E) | ✅ | ✅ | ✅ |
| tournaments | (…, →) | ✅ | ✅ | ✅ |
| 3-hypergraphs | (…, E<sub>3</sub>) |  | 🤔 |  |
| 𓉴-free 3-hypergraphs | (…, E<sub>3</sub>) |  |  |  |
| meet-trees | (𝕋, ∧, ≤) | ✅ |  |  |
| vector spaces over F<sub>2</sub> | F<sub>2</sub> ⊕ F<sub>2</sub> ⊕ F<sub>2</sub> ⊕ F<sub>2</sub> ⊕ ⋯ | ✅ | ❌ over F<sub>2</sub> | ✅ |
| symplectic spaces over F<sub>2</sub> | (F<sub>2</sub> ⊕ F<sub>2</sub>) ⊕ (F<sub>2</sub> ⊕ F<sub>2</sub>) ⊕ ⋯ |  | ❌ over F<sub>2</sub> | ✅ |
| Boolean algebras | clopens of 2<sup>ℕ</sup> |  | ❌ over F<sub>2</sub> |  |
| | | | |
| **free amalgamation class,**<br/>**over a binary vocabulary,**<br/>**expanded with all total orders** |  | ✅ | <= ✅ => | ✅ |
|  | **ω-well structured & ordered**<br/>or: **AZ enumerations** of $\text{𝔸}^d$ | ✅ | | |
|  | **oligomorphically approximated**<br/>e.g. **smoothly approximated** | | | ✅ |
