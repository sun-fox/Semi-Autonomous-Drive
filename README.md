# Semi-Autonomous-Drive
This repository contains the software implementation and simulation testing of the code for a lane assist on roads.

## Steps to Run Simulation:
* **Step 1**: Inorder to run this project you will have to download udacity simulator suitable for your OS. 
* **Step 2**: Now open the simulator after installation.
* **Step 4**: change directory to Behaviour_cloning folder by running 'cd .\Behaviour_cloning\' 
* **Step 5**: Then run 'python main_drive.py' 
* **Step 6**: Now get back to the udacity simulator and click on *Autonomous mode* button, this will connect the simulator with the web socket and then it will start transferring frames to the flask api endpoint where it will be processed and then the output vectors will be predicted using the weights stored in the model.h5 file.
* **Step 7**: Tada!! Enjoy the satisfying simulation