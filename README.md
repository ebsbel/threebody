# threebody
Simulation of the three body problem using physical laws and three different neural network methods.

## Simulation
To simulate the three bodies using physical laws, use the notebook ThreeBodyProblem_SimulationOfBodies.ipynb. Use the function test_data = run_parameter_sweep(800, 6, 0.8). Here 800 is the maximum number of simulation steps. 6 is the number of variations of the velocities. As there are 6 velocities, in x and y direction for each of the three bodies, the number of simulation runs will be 6^6 = 46 656, giving a datafile of size 1GB. 0.8 is the velocity range in percent, i.e. ±80%.

## Neural networks
Several methods are tested in the notebook structuredthreebodyproblemmodelling-kaggle.ipynb.