# Evolutionary-Genetic
Two strats predicting future stock price moves - genetic algorithm vs genetic program.

Genetic Algorithm: Bit string population evolution to predict if the following day's price will rise or fall. 
Genetic Program: Tree based population evolution, minimising the error between predicted price and actual price


Base Genetic Description:
In this code, we start by loading the Apple stock price data from a CSV file. We define constants such as the population size, 
the number of generations, and the mutation rate. The length of the chromosome is determined by the number of trading days in the data.
Next, we define the fitness function, which calculates the cumulative returns based on the 
chromosome and the stock price data. The fitness is the final cumulative return.
We initialize the population randomly with binary chromosomes. Then, in each generation, 
we evaluate the fitness for each chromosome, select parents for reproduction using tournament selection, 
create offspring through crossover, apply mutation to the offspring, and replace the old population with the offspring.

Finally, we find the best solution based on the highest fitness score and print the best solution and its fitness.
Note that this code is a simplified example but we must still ensure that we have the necessary 
stock price data in the correct format.
