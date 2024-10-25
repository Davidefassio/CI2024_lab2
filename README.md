# Lab 2: Traveling Salesman Problem

Solve Traveling Salesman Problem using two different methods.

## Christofides Algorithm

This method returns an approximation that is not worse than 1.5x of the best solution.

It runs in O(n^3) on a complete graph of n nodes (dominated by the perfect matching step).

## Evolutionary Algorithm

This method evolves a population of solutions to effectively solve the TSP.

The solution is encoded in the genome as a path represented by one-time items.

I used a hyper-moder generational approach with elitism.

The genetic operators used are:

- Swap Mutation
- Inversion Mutation
- Order Crossover

N.B.: the mutations can be applied multiple times.

## Results

To obtain the results choose the cvs with the problem to solve and run the code.

Results and plots will appear at the bottom.
