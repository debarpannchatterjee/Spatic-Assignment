# Spatic-Assignment

This repository contains 2 solutions with different assumptions since the problem statement was not clear.

Solution 1 : This is a more generalised solution which compares each entry in the dataset with every other entry to find all possible pairs. This approach took 3.5 hours to run.

Solution 2: Since the desired output required only one addition column stating True or False in front of every entry, I have assumed for this solution that our sole objective is to find wether a similar record exists for each entry and not to find all the records that are similar to each other. Hence, I have put a break statement in the loop as soon as we find a single match. This brough down the running time to less than a second.

Both the solution produce the same output csv file.

There could be another possible solution that uses vectors to perform the comparisons instead of loops. This approach should drastically reduce the time for solution 1. However, I thought that such an approach would be beyond the scope of this assignment.

