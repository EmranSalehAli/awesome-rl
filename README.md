A constantly evolving list of Reinforcement Learning papers, notes, books etc.

[atari]: ./icons/atari.png	"Atari 2600 games"
[doom]: ./icons/doom.png	"Doom game"
[sc]: ./icons/sc.png	"Starcraft game"
[go]: ./icons/go.png	"Go game"
[table]: ./icons/table.png	"Table games"
[nn]: ./icons/nn.png	"Neural Networks & Optimizers"
[robot]: ./icons/robot.png	"Real Robot Experiments"
[loco]: ./icons/loco.png	"Locomotion tasks"
[maze]: ./icons/maze.png	"Mazes & Labyrinths"

**Glossary:**

- :rocket: - state-of-the-art method in current domain at the moment of paper publication.
- :star: - valuable paper.

**Domain Tags**:
- **Model-based** - Model-based RL.
- **MARL** - Multi-Agent RL.
- ![atari] - Atari game (Atari).
- ![doom] - Doom game (Doom).
- ![sc] - Starcraft game (Starcraft).
- ![nn] - Neural Networks & Optimizers (NN).
- ![go] - Go game (Go).
- ![table] - Table games (Table).
- ![robot] - Real-robot applications (Robot).
- ![loco] - Real/Simulated robotic locomotion (MuJoCo, Roboschool etc).
- ![maze] - Mazes and Labyrinths (Maze).
- **Planning** - Complex planning problems.
- **Transfer** - Transfer learning.
- **RTS** - Real-Time Strategy video game.
- **FPS** - First-Person Shooter video game.

# Deep Reinforcement Learning

## Year 2018
**World Models**
  - [[arXiv](https://arxiv.org/abs/1803.10122)] [[blog](https://worldmodels.github.io/)] Ha and Schmidhuber; IDSIA, Google Brain, NNAISENSE
  - ![doom] Model-based, Doom

**Back to Basics: Benchmarking Canonical Evolution Strategies for Playing Atari**
  - [[arXiv](https://arxiv.org/abs/1802.08842)] Chrabaszcz et al.; University of Freiburg
  - ![atari] Atari

:rocket: **IMPALA: Scalable Distributed Deep-RL with Importance Weighted Actor-Learner Architectures**
  - [[arXiv](https://arxiv.org/abs/1802.01561v2)], [[pdf](https://arxiv.org/abs/1802.01561v2)]
  - Such et al.; Uber AI Labs
  - ![atari] ![maze] Atari, Maze

:star: **One-Shot Imitation from Observing Humans via Domain-Adaptive Meta-Learning**
  - [[arXiv](https://arxiv.org/abs/1802.01557v1)], [[pdf](https://arxiv.org/pdf/1802.01557v1.pdf)]
  - Finn et al.; UC Berkeley
  - ![robot] Robot, Meta-Learning

:rocket: **Regularized Evolution for Image Classifier Architecture Search**
- [[arXiv](https://arxiv.org/abs/1802.01548v2)], [[pdf](https://arxiv.org/pdf/1802.01548v2.pdf)]
- Real et al.; Google Brain
- ![nn] NN


## Year 2017
:rocket: **Deep Neuroevolution: Genetic Algorithms Are a Competitive Alternative for Training Deep Neural Networks for Reinforcement Learning**
  - [[arXiv](https://arxiv.org/abs/1712.06567)] Such et al.; Uber AI Labs
  - ![atari] ![loco] Atari, Locomotion

**Mastering Chess and Shogi by Self-Play with a General Reinforcement Learning Algorithm**
- [[arxiv](https://arxiv.org/abs/1712.01815)] Silver et al.; DeepMind
- ![table] Table

:rocket: **Rainbow: Combining Improvements in Deep Reinforcement Learning** (DQN improvements combined)
- [[arXiv](https://arxiv.org/abs/1710.02298)] Hessel et al.; Deepmind
- ![atari] Atari

:star: **Meta Learning Shared Hierarchies**
- [[arXiv](https://arxiv.org/abs/1710.09767)] [[blog](https://blog.openai.com/learning-a-hierarchy/)] Frans et al.; OpenAI, Berkeley.
- ![loco] Locomotion, Meta-Learning

**One-Shot Visual Imitation Learning via Meta-Learning**
- [[arXiv](https://arxiv.org/abs/1709.04905)] [[pdf](https://arxiv.org/pdf/1709.04905.pdf)] Finn et al.; UC Berkeley, OpenAI
- ![robot] Robot, Meta-Learning

:star: **Learning with Opponent-Learning Awareness** (LOLA)
- [[arXiv](https://arxiv.org/abs/1709.04326)] [[blog](https://blog.openai.com/learning-to-model-other-minds/)] Foerster et al.; OpenAI, Oxford, Berkeley, CMU
- MARL

:rocket: **Scalable trust-region method for deep reinforcement learning using Kronecker-factored approximation** (ACKTR, A2C)
- [[arXiv](https://arxiv.org/abs/1708.05144)] Wu et al.; University of Toronto, New York University
- ![atari] ![loco] Atari, Locomotion

**Neural Network Dynamics for Model-Based Deep Reinforcement Learning with Model-Free Fine-Tuning**
- [[arXiv](https://arxiv.org/abs/1708.02596)] [[blog](http://bair.berkeley.edu/blog/2017/11/30/model-based-rl/)] [[code](https://github.com/nagaban2/nn_dynamics)] Nagabandi et al.; Berkeley
- ![loco] Locomotion

:rocket: **Proximal Policy Optimization Algorithms** (PPO)
- [[arXiv](https://arxiv.org/abs/1707.06347)] [[blog](https://blog.openai.com/openai-baselines-ppo/)] Schulman et al.; OpenAI
- ![atari] ![loco] Atari, Locomotion

:rocket: **Learning Transferable Architectures for Scalable Image Recognition**
- [[arXiv](https://arxiv.org/abs/1707.07012)] Zoph et al.; Google Brain
- ![nn] NN

:star: **Hybrid Reward Architecture for Reinforcement Learning** (HRA)
- [[arXiv](https://arxiv.org/abs/1706.04208v1)] van Seijen et al.; Microsoft Maluuba, McGill University
- ![atari] Atari

**Parameter Space Noise for Exploration**
- [[arXiv](https://arxiv.org/abs/1706.01905)] Plappert et al.; OpenAI, Karlsruhe Institute of Technology
- ![atari] ![loco] Atari, Locomotion

:rocket: **Mastering the Game of Go without Human Knowledge** (AlphaGo Zero)
- [[pdf](https://deepmind.com/documents/119/agz_unformatted_nature.pdf)], [[blog](https://deepmind.com/blog/alphago-zero-learning-scratch/)]
- Silver et al.; Deepmind
- ![go] ![table] Go, Table, Planning

**Neural Optimizer Search with Reinforcement Learning**
- [[pdf](http://proceedings.mlr.press/v70/bello17a/bello17a.pdf)] Bello et al.; Google Brain
- ![nn] NN


**Asymmetric Actor Critic for Image-Based Robot Learning**
- [[arXiv](https://arxiv.org/abs/1710.06542)], [[official blog post](https://blog.openai.com/generalizing-from-simulation/)] Pinto et al.; OpenAI, CMU
- ![robot] Robot


**Sim-to-Real Transfer of Robotic Control with Dynamics Randomization**
- [[arXiv](https://arxiv.org/abs/1710.06537)], [[blog](https://blog.openai.com/generalizing-from-simulation/)] Peng et al.; OpenAI, Berkeley
- ![robot] Robot

**A Deep Reinforcement Learning Chatbot**
- [[arXiv](https://arxiv.org/abs/1709.02349)] Serban et al.; MILA

**Learning model-based planning from scratch**
- [[arXiv](https://arxiv.org/abs/1707.06170)], [[blog](https://deepmind.com/blog/agents-imagine-and-plan/)] Pascanu et al.; Google DeepMind
- ![loco] Locomotion

:star: **Imagination-Augmented Agents for Deep Reinforcement Learning** (I2As)
- [[arXiv](https://arxiv.org/abs/1707.06203)] [[blog](https://deepmind.com/blog/agents-imagine-and-plan/)] Weber et al.; DeepMind
- ![atari] Planning, Atari, Transfer


**Distral: Robust Multitask Reinforcement Learning**
- [[arXiv](https://arxiv.org/abs/1707.04175)] Teh et al.; DeepMind
- ![maze] Maze, Transfer


**Emergence of Locomotion Behaviours in Rich Environments**
- [[arXiv](https://arxiv.org/abs/1707.02286)] [[blog](https://deepmind.com/blog/producing-flexible-behaviours-simulated-environments/)] Heess et al.; DeepMind
- ![loco] Locomotion

**Programmable Agents**
- [[arXiv](https://arxiv.org/abs/1706.06383v1)] Denil et al.; DeepMind
- ![loco] Locomotion

:star: **Evolution Strategies as a Scalable Alternative to Reinforcement Learning**
- [[arXiv](https://arxiv.org/abs/1703.03864v1)] Salimans et al.; OpenAI
- ![atari] Atari

**Neural Episodic Control**
- [[arXiv](https://arxiv.org/abs/1703.01988v1)] Pritzel et al.; DeepMind
- ![atari] Atari


## Year 2016
**The Predictron: End-To-End Learning and Planning**
- [[arXiv](https://arxiv.org/abs/1612.08810v2)] Silver et al.; DeepMind
- ![maze] Model-based, Maze, Planning

**RL<sup>2</sup>: Fast Reinforcement Learning via Slow Reinforcement Learning**
- [[arXiv](https://arxiv.org/abs/1611.02779)] Duan et al.; Berkeley, OpenAI
- ![maze] Maze, Meta-Learning

**Neural Architecture Search with Reinforcement Learning**
- [[arXiv](https://arxiv.org/abs/1611.01578)] B. Zoph and Quoc V. Le; Google Brain; ICLR.
- ![nn] NN

**Reinforcement Learning with unsupervised auxiliary tasks** (UNREAL)
- [[arXiv](https://arxiv.org/abs/1611.05397)] Jaderberg et al.; Google DeepMind
- :pencil: [**Notes**](./notes/unreal-agent.md)
- ![atari] ![maze] ![loco] Atari, Maze, Locomotion, Continious

:rocket: **Learning to act by predicting the future** (VizDoom 2016 Full DM Winner)
- [[arXiv](https://arxiv.org/abs/1611.01779)] Dosovitskiy, Koltun; Intel Labs
- ![doom] ![maze] Doom, Maze, FPS

**Multiagent Bidirectionally-Coordinated Nets for Learning to Play StarCraft Combat Games**
- [[arXiv](https://arxiv.org/abs/1609.02993)] Peng et al.; Alibaba Group, University College London
- ![sc] Starcraft, MARL

**Playing FPS Games with Deep Reinforcement Learning** (VizDoom 2016 Limited DM 2nd place)
- [[arXiv](https://arxiv.org/abs/1609.05521)] Lample, Chaplot; Carnegie Mellon University
- ![doom] ![maze] Doom, Maze, FPS

[RTS:SC] **Episodic Exploration for Deep Deterministic Policies: An Application to StarCraft Micromanagement Tasks**
- [[arXiv](https://arxiv.org/abs/1609.02993)] Usunier et al.; Facebook AI Research
- ![sc] Starcraft

:rocket: **Asynchronous Methods for Deep Reinforcement Learning** (A3C)
- [[arXiv](https://arxiv.org/abs/1602.01783v2)] Mnih et al.; DeepMind
- :pencil: [**Notes**](./notes/a3c-agent.md)
- ![atari] ![maze] ![loco] Atari, Maze, Locomotion, Continious

## Year 2015

:star: **Dueling Network Architectures for Deep Reinforcement Learning** (Dueling DQN)
- [[arXiv](https://arxiv.org/abs/1511.06581)] Wang et al.; DeepMind
- ![atari] Atari

**Prioritized Experience Replay**
- [[arXiv](https://arxiv.org/abs/1511.05952v4)] Schaul et al.; DeepMind
- :pencil: [**Notes**](./notes/prioritized-exp-replay.md)
- ![atari] Atari

:star: **Deep Reinforcement Learning with Double Q-learning** (Double DQN)
- [[arXiv](https://arxiv.org/abs/1509.06461)] Hasselt et al.; DeepMind
- ![atari] Atari

**High-dimensional continuous control using generalized advantage estimation**
- [[arXiv](https://arxiv.org/abs/1506.02438)] Schulman et al.; Berkeley
- ![loco] Locomotion

:star: **Trust Region Policy Optimization** (TRPO)
- [[arXiv](https://arxiv.org/abs/1502.05477)] Schulman et al.; UC Berkeley
- ![atari] ![maze] ![loco] Atari, Maze, Locomotion

:rocket: **Human-level control through deep reinforcement learning** (DQN)

- [[Nature](http://www.nature.com/nature/journal/v518/n7540/full/nature14236.html)] [[pdf](hhttp://www.readcube.com/articles/10.1038/nature14236?shared_access_token=Lo_2hFdW4MuqEcF3CVBZm9RgN0jAjWel9jnR3ZoTv0P5kedCCNjz3FJ2FhQCgXkApOr3ZSsJAldp-tw3IWgTseRnLpAc9xQq-vTA2Z5Ji9lg16_WvCy4SaOgpK5XXA6ecqo8d8J7l4EJsdjwai53GqKt-7JuioG0r3iV67MQIro74l6IxvmcVNKBgOwiMGi8U0izJStLpmQp6Vmi_8Lw_A%3D%3D)] Mnih et al.; Google Deepmind
- :pencil: [**Notes**](./notes/dqn-agent.md)
- ![atari] Atari

**Mastering the game of Go with deep neural networks and tree search** (AlphaGo Master)

- [[Nature](https://www.nature.com/nature/journal/v529/n7587/full/nature16961.html)], [[reddit](https://www.reddit.com/r/MachineLearning/comments/42ytdx/pdf_mastering_the_game_of_go_with_deep_neural/)] Silver et al.; Deepmind, Google
- ![go] ![table] Go, Table

## Year 2013

:rocket: **Playing Atari with Deep Reinforcement Learning** (DQN)
- [[arXiv](https://arxiv.org/abs/1312.5602)] Mnih et al.; DeepMind Technologies
- ![atari] Atari

**Evolving Large-Scale Neural Networks for Vision-Based Reinforcement Learning**
- [[pdf](http://people.idsia.ch/~juergen/gecco2013torcs.pdf)] Koutnik et al.; IDSIA, USI-SUPSI

## 2012 and earlier

**Horde: A Scalable Real-time Architecture for Learning Knowledge from Unsupervised Sensorimotor Interaction**

- [[pdf](https://www.cs.swarthmore.edu/~meeden/DevelopmentalRobotics/horde1.pdf)]
- Sutton et al. (2011);  University of Alberta, McGill University
- ![robot] ![loco] Robot, Locomotion

:star: **Policy Gradient Reinforcement Learning for Fast Quadrupedal Locomotion**

- [[pdf](http://www.cs.utexas.edu/~ai-lab/pubs/icra04.pdf)]
- Kohl and Stone (2004); The University of Texas at Austin
- ![robot] ![loco] Robot, Locomotion

:star: **Autonomous helicopter flight via reinforcement learning**

- [[pdf](https://people.eecs.berkeley.edu/~jordan/papers/ng-etal03.pdf)]
- Ng et al. (2004); Stanford, Berkeley
- ![robot] Robot

:star: **Actor-Critic Algorithms**

- [[pdf](https://papers.nips.cc/paper/1786-actor-critic-algorithms.pdf)]
- Konda and Tsitsiklis (2003)

:star: **Temporal Difference Learning and TD-Gammon**

- [[pdf](http://cling.csd.uwo.ca/cs346a/extra/tdgammon.pdf)]
- Gerald Tesauro (1995)
- ![table] Table

:star: **Simple Statistical Gradient-Following Algorithms for Connectionist Reinforcement Learning** (REINFORCE)

- [[pdf](http://www-anw.cs.umass.edu/~barto/courses/cs687/williams92simple.pdf)]
- Ronald J. Williams (1992); Northeastern University

## Surveys
**A Brief Survey of Deep Reinforcement Learning**
  - [[arXiv](https://arxiv.org/abs/1708.05866)] Arulkumaran et al (2017).

## Books
:star: **Reinforcement Learning: An Introduction** (Complete Draft)
- [[pdf](http://incompleteideas.net/book/bookdraft2018jan1.pdf)] Richard S. Sutton and Andrew G. Barto (2018)

## Miscellaneous

**How to Read a Paper**

- [[pdf](http://ccr.sigcomm.org/online/files/p83-keshavA.pdf)]
- S. Keshav (2007); University of Waterloo
