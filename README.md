# Current-Emerging-Trends-in-Computer-Science

This project is from coursework in CS-370 -- Current and Emerging trends in Computer Science. In this course, I explored various types of neural network architectures including convolutional neural networks, (CNNs) recurrent neural networks, (RNNs) deep Q-learning networks, (DQNs) and actor-critic models. This project specifically I was tasked with developing a deep Q-learning model to train a pathfinding agent in the game "TreasureHunt". 
The basic game setup was provided including the GameExperience.py and TreasureMaze.py as well as setup in the ipynb file, my only focus for the project was developing both a functional, and optimal algorithm to train the agent. I utilized an epsilon-greedy algorithm for balancing exploration with exploitation decision-making with an epsilon value of 0.1. This epsilon value means that for every state-action, the algorithm will choose to exploit previously successful routes 90% of the time and explore a new path at random 10% of the time. After only 96 epochs of training (about 7.32 minutes) the model is able to reach the *treasure* with 100% accuracy every run now.

![successful_maze](https://github.com/sacredpoom/Current-Emerging-Trends-in-Computer-Science/assets/20672168/ea8a34e6-e471-4a66-a688-68374fe58e52)

### **TOOLS**
* Python
* Jupyter Notebook
* TensorFlow - Keras

This course focused on both technical innovations in the field of Computer Science as well as ethical concerns and responsabilities. Ethical concerns of bias can be addressed by transparency in training data and ensuring bias-free datasets, and continued audits and maintenance to ensure no new bias is introduced to models. AI development has already had great impact on everyday life and will continue to have great societal impact in coming years. As a computer scientist it is important to ensure technology is designed and developed ethically and responsibly. Technology is meant to improve our quality of life, not detract from it. This course has been a great experience in learning how critical technologies like reinforcement learning have developed and will potentially continue to develop. Reinforcement learning has already seen wide use in fields such as robotics, healthcare, finance, and energy management among many others demonstrating its versatility in solving complex problems. AI may not have the same intuition and heuristics that humans have, it does excel in sorting through massive amounts of data and recognizing patterns impossible for humans to see. 

Moving forward in my career, I will bring not only my knowledge of neural networks and AI, but also my understanding of the ethical framework guiding their application. This course has helped broaden my perspective on potential impact of technology on society and the importance of its responsible use and development. 
