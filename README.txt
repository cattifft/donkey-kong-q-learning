There are three main files. _main.py is the unchanged program from !!!!!plemaster01 on github: https://github.com/plemaster01/PythonDonkeyKong !!!!! which allows you to play the level using keyboard input through pygame. 

simple_main.py is the Q-Learning version using a reduced environment lacking all assets besides Mario, ladders, and platforms.
dangerous_main.py is the version with all assets included.

For both files, you can choose to set the boolean RENDER depending on whether you would like to see a policy or have faster training.
Right now, both files are set to load the policies they found from training for the agent. You can also set the number of episodes on lines 811 and 899 respectively. 

As they are right now, both files can be run to display what the agent learned from respective training sessions.
