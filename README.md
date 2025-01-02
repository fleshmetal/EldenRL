# EldenRL - Elden Ring Ai
Reinforcement Learning for Elden Ring on Windows11.  

This is a forked version of [ocram444s PPO RL Elden Ring implementation](https://github.com/ocram444/EldenRL). This fork contains changes that improve training procedure quality.

# Modifications:

**Free Game window:** The window frame is located (that which is rendered in screen space) to allow the game window to be free. This looks for the first 'Elden Ring' window.

**Auto-locate 'Next':**  Functionality has been added to locate the 'Next' tag to differentient between training episodes, after the 'YOU DIED' splash appears.

**requirements.txt:** A requirements file has been provided to produce a baseline sufficient Python environment.


