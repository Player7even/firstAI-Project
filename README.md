# firstAI-Project



# Tasks and objectives
The aim of the project was to develop a self-learning artificial intelligence for the game Tic-Tac-Toe using the Q-learning algorithm. The AI had to take various aspects into account. 
Firstly, it had torecognize and learn the game patterns independently during training through simulated games without being dependent on predefined winning patterns. 
The AI should be able to compete against human players, which means that it not only persistently stores its newly learned knowledge, but also retrieves and uses it in real time.
Measurable learning successes should be demonstrated by continuously improving game performance and making the AI virtually unbeatable.

# How to use?
There are already 3 trained PKL files available, which means that the program does not need to be retrained, but they must be stored INDIVIDUALLY in the folder with the QDeepLearning.py file.
To do this, you must remove the number of passes from the file name and rename it “tictactoe_ai”.
In order to train a new run, you must remove the previous file from the folder so that the program can create a new one. Otherwise, it will train on the previous file.

Optionally, you can rename the trained file being loaded in line 372. 
Note that if you do this, the filename must also be changed either in the code where it is saved or directly in the directory.
