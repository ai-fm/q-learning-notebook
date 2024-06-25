# Intro to Reinforcement Learning: Q-Learning



### Hands-on introduction to Q-Learning
---

This Jupyter Notebook provides introductory exercises for Q-Learning in the field of Reinforcement Learning. 

To open the Jupyter Notebook and run the code in Google Colab click on the following badge:

<a target="_blank" href="https://colab.research.google.com/github/ai-fm/q-learning-notbeook/blob/main/Q_Learning_exercise.ipynb">
  <img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/>
</a>

Otherwise you can find the notebook in the repository here.


### Exercise on Expected Accumulated Reward
---

<img src="MDP_exercise.svg" alt="Exercise on Expected Accumulated Reward" width=700px>

**Solution:**
We use a discount factor of 1.0 .  
From the kitchen ...
- choosing action "go to living room" gives us the expected reward:  
  1.0 * 10 + 0.9 * 10 + 0.1 * (-100) = 10 + 9 - 10 = 9
- choosing action "go to bedroom" gives us the expected reward  
  1.0 * 30 + 0.7 * 10 + 0.3 * (-100) = 30 + 7 - 30 = 7

**Conclusion:** Choosing the action "go to living room" is the safer option here and will provide a higher reward on average.


# Credits
---

- Joshua Wendland, Chair of Formal Methods and Artificial Intelligence, Ruhr University Bochum
- [Huggingface Deep Reinforcement Learning Course](https://huggingface.co/learn/deep-rl-course/unit0/introduction)
- [Gymnasium](https://gymnasium.farama.org/)
- Flaticon: smalllikeart, Freepik, photo3idea_studio