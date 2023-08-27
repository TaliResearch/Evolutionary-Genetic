# Evolutionary-Genetic
Two strats predicting future stock price moves - genetic algorithm vs genetic program.

Genetic Algorithm: Bit string population evolution to predict if the following day's price will rise or fall. 
Genetic Program: Tree based population evolution, minimising the error between predicted price and actual price

Base Genetic Description:
In this code, we start by loading the Apple stock price data from a CSV file. We define constants such as the population size, 
the number of generations, and the mutation rate. The length of the chromosome is determined by the number of trading days in the data.

