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
Defined a new function called `simdivis()` that returns a 1 if a number form 1 to 1000 is divisible by 3, 5 or 9 and 0 if not.  

**Seed**   
This sets our seed for reproducibility of results.

**Experiment**   
Repeat  the tosses 50, 2000 and 10,000 times using the `replicate()` function and get an average of each of the tosses.  

**Vizualisation**   
Calculating the cumulative mean across all epochs. 
Create a scatter-plot to show the average of each repeated experiment against the `abline(`) of true calculated probability. 

<img width="1440" height="898" alt="Image" src="https://github.com/user-attachments/assets/fdb05d23-d3a8-4188-b7b7-4d7c8d07490d" />

## ACKNOWLEDGEMENTS
This simulation is based on an in-class example by Dr. Wei- Min Huang 

## PROJECT STRUCTURE      
|[Simulation- Law of Large Numbers](https://github.com/leta199/Simulation-Law-of-Large-Numbers-)   
|├──[analytical](https://github.com/leta199/Simulation-Law-of-Large-Numbers/tree/main/analytical)    
│  ├──[LLN pdf analytical](https://github.com/leta199/Simulation-Law-of-Large-Numbers/blob/main/analytical/LLN%20pdf%20analytical.pdf)     
│  └──[LLN tex](https://github.com/leta199/Simulation-Law-of-Large-Numbers/blob/main/analytical/LLN.tex) 
|├── [Law of large numbers sim/](https://github.com/leta199/Simulation-Law-of-Large-Numbers-/blob/main/Law_of_Large_Numbers_sim.r)   
|└── [README.md/](https://github.com/leta199/Simulation-Law-of-Large-Numbers-/blob/main/README.md)  

## AUTHORS   
[leta199](https://github.com/leta199)  
