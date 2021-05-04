# GEOG5990 Programming Online Portfolio
This webpage is made using the Slate Jekyll Theme.
This webpage will give access to the different projects I have completed during the module.
Each link will take you to a github folder where you can view or download the code.

### Practical Workshops
* [GEOG5990 Homepage](https://github.com/b3nlewis/GEOG5990)
* [Agent Based Modelling](https://github.com/b3nlewis/GEOG5990/tree/main/1)
* [Code Shrinking I](https://github.com/b3nlewis/GEOG5990/tree/main/2)
* [Code Shrinking II](https://github.com/b3nlewis/GEOG5990/tree/main/3)
* [Building Tools](https://github.com/b3nlewis/GEOG5990/tree/main/4)
* [Agents!](https://github.com/b3nlewis/GEOG5990/tree/main/5)
* [I/O](https://github.com/b3nlewis/GEOG5990/tree/main/6)
* [Communicating](https://github.com/b3nlewis/GEOG5990/tree/main/7)
* [Animation/Behaviour](https://github.com/b3nlewis/GEOG5990/tree/main/8)
* [GUI/Web Scraping](https://github.com/b3nlewis/GEOG5990/tree/main/ABM)

## About ABM

The final version of the agent based model (ABM), which is available from the GUI/ Web Scraping link is a
combination of all the processes I have learnt in GEOG5990. 

### Summary

The ABM allows agents (sheep) to interact with the environment and each other. Agents are placed randomly in the starting environment, each update the agents move randomly one unit,
eat the environment and prescribed amount, and if within range of other agents share food. Additionally, the agents have a random chance of sicking up food units which then adds to
the environment. The model continues to run until the stopping condition is met. The stopping condition is based on a randomly generated food total (between 60 and 100) and the number
of agents. When all of the agents meet the food total the program stops. When exiting the program, the environment, food stored and time completion are exported to txt files.

### Associated files

Input: in
      A txt file with values which range between 0 and 255. This is the environment and the agents eat this.
      
Output: dataout
      This is the environment after the model has completed. It will be altered due to agents eating it.
Output: store
      This is the total amount of food units stored by all agents. 
Output: time
      Records how long the script takes to complete. Normally takes between 3 to 4 seconds.
      
### How to use

This script can be run in IDLE or command line. Using the command line is recommended as variables (number of agents, number of iterations and neighbourhood size) can be changed.
Varaibles are optional and defaults of 50, 20, 20 are set. In order to use command line type "python model.py -h" to bring up help information.

### Testing

This script has been tested on two different computers using both Spyder and AnacondaPrompt. Both work on both computers.
The script has been tested using different parameters. The script can only use 100 agents at a time due to limitations with the html website used to randomly place agents in a scene.
Therefore an if statement was implemented to detect agent numbers over 100 and provide a new value.
Additionally, all sections have time code so that the amount of time they were active for could be monitored.
Finally, test code was added at the bottom to detect if the script finsihed early. If the agents did not store enough food a message would print saying the script has failed. Failures
happen when the script is closed early and when the code was unfinished.


### Independant Programming Project
