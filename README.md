# Honda

This project contains SageMath code to compute p-curvatures of first-order differential equations with rational coefficients, and decide algebraicity of solutions doing so, based on the work of F.Fürnsinn and L.Pannier.

In 'Effective Honda.ipynb' you will find a unique block of code containing all functions, commented, related to this work.
The main functions are:
  - pcurvature(a,b,p) that computes (the 1/p-th power of) the p-curvature of the differential equation y' = (a/b)y;
  - Honda(a,b) decides algebraicity of solutions of y' = (a/b)y using p-curvatures computations
  - CompFactor(a,b) that decides algebraicity of solutions of y' = (a/b)y using polynomial factorization;
  - sigma(a,b) computes the upper bound S on the primes for which we need to check that (almost) all p-curvatures vanish, the function Honda does not call this function.

In 'Examples.ipynb' you will find different examples with a bit of comment showcasing how our main algorithm performs on various inputs, and how it compares to a polynomial factorization approach.

If you find any error please report them to lucas.pannier@uvsq.fr
