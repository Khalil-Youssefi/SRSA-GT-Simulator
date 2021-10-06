# SRSA-GT Simulator
Please use the "SRSA-GT.exe" file to start the simulator and select the desired Scene (S, U, H, C, C2). You can also alter the algorithm parameters as well as the experiment name.

Setting a unique Experiment Name will result in new CSV files with the results of the simulation. To apply the changes, press the "Save CFG" button.

Please note that running multiple simulations with the same Name, Scene and Settings will be stored together in CSV files under the Experiment Name.

Lines of the main generated CSV file (i.e., file ended with the word "Records") include the following data:

+-----------------------------+

Swarm Size

Scene

Experiment

Max Memory Size

Maximum Velocity

MaxTime (minuets)

Target Radius

FF_THR

C1

C2

T_RR

MPR

MD

MPP1

MPP2

Use Mem

Use MA

NR

eo

ei

Use GT

Swarm Size

Search Duration

Iterations (time steps)

Path Length

Route traveled by the Swarm

+-----------------------------+

For a detailed description of these parameters (except "NR", "eo", and "ei", which are new parameters of the SRSA-GT), please kindly check the primary paper of the SRSA algorithm (https://doi.org/10.1016/j.eswa.2021.114907).

To reset the algorithm parameters to the default parameters (i.e., parameters suggested by the authors), use the "Load Author's CFG" button.
