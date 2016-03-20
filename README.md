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

## WEEK # 5
  8. Proof by Contradiction
        - "When you have eliminated all which is impossible, then whatever remains, however imporobable, must be the truth."
        - We proved √2 is irrational; 
            * Rational number: {a/b | a, b ∈ Z, b≠0, *a, b does not have common factor except ±1 (or in lowest terms)} *
          a. Assume ¬ premise ≡ T
          b. Show that a. ends up in a contradiction
            * Theorem : If a^2 is even; then a is also even
        - 3n+2 is odd, then n is odd
          a. Assume ¬ premise ≡ T
            * If 3n is even, then n is even *
  9. Negation of Implication
        - (¬(p → q) → (p ∧ ¬q))
        - The negation statement: "If p is true, then q is true"
        - There is atleast one case.
  10. Contradiction and Implication
        - Proving a theorem that is a biconditional statement (p ↔ q); we show that: (p → q) → [(p → q) ∧ (q → p)]
  11. Proof by Equivalence (Biconditionals)
        - (p ↔ p) = (p → q) → (q → p)
        - "If n is an integer, n is even; if f n^2 is even"
        - Ex. r ↔ s
          a. Assume T ≡ T
          b. Show that ¬≡ T
          c. ∴ Even

## WEEK # 6
  1. Proof by Equivalence (Biconditionals)
          a. "If n is a positive integer, then n is odd if and only if n^2 is odd."
          b. " For any natural number n, n is even if f n^2 is even."
          c. P1 : n is even ; P2 : n-1 is odd ; n^2 is even
  2. Mathematical Induction
        - Sequence of Proposition
          1. Basic Step : P(1) is shown to be true.
          2. Inductive Step : "If P(k+1)is true whenever P(k) is true, then P is true for all positive integer."
                [ P(1) ∧  ∀k(P(k) → P(k+1)) ] → ∀ ∧ P(n)
          3. Using induction :
            a. Basis : P(1) or P(0) to be true
            b. Direct Proof :
                i. Assume P(k) ≡ T
                ii. Show that P(k+1) ≡ T
          4. Ex. Prove P(n) = 1 + 2 + 3 . . . + n = n(n+1)/2
                a. Basis :
                     P(n) ≡ T
                     P(1) ≡ T
                     1 = n(n+1)/2
                     1 = 1
                    ∴ P(1) ≡ T
                b. Assume P(k) ≡ T
                    i. 1 + 2 + 3 + . . . + k = k(k+1)/2
                    ii. 1 + 2 + 3 + . . . + k+1 = (k+1)(k+1+1)/2
                        k(k+1)/2 + (k+1) = (k+1)(k+2)/2
                      ∴ QED
                      
          5. 
          
  ## WEEK # 7
  1. Partial Correctness :
      P : Initial Assertion = T
          S : If ___________
              Else ___________
          Q : Final Assertion = T
  2. Hoare Triple :
      p { S } q ≡ T
  3. Rules of Inference :
      p { S1 } q ≡ T
      q { S1 } r ≡ T
      ∴ p { S1; S2 } r --> Composition Rule
  4. Conditional Statement :
      ( P ∧ condition ) { S } q --> Case I
      ( P ∧ ¬condition ) → q --> Case II
      ∴ p { if condiition then S } q
  5. If Else Statement :
      ( P ∧ condition ) { S1 } q ---> Case I
      ( P ∧ ¬condition ) { S2 } q ---> Case II
      ∴ p { if condiition then S1 else S2 } q

 ## WEEK # 8
 This week is all about functions and algorithms.
 Function :
  - f(a) = b ; where f(a) is called the domain while b is the codomain
  - There must only be one domain.
  - Ex. 
    a. f(x) = x^2 ; Domain x ∈ ℤ f: ℤ to ℤ 
    b. int floor (float x)
  - Types of Functions :
    a. One-to-One (Injective) = ∀x∀y(f(x)=f(y) → x=y) and ∀x∀y(x≠y → f(x)≠f(y))
    b. Onto (Surjective) Range = Co-domain 
    c. One-to-one and Onto (Bijection) 
  Algorithm :
  - Properties of Algorithm :
    a. Input
    b. Output
    c. Definiteness
    d. Correctness
    e. Finiteness
    f. Effectiveness
    g. Generality

  ## WEEK # 9
  Algorithm
  - Searching Algorithm :
    a. Linear Search Algorithm :
      PRECONDITION 
      Procedure linear search(x: integer, a1, a2, . . . , an: increasing integer)
      i:=1
      while (i ≤ n and x = ai )
      i := i + 1
      if i ≤ n then location := i
      else location := 0
      return location{location is the subscript of the term that equals x, or is 0 if x is not found}
      POSTCONDITION 
    b. Binary Search Algorithm :
      PRECONDITION 
      procedure binary search (x: integer, a1, a2, . . . , an: increasing integers)
      i := 1{i is left endpoint of search interval}
      j := n {j is right endpoint of search interval}
      while i < j
      m := (i + j)/2
      if x > am then i := m + 1
      else j := m
      if x = ai then location := i
      else location := 0
      return location{location is the subscript i of the term ai equal to x, or 0 if x is not found}
  - Sorting Algorithm :
    a. Bubble Sort :
      PRECONDITION
      procedure bubblesort(a1, . . . , an : real numbers with n ≥ 2)
      for i := 1 to n − 1
      for j := 1 to n − i
      if aj > aj+1 then interchange aj and aj+1
      {a1, . . . , an is in increasing order}
    b. Insertion Sort :
      PRECONDITION 
      procedure insertion sort(a1, a2, . . . , an: real numbers with n ≥ 2)
      for j := 2 to n
      i := 1
      while aj > ai
      i := i + 1
      m := aj
      for k := 0 to j − i − 1
      aj−k := aj−k−1
      ai := m
      {a1, . . . , an is in increasing order}

 ## WEEK # 9
 - Another type of Algorithm :
    a. Greedy Change-Making Algorithm helps the computer make decisions
      PRECONDITION
      procedure change(c1, c2, . . . , cr : values of denominations of coins, where c1 > c2 > · · · > cr ; n: a positive          integer)
      for i := 1 to r
      di := 0 {di counts the coins of denomination ci used}
      while n ≥ ci
      di := di + 1 {add a coin of denomination ci}
      n := n − ci
      {di is the number of coins of denomination ci in the change for i = 1, 2, . . . , r}
    b. Growth of Functions commonly used in Big-O Estimates
    c. Big-O Notation
      Let f and g be functions from R-R; f(x) is O(g(x))
      We can take C and k as witnesses such that: |f(x)| ≤ C|g(x)| whenever x > k
        i. Show that 7x2 is O(x3).
           Solution: When x > 7, we have 7x2 < x3.
                     C = 1 and k = 7 as witnesses
    d. Big-O Estimates
      Let f (x) = anx^n + an−1x^n−1 +· · ·+a1x + a0, where a0, a1, . . . , an−1, an are real numbers.
      Then f (x) is O(x^n).
      1 + 2 + 3+· · ·+n is O(n2)
      n! is O(n^n)
      log n is O(n).
    e. Big Omega Notation
      Big O cannot express the lower bound, we use big Omega notation.
      Let f and g be functions from R to R; f(x) is O(g(x))
      C and k as witnesses such that: |f(x)| ≥ C|g(x)| whenever x < k.
      f(n) is (n2)
    f. Big Theta Notation
      For Lower and Upper bound
    g. Time Complexity or Complexity of Algorithms

      | Complexity  |  Terminology |
      | :-----: |:-------:|
      | O(n) |  Constant Complexity |
      | O(log n) | Logarithm Complexity |
      | O(n) | Linear Complexity |
      | O(n log n) | Linearithmic Complexity |
      | O(n^b) | Polynomial Complexity |
      | O(b^n), where b>1 | Exponential Complexity |
      | (n!) | Factorial Complexity |
      
    h. Division and Modulo Operator
      Let a be an integer and d positive integer. 
      Then there is a unique Q and r with 0 ≤ r < d such that a = dQ + r
      Q = a div d
      r = a mod d
        i. Example:
            a = 9, b = 2
            Q = 9 div 2 = 4
            r = 2 mod 2 = 1
            4(2) + 1 = 9
            
            a = - 12, b = 3
            Q = -11 div 3 = -4
            r = -11 mod 3 = 1
            -4(3) + 1 = -11
            
            → ∧ ¬ ∴ ↔

  ## WEEK # 10
