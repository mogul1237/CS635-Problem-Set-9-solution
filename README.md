# CS635-Problem-Set-9-solution

Download Here: [CS635 – Problem Set #9 solution](https://jarviscodinghub.com/assignment/cs635-problem-set-9-solution/)

For Custom/Original Work email jarviscodinghub@gmail.com/whatsapp +1(541)423-7793

1. When considering a second order cone constraint, a temptation might be to square it in order
to obhain a classical convex quadratic constraint. This might not always work. Consider the
constraint
2×1 + x2 ≥ kxk2
,
and its squared conterpart:
(2×1 + x2)
2 ≥ kxk
2
2
.
Is the set defined by the first inequality convex? Is the set defined by the second inequality
convex? Draw them both and discuss.
2. We would like to minimize the function f : R
3
7→ R, with values:
f(x) = max 
x1 + x2 − min(min(x1 + 2, x2 + 2×1 − 5), x3 − 6),
(x1 − x3)
2 + 2x
2
2
1 − x1

,
with the constraint kxk∞ < 1. Explain precisely how to formulate the problem as an SOCP in standard form. Solve using GAMS. 3. The returns on n = 4 assets are described by a Gaussian (normal) random vector r ∈ R 4 , having the following expected value rˆ and covariance matrix Σ: rˆ =      0.12 0.10 0.07 0.03      , Σ =      0.0064 0.0008 −0.0011 0 0.0008 0.0025 0 0 −0.0011 0 0.0004 0 0 0 0 0      . The last (fourth) asset corresponds to a risk-free investment. An investor wants to design a portfolio mix with weights x ∈ R 4 (each weight xi is non-negative , and the sum of the weights is one) so as to obtain the best expected return rˆ T x, while guaranteeing that (a) no single asset weights more that 40%; (b) the risk-free assests should not weight more that 20%; (c) no asset should weight less than 5%; (d) the probability of experiencing a return lower than q = −3% should be no larger that  = 10−4 . What is the maximal achievable expected return, under the above constraints? 
