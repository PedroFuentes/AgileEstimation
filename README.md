# AgileEstimation

Materials supporting research and presentations on Agile estimation techniques

## Files:

* Velocity with Team Strength.xlsx: Spreadsheet showing how to normalize velocity against team strength for capacity planning that accounts for absences, sprint length variations, team staffing level changes, etc.
* Pi Sampling.xslx: Spreadsheet for exploring some basic concepts of Monte Carlo simulation using the estimation of π.
  * Simulation worksheets
    * Manual Pi: Basic framework supporting visualization and calculation rolling dice to obtain sample data. The use of dice only demonstrates discreet sampling of integers. Enter the results of dice rolls in the X and Y columns and extend the Distance calculation for all entered points.
    * Random Pi: Like the _Manual Pi_ framework but with random generation of 1000 points and a tuneable to specify how many points to use. This allows you to play with the number of samples. The values are decimal demonstrating sampling over a continuous space. Change the Points value to adjust how many samples are used.
    * Parallel Pi: Larger scale simulation framework supporting up to 500 parallel simulations of up to 100 samples in each simulation. Change the Samples and Simulations values to adjust the simulation parameters.
  * Other worksheets
    * Frequency: Support data for the Parallel Pi worksheet. Do not change.