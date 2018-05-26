### ViZDoom reinforcement learning

Implemented DQN [2] and A3C [3] algorithms for ViZDoom [1] basic scenario.

### Dependencies

* python3
* opencv-python
* [tensorflow](https://github.com/tensorflow/tensorflow)
* [ViZDoom](https://github.com/mwydmuch/ViZDoom)

### How to run

* Install [ViZDoom](https://github.com/mwydmuch/ViZDoom) and other dependencies
* Set path to it in variable *vizdoom_path*
* Set path to vizdoom_rl in *path_work_dir*
* Run:
  * DQN: *python3 agent_dqn.py*
  * A3C: *python3 agent_a3c.py*

### References
[1] Michał Kempka, Marek Wydmuch, Grzegorz Runc, Jakub Toczek, Wojciech Jaśkowski. ViZDoom: A Doom-based AI Research Platform for Visual Reinforcement Learning. arXiv:[1605.02097](https://arxiv.org/abs/1605.02097), 2016.

[2] Volodymyr Mnih, Koray Kavukcuoglu, David Silver, Alex Graves, Ioannis Antonoglou, Daan Wierstra, Martin Riedmiller. Playing Atari with Deep Reinforcement Learning. arXiv:[1312.5602](https://arxiv.org/abs/1312.5602), 2013.

[3] Volodymyr Mnih, Adrià Puigdomènech Badia, Mehdi Mirza, Alex Graves, Timothy P. Lillicrap, Tim Harley, David Silver, Koray Kavukcuoglu. Asynchronous Methods for Deep Reinforcement Learning. arXiv:[1602.01783](https://arxiv.org/abs/1602.01783), 2016.
