# CS370-sai-g


Briefly explain the work that you did on this project: What code were you given? What code did you create yourself?

The starting point for this project was a starter code that comprised of the TreasureMaze environment class that represents the grid world; the GameExperience class that deals with memory storage of previous episodes; some utility functions for visualization and gameplay evaluation, and a predetermined Keras-based neural network model (build_model). I developed the deep Q-learning training algorithm in the qtrain function. My implementation included the creation of the training loop, application of the epsilon-greedy approach, storing state-action pairs in the experience replay buffer, sampling of mini-batches, and use of the early stopping mechanism based on completion tests to make sure that the pirate agent learned how to navigate to the treasure from any starting point.


Connect your learning from throughout this course to the larger field of computer science:

What do computer scientists do and why does it matter?

As a computer scientist, you create algorithms, develop software applications, and construct computing systems to address complicated and data-oriented issues in order to lay the groundwork for automation, artificial intelligence, and technological innovation in every field of business today. It matters because most of our world is digitalized and is only getting more digitalized with time.


How do I approach a problem as a computer scientist?

Problem solving as a computer scientist means that you carefully break down a complex issue into modular elements, determine the requirements, model an algorithm, and then test, debug, and iterate using performance data. 


What are my ethical responsibilities to the end user and the organization?

You need to make sure your systems are reliable and safe, especially in the cases of autonomous or machine learning models, while protecting user data privacy and avoiding bias at all times. You should also follow the laws, especially ones related to piracy and privacy, of the areas your users are located in.

