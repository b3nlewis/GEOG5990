# Readme
This script is an agent based model (ABM), where agents randomly walk around an area, eat the environment and share food with other agents.
This is the final version of the ABM, which has a inputs from "in.txt" and from an html file, and outputs into "dataout.txt, stored.txt and time.txt".
To run this script download and open the commandline. Type <b>python model.py -h</b>, this will show you what variables you need to add. Otherwise you can leave it and use
the default settings. See documentation for further details.

## Files
### Input
* in.txt:
* html:
### Output
* dataout.txt:
* stored.txt:
* time.txt:

## How to use
This script required python 3.
It also depends on:
* matplotlib
* time
* csv
* random
* requests
* BeautifulSoup
* tkinter
* sys
* argparse

This script can be run in commandline or IDLE. Using the IDLE you can only use the default arguments. Using commandline you can use default arguments or select your own.  \
In commandline type __python model.py__ to run default settings  \
To select your own variables in commandline type __python model.py -h__ this will give you a list of the arguments you need to use:
* __-a__ for num of agents
* __-i__ for number of iterations
* __-n__ for neighbourhood size

When the script is run a GUI will appear. To complete the script on the GUI menu bar click __Run__.
The script will run and the GUI will show the animation. When completed, a line in the commandline will tell you to close/exit the GUI. After you do this data will be exported to the txt files. 
