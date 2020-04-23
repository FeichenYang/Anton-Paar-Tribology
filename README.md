# Anton-Paar-Tribology
So basically, I was trying to measure the coefficient of friction (COF) of a material. 
Typically to do that, we need a "3-pin-on-disk" setup (no need to know what it is), which cost $13,000.
As someone who's poor and cheap, I only had the budget to buy a $2000 "1-pin-on-disk" setup. 
The $2000 setup works, but there's a problem: it outputs the "torque", instead of the "COF".
The COF can be calculated by this equation:
Torque = ∫2πr^2fdr (from 0 to R), where f is the COF. 
(If y'all interested please read this paper: https://pubs.acs.org/doi/abs/10.1021/jp990256v)
Our task is to solve this equation with linear algebra in Numpy.

