# logic-equivalences-inference-reference
rules for logic

symbols:
¬ ^ ∨ ⊕ ⇒ ⇔ ∀	∃ ∴ ≡

|Equivalence | Name|
|------------ | -------------|
|p ^ T ≡ p | Identity Law|
|p ∨ F ≡ p | |
|------------ | -------------|
|p ^ F ≡ F | Domination Law|
|p ∨ T ≡ T | |
|------------ | -------------|
|p ∨ p ≡ p | Idempotent Law|
|p ^ p ≡ p | |
|------------ | -------------|
|¬(¬p) ≡ p | Double Negation Law|
|------------ | -------------|
|p ∨ q ≡ q ∨ p | Commutative Law|
|p ^ q ≡ q ^ p | |
|------------ | -------------|
|(p ∨ q) ∨ r ≡ p ∨ (q ∨ r) | Associative Law|
|(p ^ q) ^ r ≡ p ^ (q ^ r) | |
|------------ | -------------|
|p ∨ (q ^ r) ≡ (p ∨ q) ^ (q ∨ r) | Distributive Law|
|p ^ (q ∨ r) ≡ (p ^ q) ∨ (q ^ r) | |
|------------ | -------------|
|¬(p ^ q) ≡ ¬p ∨ ¬q | De Morgan's Law|
|¬(p ∨ q) ≡ ¬p ^ ¬q | |
|------------ | -------------|
|p ∨ (p ^ q) ≡ p | Absorption Law|
|p ^ (p ∨ q) ≡ p  | |
|------------ | -------------|
|p ∨ p ≡ T | Absorption Law|
|p ^ ¬p ≡ F  | |
|------------ | -------------|

implication related equivalences
|------------ |
|p ⇒ q ≡ ¬p ^ q|
|p ⇒ q ≡ ¬q ⇒ ¬p|
|p ∨ q ≡ ¬p ⇒ q|
|p ^ q ≡ ¬(q ⇒ ¬p)|
|¬(p ⇒ q) ≡ p ^ ¬q|
|(p ⇒ q) ^ (p ⇒ r) ≡ p ⇒ (q ^ r)|
|(p ⇒ r) ^ (q ⇒ r) ≡  | (p ∨ q) ⇒ r|
|(p ⇒ q) ∨ (p ⇒ r) ≡ p ⇒ (q ∨ r)|
|(p ⇒ r) ∨ (q ⇒ r) ≡ (p^q) ⇒ r|
|------------ |

¬ ^ ∨ ⊕ ⇒ ⇔ ∀	∃ ∴ ≡
