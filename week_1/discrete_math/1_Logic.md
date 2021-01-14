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
      - [The converse, contrapositive, and inverse](#the-converse-contrapositive-and-inverse)
      - [The biconditional operation](#the-biconditional-operation)
      - [Compound propositions with conditional and biconditional operations](#compound-propositions-with-conditional-and-biconditional-operations)
  - [1.4 Logical equivalence](#14-logical-equivalence)
      - [Showing logical equivalence using truth tables](#showing-logical-equivalence-using-truth-tables)
      - [De Morgan's laws](#de-morgans-laws)
  - [1.5 Laws of propositional logic](#15-laws-of-propositional-logic)
  - [1.6 Predicates and quantifiers](#16-predicates-and-quantifiers)
  - [1.7 Quantified statements](#17-quantified-statements)
  - [1.8 De Morgan's law for quantified statements](#18-de-morgans-law-for-quantified-statements)
  - [1.9 Nested quantifiers](#19-nested-quantifiers)
  - [1.10 More nested quantified statements](#110-more-nested-quantified-statements)


##  1.1 Propositions and logical operations
| Keyword   | Definition |
| ------------- |:-------------| 
| **Logic** | Logic is the study of formal reasoning. |
| **proposition** |A proposition is a statement that is either true or false. |
| **truth value** | A proposition's truth value is a value indicating whether the proposition is actually true or false. |
| **compound proposition** | A compound proposition is created by connecting individual propositions with logical operations. |
| **logical operation** | A logical operation combines propositions using a particular composition rule. |
| **conjunction** | The proposition p ∧ q is read "p and q" and is called the conjunction of p and q. |
| **truth table** | A truth table shows the truth value of a compound proposition for every possible combination of truth | values for the variables contained in the compound proposition. |
| **T** | T represents true. |
| **F** | F represents false. |
| **disjunction** | The proposition p ∨ q is read "p or q", and is called the disjunction of p and q. |
| **exclusive or**  | The exclusive or of p and q evaluates to true when p is true and q is false or when q is true and p is false. |
| **inclusive or**  | The inclusive or operation is the same as the disjunction (∨) operation and evaluates to true when one or both of the propositions are true. |
| **negation** | The negation operation acts on just one proposition and has the effect of reversing the truth value of the proposition. The negation of proposition p is denoted ¬p and is read as "not p". |

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

| Keyword   | Definition |
| ------------- |:-------------| 
| **conditional operation** | The conditional operation is denoted with the symbol →. The proposition p → q is read "if p then q".. |
| **conditional proposition** | A compound proposition that uses a conditional operation is called a conditional proposition. |
| **conditional statement** | A conditional proposition expressed in English is sometimes referred to as a conditional statement. |
| **hypothesis** | In p → q, the proposition p is called the hypothesis, and the proposition q is called the conclusion. |
| **conclusion** | In p → q, the proposition p is called the hypothesis, and the proposition q is called the conclusion. |
| **converse** | The converse of p → q is q → p.. |
| **contrapositive** | The contrapositive of p → q is ¬q → ¬p.. |
| **inverse** | The inverse of p → q is ¬p → ¬q.. |
| **biconditional operation** | If p and q are propositions, the proposition "p if and only if q" is expressed with the biconditional operation and is denoted p ↔ q. . |
| **iff** | The term iff is an abbreviation of the expression "if and only if", as in "p iff q".. |

- The **conditional operation** is denoted with the symbol →. 
- The proposition p → q is read "if p then q". 
- The proposition p → q is false if p is true and q is false; otherwise, p → q is true.


Truth table for the conditional operation:

| p | q |	p → q |
| --------|:-----| :-----:| 
| T | T |	T |
| T | F |	F |
| F | T |	T |
| F | F |	T |

Located below is an illustrated conditional statement

![Counting in base 5](/images/1.3.png)


#### The converse, contrapositive, and inverse

Three conditional statements related to proposition p → q are so common that they have special names. 
- The **converse** of p → q is q → p. 
- The **contrapositive** of p → q is ¬q → ¬p.The **inverse** of p → q is ¬p → ¬q.


| Proposition:| 	  p → q	    | Ex: If it is raining today, the game will be cancelled. | 
| --------|:-----| :-----:| 
| **Converse**:| 	  q → p	    | If the game is cancelled, it is raining today. | 
| **Contrapositive**:| 	  ¬q → ¬p	    | If the game is not cancelled, then it is not raining today. | 
| **Inverse**:| 	  ¬p → ¬q	    | If it is not raining today, the game will not be cancelled | 

#### The biconditional operation

**Biconditional operation:** the proposition "p if and only if q" is expressed with the biconditional operation and is denoted p ↔ q. 

The proposition p ↔ q is true when p and q have the same truth value and is false when p and q have different truth values.

The term **iff** is an abbreviation of the expression "if and only if", as in "p iff q". 

#### Compound propositions with conditional and biconditional operations

- The proposition p → q ∧ r should be evaluated as p → (q ∧ r). This is because parentheses are not used to indicate order.
- **Note:** It is good practice to use parentheses to make sure order of operations is correct




| p	| q	| p ↔ q |
| --------|:-----| :-----:| 
| T	| T	| T |
| T	| F	| F |
| F	| T	| F |
| F	| F	| T |

##   1.4 Logical equivalence

| Keyword   | Definition |
| ------------- |:-------------| 
| **tautology** | A compound proposition is a tautology if the proposition **is always true**, regardless of the truth value of the individual propositions that occur in it. |
| **contradiction** | A compound proposition is a contradiction if the proposition is **always false**, regardless of the truth value of the individual propositions that occur in it. |
| **logically equivalent** | Two compound propositions are said to be logically equivalent if they have the same truth value regardless of the truth values of their individual propositions. |
| **De Morgan's laws** | De Morgan's laws are logical equivalences that show how to correctly distribute a negation operation inside a parenthesized expression. |

- **p ∨ ¬p** is a simple example of a tautology since the proposition is always true whether p is true or false.


|p	| ¬p| 	p ∨ ¬p |
| --------|:-----| :-----:| 
|T	| F| 	T |
|F	| T| 	T |

-  **p ∧ ¬p** is an example of a simple contradiction cus the proposition is false regardless if p is true or false

| p	| ¬p	| p ∧ ¬p |
| --------|:-----| :-----:| 
| T	| F	| F |
| F	| T| 	F |

| Question | Answer | Why |
| --------|:-----| :-----| 
p ↔ ¬p | contradiction | The proposition is always false whether p is true or false. Regardless of p's truth value, p can not have the same truth value as ¬p. |
p → ¬p | neither contradiction or tautology | There is a truth value for p that makes the proposition true, and a truth value for p that makes the proposition false.
(p ∧ q) → p | tautology | he proposition is true regardless of the truth values for p and q.

#### Showing logical equivalence using truth tables

Two compound propositions are said to be **logically equivalent** if they have the same truth value regardless of the truth values of their individual propositions

- If s and r are two compound propositions, the notation **s ≡ r** is used to indicate that r and s are logically equivalent.

```s ≡ r is used if s and r are two compound propositions.```

![Counting in base 5](/images/1.4.png)

 Truth table to show:   **¬p ∨ ¬q ≡ ¬(p ∧ q)**.


| p	 | q	 | ¬p	 | ¬q	 | p ∧ q	 | ¬(p ∧ q)	 | ¬p ∨ ¬q |
| --------|:-----| :-----:|  :-----:|  :-----:|  :-----:|  :-----:| 
| T |	T |	F |	F |	T | **F** |	**F** |
| T |	F |	F |	T |	F | **T** |	**T** |
| F |	T |	T |	F |	F | **T** |	**T** |
| F |	F |	T |	T |	F | **T** |	**T** |

#### De Morgan's laws

**De Morgan's laws** are logical equivalences that show how to correctly distribute a negation operation inside a parenthesized expression.

 The first De Morgan's law is:

    ¬(p ∨ q)   ≡   (¬p ∧ ¬q)

The second version of De Morgan's law swaps the role of the disjunction and conjunction:

    ¬(p ∧ q)   ≡   (¬p ∨ ¬q)

##   1.5 Laws of propositional logic

If two propositions are logically equivalent, then one can be substituted for the other within a more complex proposition

  For example p → q ≡ ¬p ∨ q. Therefore,

<span style="color:blue">(p ∨ r)</span> ∧ <span style="color:red">(¬p ∨ q)</span>  ≡  <span style="color:blue">(p ∨ r)</span> ∧ <span style="color:red">(p → q)</span>

In the next example, the logical equivalence p → q ≡ ¬p ∨ q is applied where the variables p and q represent compound propositions:
<span style="color:blue">(¬t ∧ r)</span> → <span style="color:red">(¬s ∨ t)</span>  ≡  <span style="color:blue">¬(¬t ∧ r )</span> ∨ <span style="color:red">(¬s ∨ t)</span>

| law | variation | variation |
| --------|:-----| :-----:| 
| **Idempotent laws**: | p ∨ p ≡ p | p ∧ p ≡ p | 
| **Associative laws**: | ( p ∨ q ) ∨ r ≡  p ∨ ( q ∨ r ) | ( p ∧ q ) ∧ r ≡  p ∧ (q ∧ r ) | 
| **Commutative laws**: | p ∨ q ≡ q ∨ p | p ∧ q ≡ q ∧ p | 
| **Distributive laws**: | p ∨ ( q ∧ r ) ≡ ( p ∨ q ) ∧ ( p ∨ r ) | p ∧ ( q ∨ r ) ≡ ( p ∧ q ) ∨ ( p ∧ r ) | 
| **Identity laws**: | p ∨ F ≡ p | p ∧ T ≡ p | 
| **Domination  laws**: | p ∧ F ≡ F | p ∨ T ≡ T | 
| **Double negation law**: | ¬¬p ≡ p |  | 
| **Complement laws**: | p ∧ ¬p ≡ F<br> ¬T ≡ F | p ∨ ¬p ≡ T<br> ¬F ≡ T | 
| **De Morgan's laws**: | ¬( p ∨ q ) ≡ ¬p ∧ ¬q | ¬( p ∧ q ) ≡ ¬p ∨ ¬q | 
| **Absorption laws**: | p ∨ (p ∧ q) ≡ p | p ∧ (p ∨ q)  ≡ p | 
| **Conditional identities**: | p → q ≡ ¬p ∨ q | p ↔ q ≡ ( p → q ) ∧ ( q → p ) | 

![Counting in base 5](/images/1.5.png)

##   1.6 Predicates and quantifiers

##   1.7 Quantified statements

##   1.8 De Morgan's law for quantified statements

##   1.9 Nested quantifiers

##   1.10 More nested quantified statements
