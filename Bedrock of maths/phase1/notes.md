Logic - study of how we think, not about what we think
As per 1 -> it is the analysis of methods of reasoning.

Propositional calculus:
    1. What is propositional calculus - undefined
    2. What is proposition here and why we take it as the first step of mathematical logic - undefined
    3. Propostional connectives - what are they? - undefined
        Truth tables - getting directly to a concept
            Negation - operation performed to get falsity of a sentence.    
                        The symbol we use to represent the operator is ¬
                        To print it under linux, use Ctrl + Shift + U then type 00ac and enter
                            A   ¬A
                            T    F
                            F    T
                        Which means, it applies to the entire sentence and changes the truthiness of it
            Conjunction - operation performed on two sentences truth values to get conlusive truthiness as outcome and happens only when both the component sentences been true 
                        The symbol we use to represent the operator is ^
                        A  B  A^B
                        F  F   F
                        F  T   F
                        T  F   F
                        T  T   T
                        As per our logic of and operation -> component sentences have to be true for the combinational sentence to be true, will false otherwise
            Disjunction - operation performed on two sentences and the natural language - cannot define it now, not clear
                        natural language gives us to forms, inclusive and exclusive, we take it as inclusive or
                        A  B  A v B
                        F  F    F
                        F  T    T
                        T  F    T
                        T  T    T (inclusive only gives us true here)
            Conditional - can't define by ourself now - unclear 
                        something like if it happens then consequnce must happen formulated as
                        if A, then B and symbolized as A ==> B (implies)
                        A  B  A => B
                        F  F     T
                        F  T     T
                        T  F     F -> as per logic when A is True B cannot be False
                        T  T     T

            Biconditional
                    True only when both have same truth value
                    Represented as A <==> B
                    A  B  A <==> B
                    F  F      T
                    F  T      F
                    T  F      F
                    T  T      T

            The operators or symbols ¬, ^, v, ==>, <==> are propositional connectives

            So the rules now,
            Any sentence built up by application of these connectives has a truth value that depends on the truth values of the constituent sentences. In order to make this dependence apparent, let us apply the name statement form to an expression built up from the statement letters A, B, C, and so on by appropriate applications of the propositional connectives.

                1. All statement letters (capital italic letters) and such letters with
                numerical subscripts† are statement forms.

                2. If B and C are statement forms, then so are (¬B), (B ∧ C), (B ∨ C),
                (B ⇒ C), and (B ⇔ C).

                3.Only those expressions are statement forms that are determined
                to be so by means of conditions 1 and 2.* Some examples of state-
                ment forms are B, (¬C2 ), (D3 ∧ (¬B)), (((¬B1 ) ∨ B2) ⇒ (A1 ∧ C2)), and
                (((¬A) ⇔ A) ⇔ (C ⇒ (B ∨ C))).

                If there are n distinct letters in a statement form, then there are 2n possible
                assignments of truth values to the statement letters and, hence, 2n rows in
                the truth table.


            Statement letters - A propositional statement is being replaced with a letter(from English alphabets usually) as convention that we are more focused on structure not on the sentence meaning or context.

            Propositional statement - A statement which claims something to be either true or false. 
                It must say something that can be true or false. So propositional statements must assert something.
            Propostion word given just to the statement which claims or asserts something to be true or false.
            Atomic statement - A smallest statement that is still has a truth value and cannot be broken down further.


            Exclusive OR:
                True when both truth values are different.
                The operator is represented by simple ⊕
                    A  B  A ⊕ B
                    F  F    F
                    F  T    T
                    T  F    T
                    T  T    F

