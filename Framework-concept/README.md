# Framework Concept: Proof Machine Runtime

This document describes the current concept of the **proof machine framework runtime**.

The cleanest positioning is:

```text
Not an automatic prover by itself,
but a runtime that turns a candidate into a proof obligation,
then sends it to a formal court.
```

Core flow:

```text
Self / World / Task
  ↓
Master Tree
  ↓
KF operator runtime
  ↓
Observation / Lens / α locator
  ↓
Debt + GRC χ
  ↓
FCBTrace
  ↓
ProofMachine / Court Gate
  ↓
Lean / Formal verifier
```

Compressed statement:

```text
Lens sees.
α locates.
off-ridge generates debt.
χ routes liveness.
FCBTrace records and halts.
ProofMachine goes to court.
Lean gives final judgment.
ForgeLoop creates new methods when blocked, then returns them to court.
```

This matches the runtime law:

```text
candidate ≠ theorem
Ψ ≠ proof
```

A lens, numerical pattern, χ score, or α = 0 condition cannot directly become a theorem.

---

## 1. Outer Layer: Self / World / Task

The runtime does not begin by asking "how do we prove this?" It first fixes three layers:

```text
Self:
  Who is researching?
  What are the current memory, intent, ability, and boundary?

World:
  Which domain is active?
  Which frames, objects, invariants, and tools are available?

Task:
  What is the current objective?
  What counts as success or failure?
  What is the next proof obligation?
```

This prevents the proof machine from drifting. Every step tracks:

```text
Self = researcher / runtime operator
World = RH / zeta / alpha / Lean / runtime frame
Task = find locator, debt, bridge, lemma, formal statement
```

This is the `SWT = Self / World / Task` layer.

---

## 2. Main Spine: Master Tree

The main spine is:

```text
F−2 → F−1 → S → G ⇝ g ∋ KF(B,Q,η) ↷ Φ
  → O → Ψ → AEFP → Ω → a → outcome → FCBTrace → memory/promotion
```

Meaning:

```text
F−2 / F−1:
  Unknown pressure and pre-frame disturbance before formation.

S:
  Selected signal / candidate seed.

G:
  Grammar / lawful generation shell.

KF:
  Operator kernel that drives the runtime.

Φ:
  World-runtime state.

O:
  Observation surface.

Ψ:
  Semantic / mathematical candidate.

AEFP:
  Minimal event skeleton extracted from Ψ.

Ω:
  Decision bundle.

a:
  Action, expression, proof attempt, tool call, or writeback.
```

The only legal return path is:

```text
Ψ → (Π, Γ) → Φ
```

Any candidate that writes back into the runtime must pass through projection `Π` and constraint `Γ`. It cannot jump directly back into the lower frame.

---

## 3. Dynamics Layer: Six KF Operators

`KF` is the dynamic core of the runtime:

```text
KF = X_cl + X_D + X_G − X_Γ + X_L − X_S
```

The six operators are:

```text
X_cl:
  closure / repair / admissible return

X_D:
  decomposition / diffusion / propagation

X_G:
  generation / hypothesis growth

X_Γ:
  constraint / gate / admissibility cut

X_L:
  link / bridge / cross-frame connection

X_S:
  saturation / damping / false-attractor suppression
```

The proof machine is not merely "thinking of answers." It routes candidates through:

```text
generation → expansion → linking → constraint → false-closure suppression → repair into auditable form
```

This layer handles how to advance. It does not decide whether something has already been proved.

---

## 4. Semantic Skeleton: AEFP

Every candidate is compressed into:

```text
AEFP = (A, E, F, P)

A = actor / source
E = event / transition
F = frame / reference geometry
P = pattern / stable recurrence
```

For an RH-like task:

```text
A:
  Did the candidate come from numerics, lens, derivation, Codex, or Lean skeleton?

E:
  Is it moving from off-ridge to ridge?
  Or from local closure to bridge failure?

F:
  Which frame is active?
  α frame? A/C frame? Hardy Z frame? Lean frame?

P:
  Is there stable recurrence?
  α≈0? off-ridge debt? ridge gap not crossing zero?
```

AEFP preserves the minimal skeleton. It is not proof.

---

## 5. Locator / Debt Layer: α, Off-Ridge, GRC χ

In the RH-like version, `α` is the locator:

```text
α = Re(ρ) − 1/2
```

Interpretation:

```text
α = 0:
  candidate critical ridge / closure shell

α ≠ 0:
  off-ridge escape / residual source / debt generator
```

The core debt can be written as:

```text
D⊥(α;U)
=
1/(2U) ∫₀ᵁ [
  (e^{αu}−1)² + (e^{−αu}−1)²
] du

≈ (U²/3) α²
```

Then `GRC` evaluates candidate liveness:

```text
GRC = (G, R, C)

χ = G / (R · C + ε)
```

Route reading:

```text
χ < 1:
  dissipative; the signal cannot sustain itself.

χ ≈ 1:
  critical probe zone; worth turning into a proof obligation.

χ > 1:
  attractor or false-closure risk; requires stronger Γ / ghost / tail / bridge audit.
```

Therefore:

```text
α does not prove; α locates deviation.
off-ridge does not directly mean false; off-ridge generates debt.
χ does not judge truth; χ routes the candidate.
```

---

## 6. Record and Halt: FCBTrace

`FCBTrace` is the black-box recorder of the system:

```text
F = Frame
C = Closure
B = Basin
```

It records:

```text
frame_id
Π projection
Γ constraint
lens used
α state
debt terms
χ route
AEFP skeleton
unknown symbols
missing bridges
tail / ghost / window debt
falsifiers
replay path
halt reason
```

Its most important function is **halt**:

```text
unknown symbol → halt
missing frame → halt
missing Π/Γ → halt
missing bridge → halt
tail uncontrolled → halt
ghost unchecked → halt
candidate jumps to theorem → halt
```

FCBTrace prevents a runtime from upgrading intuition, images, or attractive numerical patterns into theorem status.

---

## 7. Court Layer: ProofMachine / Court Gate

`ProofMachine` is the court gate. It is not proof itself.

It requires this path:

```text
candidate
  → evidence packet
  → proof obligation
  → lemma candidate
  → formal statement
  → formal checker
  → theorem certificate
```

Court levels:

```text
L0 observation:
  pattern only

L1 engineering evidence:
  reproducible evidence, not proof

L2 symbolic claim:
  definitions and assumptions explicit

L3 proof obligation:
  quantifiers, domain, falsifier, debt map fixed

L4 formal verification:
  Lean / equivalent, no sorry, no hidden axiom

L5 theorem certificate:
  formal proof closed and statement matches claim
```

The core question of ProofMachine is:

```text
Can this thing go to court?
```

Lean or another formal verifier decides:

```text
Has this thing been formally proved?
```

---

## 8. When Blocked: ForgeLoop

If `FCBTrace` halts, `ProofMachine` remands, or `χ≈1` but no bridge exists, the runtime enters `ForgeLoop`.

ForgeLoop may create:

```text
new tool
new method
new lens
new metric
new decomposition
new falsifier
new visualization
new Lean skeleton
new frame bridge
```

Hard rule:

```text
new tool ≠ proof
new method ≠ theorem
insight ≠ closure
```

ForgeLoop can only produce a new candidate, then return it to:

```text
FCBTrace → GRC → ProofMachine → Lean
```

The runtime can generate methods, but it cannot bypass court.

---

## 9. RH A/C Frame as a Proof-Route Instance

In the RH off-ridge route:

```text
s = 1/2 + α + it
q = α²
```

We write:

```text
Ξ(α,t) = A(q,t) + iα C(q,t)
```

An off-ridge zero is equivalent to:

```text
0 < q < 1/4
A(q,t) = 0
C(q,t) = 0
```

So the RH-true off-ridge obstruction version is:

```text
∀ q∈(0,1/4), ∀t,
not (A(q,t)=0 ∧ C(q,t)=0)
```

Compressed into the C-ridge:

```text
C(q,t_C(q)) = 0
H(q) = A(q,t_C(q))

RH true core:
  H(q) never crosses 0
```

This is one concrete task packet for the proof machine. It is not an RH proof claim. It compresses the RH off-ridge problem into proof obligations around `A/C ridge non-crossing`.

---

## 10. Runtime v0.1

```text
ProofMachine Runtime v0.1

Input:
  question / theorem candidate / observation / numerical pattern

1. SWT:
  fix Self, World, Task

2. Master Tree:
  F−2→F−1→S→G→KF→Φ→O→Ψ→AEFP→Ω→a

3. Lens / Locator:
  use OpticalAtlas, α, A/C frame, Landau-like, Hardy-like, etc.

4. Debt:
  classify Dα, Dtail, Dbridge, Dghost, Dwindow, Doverlocalization

5. GRC:
  compute χ = G/(R·C+ε)
  route candidate

6. FCBTrace:
  record frame, closure, basin, debt, unknowns, replay, halt reason

7. ProofMachine:
  decide reject / remand / admit / build lemma / export to Lean

8. Lean:
  certify only if formal theorem closes

9. ForgeLoop:
  if blocked, create new method/tool/lens/falsifier, then return to step 3
```

Shortest summary:

```text
This proof machine runtime is not a machine that directly proves RH.
It is a proof-obligation pipeline that converts intuition, locators, numerics,
lenses, debt, and χ into traceable, haltable, auditable, formalizable objects.
```

Current strength:

```text
It prevents a candidate from quietly becoming a theorem.
It also prevents a blocked state from dying by using ForgeLoop to create
new methods, then sending them back to court.
```
