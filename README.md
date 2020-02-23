# Quantum Exercises


## Task 2 
> Implement a circuit which returns |00> and |11> with equal probability. Compare the results for different numbers of measurements: 1, 10, 100, 1000. 
> Requirements :
> * Circuit should consist only of CNOTs, RXs and RYs. 
> * Start from all parameters in parametric gates being equal to 0. 
> * You should find the right set of parameters using gradient descent (you might use more advanced optimization methods if you like). 
> * Simulations must be done with sampling - i.e. limited number of measurements per iteration and noise. 

> **Bonus question:**
> How to make sure you produce state |00>+|11> and not |00>-|11> ?
