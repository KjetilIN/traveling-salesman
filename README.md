# Traveling salesman problem 
Traveling salesman problem solved. Mandatory assignment for the master course, IN4050.

![image](./report/images/exhaustive_search_result_10_cities.png)


## Results for 6 Cities

| Algorithm           | Best Route Distance | Time Taken |
|---------------------|---------------------|----------------|
| Exhaustive Search    | 5018.809          | 0.003         |
| Hill Climbing        | 7486.31          | 1s       |


## Results for 10 Cities

| Algorithm           | Best Route Distance | Time Taken |
|---------------------|---------------------|----------------|
| Exhaustive Search    | 7486.309            | 13.47s        |
| Hill Climbing        | 11434.41            |  2.9s        |
| Genetic Algorithm    | 7486.309         | 1.9        |


The following was the **Genetic Algorithm Configuration**: 

| Parameter          | Value         |
|--------------------|---------------|
| Population Size     | 200           |
| Generations         | 200           |
| Mutation Rate       | 0.05 (5%)     |
| Crossover Rate      | 0.8 (80%)     |
| Selection Method    | Roulette Selection |
| Elitism             | Yes (Top 5%)  |
| Crossover Operator  | Edge Recombination |
| Mutation Operator   | Swap Mutation |


## Results for 24 Cities

| Algorithm           | Best Route Distance | Time Taken |
|---------------------|---------------------|----------------|
| Exhaustive Search    | NaN          | Inf      |
| Hill Climbing        | 13563.21     |      3.6s   |
| Genetic Algorithm    | 12633.75          |  2m, 10s         |

The following was the **Genetic Algorithm Configuration**: 

| Parameter          | Value         |
|--------------------|---------------|
| Population Size     | 500           |
| Generations         | 3000          |
| Mutation Rate       | 0.05 (5%)     |
| Crossover Rate      | 0.8 (80%)     |
| Selection Method    | Roulette Selection |
| Elitism             | Yes (Top 5%)  |
| Crossover Operator  | Edge Recombination |
| Mutation Operator   | Swap Mutation |