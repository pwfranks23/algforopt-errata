# algforopt-errata
Errata for Algorithms for Optimization book

* Figure 3.6, page 38: F_2 should be F_3 and F_3 should be F_4 (thanks to Zdeněk Hurák)
* p. 78: Change eq 5.26 to use s of k+1 rather than s of k. RMSProp uses the most recent value. (thanks to Michael Gobble)
* Fig 5.7: change "hypermomentum" in legend to "hypergradient" and change caption to begin: "Hypergradient versions of gradient descent and Nesterov momentum compared on..."
* p. 110: Change "elseif yr > ys" to use \geq
* p. 160: The ref to eq. 9.8 in the last paragraph should actually be to eq. 9.7. (thanks to Anthony Corso and Joan Creus-Costa)
* p. 171: There should be minus signs instead of plus signs before each of the x_i terms under the square root (thanks to Zhengyu Chen)
* p. 174: Eq 10.20 should have a + instead of a - as the gradients must point in opposite directions and mu is non-negative (thanks to Erez Krimsky)
* p. 176: Stationarity condition should use a + instead of a -
* p. 177: Stationarity condition (eq 10.31) should use + instead of - (thanks to Erez Krimsky)
* p. 180: Ex 10.6 incorrectly optimizes the dual function. It should recognize that the dual function is unbounded below when lambda is less than 1/2. The dual problem is maximized at 1/2, yielding two optimal solutions.
* p. 195: In ex. 11.4, the minimization should be over x and s in the second problem and over x+, x-, and s in the third problem (thanks to Holly Dinkel)
* p. 200: The leaving index should be in B.
* p. 203: Ex 11.7 should read "causes x_4 to become zero" (thanks to Wouter Van Gijseghem)
* p. 277: Ex 15.1 has 1^-1, which should be 2^-1 (thanks to Ryan Samuels)
* p. 284: In the matrix in Ex 15.3, the subscript of row 5, column 6 should be 21, not 12 (thanks to Veronika Korneyeva)
* p. 324: Ex 18.1 analytic solution for variance was incorrect. (plot appears to be correct) (thanks to Veronika Korneyeva)
* p. 449: Eq D.2 should read: 4 * (-27) = -108
* p. 454: Changed two instances of sigma to mu on the left-hand-side of Excercise 8.4.
* p. 459: Ex. 11.3: solution should be "We can add a slack variable $x_3$ and split $x_1$ and $x_2$ into $x_1^+$, $x_1^-$, $x_2^+$, and $x_2^-$. We minimize $6x_1^+ - 6x_1^- + 5x_2^+ - 5x_2^-$ subject to the constraints $-3x_1 + 2x_2 + x_3 = -5$ and $x_1^+, x_1^-, x_2^+, x_2^-, x_3 \geq 0$." (thanks to Jimin Park)

## Minor
* p. 46: Change Eq 3.14 to use y_min on both sides for consistency
* Example 4.2: "satisfied" is twice misspelled as "satisifed."
* Sec 4.5: "termination" is misspelled as "terminiation"
* Mu vector prior to Eq 8.18 should be bold. 
* p. 201: Changed "positive" to "non-negative" is 2nd-to-last paragraph
* p. 287: First paragraph, missing period after fourth sentence. Should be "obeserved points were drawn from the model. Equivalenty,.." (comment added by Patrick Franks)
