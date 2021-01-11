#  Logic
Table of Contents
- [Logic](#logic)
  - [1.1 Propositions and logical operations](#11-propositions-and-logical-operations)
    - [The conjunction operation](#the-conjunction-operation)
      - [Truth Table](#truth-table)
      - [The disjunction operation](#the-disjunction-operation)
        - [Exclusive or operation](#exclusive-or-operation)
        - [Inclusive or](#inclusive-or)
        - [Negation](#negation)
    - [Compound Proposition Examples](#compound-proposition-examples)
  - [1.2 Evaluating compound propositions](#12-evaluating-compound-propositions)
      - [Evaluating complex compound propositions.](#evaluating-complex-compound-propositions)
  - [1.3 Conditional statements](#13-conditional-statements)
  - [1.4 Logical equivalence](#14-logical-equivalence)
  - [1.5 Laws of propositional logic](#15-laws-of-propositional-logic)
  - [1.6 Predicates and quantifiers](#16-predicates-and-quantifiers)
  - [1.7 Quantified statements](#17-quantified-statements)
  - [1.8 De Morgan's law for quantified statements](#18-de-morgans-law-for-quantified-statements)
  - [1.9 Nested quantifiers](#19-nested-quantifiers)
  - [1.10 More nested quantified statements](#110-more-nested-quantified-statements)
  - [1.11 Logical reasoning](#111-logical-reasoning)
  - [1.12 Rules of inference with propositions](#112-rules-of-inference-with-propositions)
  - [1.13 Rules of inference with quantifiers](#113-rules-of-inference-with-quantifiers)


##  1.1 Propositions and logical operations

- **Logic** is the study of formal reasoning.
- The most basic element in logic is a proposition. A **proposition** is a statement that is either true or false.
- A proposition's **truth value** is a value indicating whether the proposition is actually true or false.


| Proposition   | Truth Value |
| ------------- |:-------------:| 
| There are an infinite number of prime numbers.     | True |
| The Declaration of Independence was signed on July 4, 1812     | False      |

The following are not propositions because Propositions are typically declarative sentences:

    English sentences that are not propositions is located below
| Sentence   | Truth Comment |
| ------------- |:-------------:| 
| What time is it?	     | A question, not a proposition. A question is neither true nor false.|
| Have a nice day.	     | A command, not a proposition. A command is neither true nor false. |

### The conjunction operation
- The conjunction operation is denoted by ∧ which means AND"
  - The proposition p ∧ q is read "p and q" and is called the conjunction of p and q.
    - p ∧ q is true if both p is true and q is true. 
    - p ∧ q is false if p is false, q is false, or both are false.
- A **compound proposition** is created by connecting individual propositions with logical operations.
- A **logical operation** combines propositions using a particular composition rule.

#### Truth Table

- A truth table shows the truth value of a compound proposition for every possible combination of truth values for the variables contained in the compound proposition.
Truth Table for p ∧ q:

| p     q | p ∧ q |
| --------|:-----:| 
| T     T |    T  |
| T     F |    F  |
| F     T |    F  |
| F     F |    F  |

* p ∧ q is true only when both p and q are true.
* p ∧ q is false for all other combinations.

Examples of different ways to express a conjunction in English.

| p     q | p ∧ q |
| --------|:----| 
| p and h	| Sam is poor and he is happy. |
| p, but h	| Sam is poor, but he is happy. |
| Despite the fact that p, h	| Despite the fact that Sam is poor, he is happy. |
| Although p, h	| Although Sam is poor, he is happy. |

#### The disjunction operation

The disjunction operation is denoted by ∨. The proposition p ∨ q is read "p **or** q", and is called the **disjunction** of p and q.

- p v q is **true** when either of p or q is true 
- p v q is **false** only when p and q are both false

| p     q | p v q |
| --------|:-----:| 
| T     T |    T  | 
| T     F |    T  |
| F     T |    T  |
| F     F |    F  |

##### Exclusive or operation
- The exclusive or of p and q evaluates to true when p is true and q is false or when q is true and p is false.
- The exclusive or operation is usually denoted with the symbol ⊕. The proposition p ⊕ q is true if exactly one of the propositions p and q is true but not both. This question asks you to fill in the truth table for p ⊕ q.

| p |	q |	p ⊕ q |
| -----|:---:| :---:|
| T |	T |	1? |
| T |	F |	2? |
| F |	T |	3? |
| F |	F |	4? |

1. **1?** p ⊕ q does not evaluate to true if p is true and q is true.
2. **2?** p ⊕ q is true if exactly one of p and q are true. In the second row of the table, p is true and q is not true.
3. **3?** p ⊕ q is true if exactly one of p and q are true. In the third row of the table, q is true and p is not true.
4. **4?** p ⊕ q does not evaluate to true if p is false and q is false.


##### Inclusive or
- The inclusive or operation is the same as the disjunction (∨) operation and evaluates to true when one or both of the propositions are true.


##### Negation
The **negation** operation acts on just one proposition and has the effect of reversing the truth value of the proposition
- The negation of proposition p is denoted ¬p and is read as "**not p**"
- Its truth table only has two rows for the proposition's two possible truth values because the negation operation only acts on a single proposition.


|    p    |   ¬p  |
| --------|:-----:| 
|    T    |   F   |
|    F    |   T   |



Examples:

    p is true
    q is true
    r is false

| Question | Answer |
| --------|:-----| 
| p ∧ q  | Since p is true and q is true, the conjunction is also **true**. |
| ¬r | The negation of a false proposition is **true**. |
| p ∧ r | Since r is false, the proposition is **false**. |
| p ∨ r | Since p is true, the proposition is **true**.|
| p ∨ q | Since at least one of p, q is true, the proposition is **true**. |

- v = or
- ∧ = and
- ¬r = not


### Compound Proposition Examples

  t: The patient took the medication.
  n: The patient had nausea.
  m: The patient had migraines.

| Question | Answer |
| --------|:-----| 
| The patient had nausea and migraines. | n ∧ m  |
| The patient took the medication, but still had migraines. | t ∧ m |
| The patient had nausea or migraines. | n v m |
| The patient did not have migraines. | ¬m |
| Despite the fact that the patient took the medication, the patient had nausea. | t ∧ n |
| There is no way that the patient took the medication. | ¬t |


##   1.2 Evaluating compound propositions

A compound proposition can be created by using more than one operation. For example, the proposition p ∨ ¬q evaluates to true if p is true or the negation of q is true.

**Note:**  In the absence of parentheses, the rule is that negation is applied first, then conjunction, then disjunction:

    1. ¬ (not)
    2. ∧ (and)
    3. ∨ (or)

So basically this is the way orders are applied in a compound proposition - the Hierarchy.

- The proposition p ∨ q ∧ r should be read as p ∨ (q ∧ r), instead of (p ∨ q) ∧ r
- The proposition ¬p ∨ q is evaluated as (¬p) ∨ q instead of ¬(p ∨ q)... This is because of readability

#### Evaluating complex compound propositions.

    p is true
    q is true
    r is false

| Question | Answer |
| --------|:-----| 
| p ∨ ¬q | true |
| ¬r ∧ (p ∨ ¬q) | true |
| ¬(p ∧ ¬r) | true |
| (p ∨ r) ∧ ¬p | true |

Answer:
1. Since p is true, the disjunction of p and any other proposition is **true**.
2. ¬r is true and (p ∨ ¬q) is **true**.
3. p is true and ¬r is true, so their conjunction is true. When the negation is applied, the final truth value is **false**.
4. Since ¬p is false, the conjunction is false.

Truth table with three variables.
**Note:** Three variables have  **2<sup>3</sup>** unique combinations and so require 8 rows.
    

| p	| q	| r	| ( p ∨ r ) ∧ ¬q| 
| --------|:-----| :-----| :-----:| 
| T |	T |	T |	F |
| T |	T |	F |	F |
| T |	F |	T |	T |
| T |	F |	F |	T |
| F |	T |	T |	F |
| F |	T |	F |	F |
| F |	F |	T |	T |
| F |	F |	F |	F |


Exercise: Writing truth tables:

¬p ⊕ q

|p	| q	| ¬p ⊕ q| 
| --------|:-----| :-----:| 
| T	| T | T |
| T	| F | F |
| F	| T | F |
| F	| F | T |


##   1.3 Conditional statements

- The **conditional operation** is denoted with the symbol →. 
- The proposition p → q is read "if p then q". 
- The proposition p → q is false if p is true and q is false; otherwise, p → q is true.


##   1.4 Logical equivalence

##   1.5 Laws of propositional logic

##   1.6 Predicates and quantifiers

##   1.7 Quantified statements

##   1.8 De Morgan's law for quantified statements

##   1.9 Nested quantifiers

##   1.10 More nested quantified statements

##   1.11 Logical reasoning

##   1.12 Rules of inference with propositions

##   1.13 Rules of inference with quantifiers




