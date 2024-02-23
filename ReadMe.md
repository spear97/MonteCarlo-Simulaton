# MonteCarlo-Python

## Table of Contents
- [Description](#Description)
- [Application](#Application)
- [What is Monte Carlo?](#MonteCarlo)
- [Outputted Figures](#Figures)

## Description
This project was created for the Programming Language Concepts Class, where the assignment was to develop a Monte Carlo Simulation using Python. The implementation was done using Python, Visual Studio, along with libraries such as NumPy, Pandas, and Matplotlib. The main purpose of this program is to generate figures that plot the results of compound interest for a given amount and show how they evolve over time.

## What is Monte Carlo?
Monte Carlo is a computational method that utilizes sampling and statistical techniques to solve problems and make predictions. It is predominantly used in various fields such as mathematics, physics, engineering, economics, finance, and computer science.

In Monte Carlo simulations, random numbers are used to model the behavior of complex systems or to approximate mathematical expressions that are difficult or impossible to solve analytically. By generating a large number of random samples, statistical averages and probabilities can be calculated, leading to useful insights and predictions about the system under study.

For example, Monte Carlo simulations can be used to:
- Approximate the value of complex integrals.
- Assess financial risks.
- Optimize processes.
- Simulate particle interactions in physics.
- Perform uncertainty analysis in engineering, among many other applications.

Overall, Monte Carlo methods are a powerful and versatile tool for solving problems where deterministic approaches are not feasible or practical.

## Outputted Figures

### Figure 1
This figure displays the compound interest returns and ending values for a given amount over time.

| Return  | Ending Value  |                    
| ------- | ------------- |                                 
| 0.4832  | $24,832.31    |                 
| 0.2379  | $40,740.51    |                 
| -0.0388 | $49,159.19    |                
| -0.3033 | $44,249.31    |                
| -0.0324 | $52,816.96    |               
| 0.2946  | $78,378.39    |                 
| -0.1397 | $77,428.81    |               
| 0.3679  | $115,914.96   |                
| 0.2775  | $158,082.14   |                
| 0.1877  | $197,750.36   |                
| 0.2916  | $265,410.40   |                
| 0.2615  | $344,821.80   |                
| 0.4257  | $501,618.93   |                
| 0.1066  | $565,080.48   |                
| 0.3135  | $752,256.64   |                
| 0.1533  | $877,569.22   |
| 0.2088  | $1,070,776.35 |
| 0.2139  | $1,309,827.11 |
| 0.2867  | $1,695,307.84 |
| -0.4461 | $948,962.88   |
| 0.1131  | $1,066,293.69 |
| -0.0814 | $989,494.70   |
| 0.1294  | $1,127,499.11 |
| 0.3389  | $1,519,571.03 |
| 0.0395  | $1,589,538.95 |
| 0.158   | $1,850,640.97 |
| 0.0263  | $1,909,280.72 |
| 0.0062  | $1,931,138.50 |
| -0.0436 | $1,856,947.91 |
| 0.0657  | $1,989,017.62 |

### Figure 2
This figure provides statistical information about the generated compound interest returns.

- Count:  5000
- Mean:  $4,870,854,880,780.73
- Standard Deviation (SD):  $2,580,601,954,146.07
- Max:  $27,312,044,932,395.73
- Min:  $493,804,909,347.42 

| Percentage | Return |
| ---------- | ------ |
| 5%         | $1,854,393,123,923.65 |
| 10%        | $2,253,719,396,768.21 |
| 15%        | $2,555,208,541,792.83 |
| 25%        | $3,061,819,051,491.75 |
| 75%        | $6,008,191,818,852.21 |
| 85%        | $7,241,025,149,410.60 |
| 90%        | $8,170,344,044,181.43 |
| 95%        | $9,899,708,099,254.17 |
