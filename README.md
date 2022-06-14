# Gurobi
Collection of optimization programming from previous classes and personal projects.

## Supermarket Sweep
A final project for Advanced Optimization (ISYE 4133) - only included personal contributions.   
A TSP problem derived from an older American television game show "Supermarket Sweep".
Solution formulated as a TSP model with polynomial number of constraints.

1. Original data file "supermarket_sweep.csv" provided in class. This file contains information about 56 different grocery items with each item's name, monetary value, and X and Y coordniates within the store aisles.
2. The shopper has a 90-second window to collect the items and return to the start point location. 
3. The shopper can include at most 15 items in the cart.
4. The shopper moves at a speed of 10 ft/sec and takes 2 seconds to pick up an item
5. For simiplicity, the shopper may only grab one of each item.
6. The shopper must take one continous path through the store.
7. The goal of the shopper is to maximize the total value of the items in cart before returning. 
