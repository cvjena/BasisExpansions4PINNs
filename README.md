# Basis Expansions for PINNs

Code accompanying the manuscript titled "Leveraging Basis Expansions For Improving Physics-Informed Neural Networks" submitted to ICCS 2024. 


## Abstract
Computational physics often involves solving differential equations that explain governing laws or processes. Efficiently solving differential equations forms an important aspect of computational methods. Physics-Informed Neural Networks allow physical rules in the form of differential equations to be integrated into deep learning frameworks. Even though they are proven to be highly useful in various applications, they are still outperformed by traditional solvers. Many times, PINNs are unable to solve PDEs accurately. Approximating the solution of PDE by expanding the solution as a weighted sum of a set of basis functions forms the foundation of many numerical methods. To improve PINNs, we propose using basis expansions of solution as the final layer of PINN, making the PINN learn coefficients of basis functions across the domain rather than learning the complete solution. We show the effectiveness of this approach by solving one-dimensional ODE with varying frequencies and a benchmark PDE, the wave equation. By using a few appropriate basis expansions, PINNs can learn solutions more accurately and in a lower number of steps.   


### Instructions

Just make sure requirements are met and run the notebooks.


### Cite:

Still under review 
