# Time Series Analysis Cell Trajectory Data
We considered two types of cells, a softer one vs a 2x stiffer one.
In the Soft and Rigid directories, we have a total of 300 CSV files (150 in each directory) containing the trajectory data for soft and slightly rigid cells. 
In both cases, the starting point is the same and evenly distributed at the inlet. 

When a cell completes its travel from one side of the geometry to the other, it reappears at the starting side. 
Each original CSV file contains approximately 14-15 travel instances for each cell.

To extract these 14-15 travel instances from each file, use the splitall.py script. 
Running this script will read the CSV files in the current directory and split each file accordingly. 
The resulting files are stored in the Soft_Directory and Rigid_Directory.
