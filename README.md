# NP_3_braids
Custom SageMath handler for NP-form 3-braids.

Contains code for exploration of Seifert matrices of NP-form 3-braids, as well as code to check a conjectured signature formula for NP-form 3-braids.

Pane #1 is preamble material.

Pane #2 is the main NP 3-braids container. Its constructor takes data of the following type:

N_start: The first syllable of N.
N_syl: An ordered list of lengths of syllables of N.
P_start: The first syllable of P.
P_syl: An ordered list of lengths of syllables of P.

Pane #3 contains an example of usage.

Panes #4 and #5 define routines necessary for checking the signature conjecture.

Pane #6 generates random braids and tests the signature conjecture. Any examples which have nullity or which make the conjecture false are immediately reported.

Pane #7 Provides a method to symmetrically row reduce a Seifert Matrix and display the step-by-step output.

