
###
 <span class="btb">Understanding Predicates and Statements</span>: 
  - **Predicate Concept**: A sentence containing variables is called a <span class="ortb">predicate</span>. For example, "P(n) means 'n is prime'" is a predicate. It becomes a statement only when we specify a value for the variable.

- <span class="btb">Implication with Free Variables</span>: 
  - **Example**: Consider the implication <span class="ortb">P(n) → ¬P(n + 7)</span>.
  - **Issue**: This contains a <span class="ortb">free variable</span> 'n', making it not a definitive statement but rather a predicate.

- <span class="btb">From Predicate to Statement</span>:
  - **Creating a Statement**: Substituting a specific value for 'n' in the predicate turns it into a <span class="gtb">statement</span>.
  - **Example Validity**: For any given value of 'n', the implication <span class="ortb">P(n) → ¬P(n + 7)</span> holds true.

- <span class="btb">Quantifying Variables</span>:
  - **Expressing General Truth**: To accurately convey the intended meaning, it's necessary to <span class="ortb">quantify</span> the variable. 
  - **Correct Formulation**: What we're actually stating is <span class="gtb">"For all values of n, if n is prime, then n + 7 is not prime."</span> 

- <span class="btb">Mathematical Expression</span>:
  - **Quantified Statement**: The proper way to express the initial idea is to use a universal quantifier:
  <span class="ortb">∀n (P(n) → ¬P(n + 7))</span>, where '∀' denotes 'for all'.
