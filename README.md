# AgileEstimation

Materials supporting research and presentations on Agile estimation techniques

## Files:

* Velocity with Team Strength.xlsx: Spreadsheet showing how to normalize velocity against team strength for capacity planning that accounts for absences, sprint length variations, team staffing level changes, etc.
* Pi Sampling.xlsx: Spreadsheet for exploring some basic concepts of Monte Carlo simulation using the estimation of π.
  * Simulation worksheets
    * Manual Pi: Basic framework supporting visualization and calculation rolling dice to obtain sample data. The use of dice only demonstrates discrete sampling of integers. Enter the results of dice rolls in the X and Y columns and extend the Distance calculation for all entered points.
    * Random Pi: Like the _Manual Pi_ framework but with random generation of 1000 points and a tuneable to specify how many points to use. This allows you to play with the number of samples. The values are decimal demonstrating sampling over a continuous space. Change the Points value to adjust how many samples are used.
    * Parallel Pi: Larger scale simulation framework supporting up to 500 parallel simulations of up to 100 samples in each simulation. Change the Samples and Simulations values to adjust the simulation parameters.
  * Other worksheets
    * Frequency: Support data for the Parallel Pi worksheet. Do not change.
* Distribution Sampling.xlsx: Spreadsheet for exploring some basic concepts of Monte Carlo simulation using the rolling of dice.
  * Simulation worksheets
    * Two Die Rolls: Simulates the rolling of two 4-sided (tetrahedral) dice and analyzing the distribution of their sum. A tuneable parameter lets you decide how many rolls to consider in your analysis.
    * One Die Roll - Computed: Simulates the rolling of two 4-sided (tetrahedral) dice by computing their values from a single roll in the range 1-16 (real world rolling a 20-sided die and ignoring 17-20) and analyzing the distribution of their sum. A tuneable parameter lets you decide how many rolls to consider in your analysis. Demonstrates the principle of distribution "flattening" by computation as a means of creating a reference sample set.
    * One Die Roll - Lookup: Simulates the rolling of two 4-sided (tetrahedral) dice by lookup up the  sum and analyzing the distribution of their sum. A tuneable parameter lets you decide how many rolls to consider in your analysis. Demonstrates the principle of distribution sampling by looking up values in the reference sample set.
  * Other worksheets
    * Frequency: Support data for distribution analysis. Do not change.
* Cycle Time Estimation.xlsx: Fairly complete framework for Monte Carlo cycle time-based forecasting running 1000 parallel simulations.
  * Sample Data: The sheet where you enter the cycle times from which to sample. These should be from the team's historical data.
  * Command Sheet: Once you've entered the Sample Data, this sheet gives you all you need to forecast unless you want to dig into the details of how the simulation runs. Enter the data in yellow fields to parameterize your simulation and select your forecasts. This sheet also includes a graph of the distribution of the simulation results.
  * Simulations: The data and computations for the parallel computations.
  * Output: The raw simulation week and likelihood data with a copy of the graph shown on the Command Sheet.