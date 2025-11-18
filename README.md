# Simulation-Law-of-Large-Numbers-
Testing out stochastic simulations to visualise the Law of Large Number (LLN) as one of the foundations of statistics and probability.   
This project will cover:

- Creating simualtion to calculate the probability of an integer from 1 to 1000 is divisible by 3,5 or 9.
- Proving Law of large numbers by visualising how simulation results converge to the analytical solution as number of replications (epochs) grows. 

[![Language: R](https://img.shields.io/badge/Language-R-276DC3.svg?style=flat-square)](https://www.r-project.org/)
[![Built with RStudio](https://img.shields.io/badge/IDE-RStudio-75AADB?style=for‐the‐badge&logo=rstudio&logoColor=white)](https://www.rstudio.com/)
![Status](https://img.shields.io/badge/Status-Completed-lightgrey)

## HOW IT'S MADE 
Languages used: R version (4.5.1)    
Environemnt: RStudio

## METHODS AND TECHNIQUES  
**Function creation**  
 Defined a new variable called `simdivis()` that returns a 1 if our number is divisible by 3, 5 or 9 and 0 if not.  
**Seed**   
This sets our seed for reproducability of results.
**Experiment**   
Repeat  the tosses 50, 2000 and 10,000 times using the `replicate()` function and get an average of each of the tosses.  
**Vizualisation**   
Create a scatter-plot to show the average of each repeated experiment against the `abline(`) of true calculated probability. 

## ACKNOWLEDGEMENTS
This simulation is based on an in-class example by Dr. Wei- Min Huang 

## PROJECT STRUCTURE      
|[Simulation- Law of Large Numbers](https://github.com/leta199/Simulation-Law-of-Large-Numbers-)   
|├──[Analytical solution pdf](https://github.com/leta199/Simulation-Law-of-Large-Numbers/blob/main/LLN%20pdf%20analytical.pdf)  
|├── [Analytical solution latex](https://github.com/leta199/Simulation-Law-of-Large-Numbers/blob/main/LLN.tex)  
|├── [Law of large numbers sim/](https://github.com/leta199/Simulation-Law-of-Large-Numbers-/blob/main/Law_of_Large_Numbers_sim.r)   
|└── [README.md/](https://github.com/leta199/Simulation-Law-of-Large-Numbers-/blob/main/README.md)  

## AUTHORS   
[leta199](https://github.com/leta199)  
