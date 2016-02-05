# dismathportfolio-ahvabada
dismathportfolio-ahvabada created by Classroom for GitHub

## WEEK # 1

- This week, we were introuduced to logic and proofs.
- Proof
  - Mathematical proof of a proposition is a chain of logical deductions leading
      to the proposition from a base set of axioms.
- We were also taught how to use the Truth Table on proving a statement whether it is true or false.

| Logical Symbol  |  Logical Operator | Shorthand | Formula | Logical Expression |
| :-----: |:-------:|:-----:| :-------: | :-------: |
| ¬ |Negation | not | val(¬p) = 1 - val(p) | ¬p |
| ∧ | Conjunction | and | val(p ∧ q) = min(val(p), val(q)) | p ∧ q |
| v | Disjunction | or | val(p v q) = max(val(p), val(q)) | p v q |
| ⊕ | Exclusive disjunction | xor | if val(p)  not equal val(q) = 1 , otherwise  0|  p ⊕ q  ≡ (¬p ∧ q) v (p ∧ ¬q) |
| → | Conditional | if, then | if val(p)  ≤ val(q) = 1 , otherwise  0  | p → q ≡  ¬p v q |
| ↔ | Biconditional | iff | if val(p) equals val(q) = 1 , otherwise  0 |  p ↔ q ≡ (p → q) ∧ (q → p) |

- There were also applications for all.
- Although I've understood how the logic works, it still confuses me a little.

## WEEK # 2

-  Logical Equivalences
- We need to know each of these so that when we answer the quiz, we can identify and know the sequence of the steps.

| Name  |  Logical Equivalences |
| :-----: |:-------:|
| Identity Laws |  p v F = p |
                | p ∧ T = p |
| Domination Laws | p v T = T |
                  | p ∧ F = F |
| Negation Laws | p v ¬p = T |
                | p ∧ ¬p = F |
| Double Negation | ¬(¬p) = p |
| Idempolent Laws | p v p = p |
                  | p ∧ p = p |
| Commutative Laws | p v q = q v p |
                   | p ∧ q = q ∧ p |
| Associative Laws | (p v q) v r = p v (q v r) |
                   | (p ∧ q) ∧ r = p ∧ (q ∧ r) |
| Distributive Laws | p v (q r) = (p v q)  (p v r) |
                    | p ∧ (q v r ) = (p ∧ q) v (p ∧ r)
| DeMorgan's Laws | ¬(p ∧ q) = ¬p v ¬q |
                  | ¬(p v q) = ¬p ∧ ¬q |
| Absorption Laws | p v (p ∧ q) = p |
                  | p ∧ (p v q) = p |

- We were also given a homework about Superman's existence, by the use of rules of inference, it proved that 'Superman does not exist' which means the statement is valid. A lot of variables were used to end up with final answer.

## WEEK # 3
- New topics were discussed this week
- Tools
  - Truth Table
  - Logical Equivalences
  - Quantifiers
    There are two types of it :
    1. Existential Quantifier (∃x)
         " There exist "
    2. Universal Quantifier (∀x)
         " For All "
  - Predicate Property
  - Logical Expressions
  - Tautology 
      " statement that is always true "
  - Rules of Inference
    - Another set of things we should start familiarizing ourselve, 'the rules of inference'

| Rules of Inference | | |
| :-----: |:-------:|:-----:|
| p | (p ∧ (p → q)) → q | Modus Ponens |
| p → q |
| ∴ q |
| ¬q | (¬q ∧ (p → q)) →  p | Modus Tollens |
| p → q |
| ∴ ¬p |
| p → q | ((p → q) ∧ (q → r)) → (p → r) | Hypothetical Syllogism |
| q → r |
| ∴ p → r |
| p v q | ((p v q) ∧  p) → q | Disjunctive Syllogism |
| ¬p |
| ∴ q |
| p | p → (p v q) | Addition |
| ∴ p v q |
| p ∧ q | (p ∧ q) → p | Simplification |
| ∴ p |
| p | ((p) ∧ (q)) → (p ∧ q) | Conjunction |
| q |
| ∴ p ∧ q |
| p v q | ((p v q) ∧ (¬p v r)) → (q v r) | Resolution |
| ¬p v r |
| ∴ q v r |

- We were given examples of statements to prove that made me understand the lesson.

## WEEK # 4
- This week, we focused on methods o proof such as Direct, Contraposition, Vacuous, Trivial, Proof by Contradiction, Negation of Implication and Proof of Equivalence (Biconditionals).
  1. Direct Proof 
        - Assume that p is true to show that q must also be true.
  2. Contraposition Proof
        - Assume that the negation of q must be true.
  3. Vacuous Proof 
        - Show that p is false because → q  must be true when p is false.
  4. Trivial Proof 
        - Show that q is true, it follows that p → q must also be true. q → (p → q) 
  5. Proof of Contradiction 
        - Assume that the negation of p must be true.
  6. Negation of Implication 
        - "If p is true, then q is true" is the statement "There is at least one case where p is true and q is false."
  7. Proof of Equivalence (Biconditionals) 
        - (p ↔ q) = (p → q) → (q → p)
- Even if we were given examples for each, I am still figuring out on how and when to use the methods on certain problems.
- A lot of assuming happened this week and it is really hard to give proof on things.

