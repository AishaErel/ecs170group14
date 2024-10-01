# In class group project, ecs170group14
Implementing RL to enhance the performance of an agent in a snake game

Group Members: Shrinidhi Prasanna, Ayse (Aisha) Erel, Imen Belhadj, Fatima Mustafa, Saniya Kotwal, Kamyar Alishahi

The main objective of our project was to develop an AI agent that would be capable of navigating and potentially mastering the classic Snake game using simple reinforcement learning techniques. The first subpart of our project, dubbed Part I hereafter, consisted of utilizing existing code for the purpose of agent training using a Deep Q Learning Implementation. The primary focus of Part I was to modify the game environment in numerous ways and monitor the agent’s performance in these environments. Part I consisted of three different game models. Our first adjustment to the game environment entailed adding a variety of fruits in varying sizes. The second entailed including a variable number of obstacles. The third implemented a moving obstacle and a special element that, upon collection, would not penalize the agent for the next three collisions. The second subpart of our project, dubbed Part II hereafter, consisted of implementing an agent dependent on Q-Learning rather than Deep-Q-Learning to play the base game. This implementation resulted in three different models, where the first and third model applied the new Q-Learning algorithm to the existing Snake Game environment, and the second model applied the same algorithm but to a completely novel game environment we defined. 
Despite the game’s seemingly straightforward mechanics, our challenges primarily lay in training the agent to play the game optimally, carefully balancing exploration and exploitation by adjusting the game’s reward and penalty values accordingly. To evaluate the performance of our agents in both Part I and Part II, we utilized performance metrics such as average reward per episode, success rate, training efficiency, and policy entropy. These metrics and visual observation of the agent’s progress with each additional round of training allowed us to better grasp the efficiency of reinforcement learning in mastering tasks requiring complex learning. 

References: 

1- Original Snake Game GitHub Repository: https://github.com/patrickloeber/snake-ai-pytorch
	It was this code that served as our foundation from which we built upon. We primarily adjusted the game and agent files in our implementations.

2- Snake Game AI Implementation Article: https://medium.com/@nancy.q.zhou/teaching-an-ai-to-play-the-snake-game-using-reinforcement-learning-6d2a6e8f3b1c
	It was this article that took us through the code and allowed us to understand the code we were using.

3- Snake Game AI Implementation Video: https://www.youtube.com/watch?v=L8ypSXwyBds&t=1229s
	It was this video that allowed us to understand the virtual environment and how our foundational code and the agent would appear in said virtual environment

4- Q-Learning, a Complete Example: https://www.youtube.com/watch?v=iKdlKYG78j4
	It was this video that helped us implement our Q-Learning agent.

