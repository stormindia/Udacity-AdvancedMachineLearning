For this assignment, you can find the smartcab folder containing the necessary project files on the Machine Learning projects GitHub(https://github.com/udacity/machine-learning), under the projects folder. You may download all of the files for projects we'll use in this Nanodegree program directly from this repo. Please make sure that you use the most recent version of project files when completing a project!

This project contains three directories:

/logs/: This folder will contain all log files that are given from the simulation when specific prerequisites are met.
/images/: This folder contains various images of cars to be used in the graphical user interface. You will not need to modify or create any files in this directory.
/smartcab/: This folder contains the Python scripts that create the environment, graphical user interface, the simulation, and the agents. You will not need to modify or create any files in this directory except for agent.py.
It also contains two files:

smartcab.ipynb: This is the main file where you will answer questions and provide an analysis for your work. -visuals.py: This Python script provides supplementary visualizations for the analysis. Do not modify.
Finally, in /smartcab/ are the following four files:

Modify:
agent.py: This is the main Python file where you will be performing your work on the project.
Do not modify:
environment.py: This Python file will create the smartcab environment.
planner.py: This Python file creates a high-level planner for the agent to follow towards a set goal.
simulator.py: This Python file creates the simulation and graphical user interface.
Running the Code
In a terminal or command window, navigate to the top-level project directory smartcab/ (that contains the three project directories) and run one of the following commands:

python smartcab/agent.py or
python -m smartcab.agent

This will run the agent.py file and execute your implemented agent code into the environment. Additionally, use the command jupyter notebook smartcab.ipynb from this same directory to open up a browser window or tab to work with your analysis notebook. Alternatively, you can use the command jupyter notebook or ipython notebook and navigate to the notebook file in the browser window that opens. Follow the instructions in the notebook and answer each question presented to successfully complete the implementation necessary for your agent.py agent file.
