# Numerical Analysis
- My personal MATLAB toolbox for numerical analysis
- May. 12, 2021 ~ Present

## 1. Numerical solution of first order ODEs
### Forward Euler Method - Explicit | [Code](https://github.com/OH-Seoyoung/Numerical_Analysis/blob/master/Numerical_solution_of_ODEs/Forward_Euler_Method.m)
y<sub>i+1</sub> = y<sub>i</sub> + f(t<sub>i</sub>, y<sub>i</sub>)&Delta;t + O(&Delta;t<sup>2</sup>) 
- It uses the slope at each point to exgtrapolate and find the next point  
- O(&Delta;t<sup>2</sup>)
--------------------
### Backward Euler Method - Implicit
y<sub>i+1</sub> = y<sub>i</sub> + f(t<sub>i+1</sub>, y<sub>i+1</sub>)&Delta;t + O(&Delta;t<sup>2</sup>)  
- O(&Delta;t<sup>2</sup>)
----------------------
### Midpoint Method
y<sub>i+1</sub> = y<sub>i-1</sub> + 2f(t<sub>i</sub>, y<sub>i</sub>)&Delta;t + O(&Delta;t<sup>3</sup>)  
- Symmetric method using Taylor expansion that involves only odd powers of &Delta;t
- O(&Delta;t<sup>3</sup>) -> More accurate  
-> but require special initialisation

## Reference
```
[1] Finite-difference Numerical Methods of Partial Differential Equations in Finance with Matlab, Aitor Bergara
[2] Aitor Bergara, http://www.ehu.eus/aitor/
```
