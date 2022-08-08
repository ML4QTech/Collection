# Artificial Intelligence and Machine Learning For Quantum Technologies
### **[Mario Krenn](https://mpl.mpg.de/research-at-mpl/independent-research-groups/krenn-research-group/), Jonas Landgraf, Thomas Foesel, [Florian Marquardt](https://mpl.mpg.de/divisions/marquardt-division)**

#### contact: ML4qtech@mpl.mpg.de

<p align="center">
   <img src="https://github.com/ML4QTech/Collection/blob/main/overview.png" alt="Overview" width="999px">
</p>

## Basics of Artificial Intelligence and Machine Learning

### General resources
- [Basics of Neural Networks](https://www.dkriesel.com/en/science/neural_networks): Lightweight introduction to machine learning and neural networks
- [Neural Networks and Deep Learning](http://neuralnetworksanddeeplearning.com): Basic, compact and intuitive introduction to neural networks, supervised learning and the backpropagation algorithm
- [Deep Learning](https://www.deeplearningbook.org/): A detailed introduction to the field of machine learning
- [Dive into Deep Learning](https://d2l.ai/): An interactive deep learning book with code, math, and discussions
- Hands-On Machine Learning with Scikit-Learn, Keras, and TensorFlow
- [Reinforcement Learning: An Introduction](http://incompleteideas.net/book/the-book.html): A detailed introduction to reinforcement learning

### Resources for STEM students
- [Machine Learning for Scientists](https://ml-lectures.org): see also [arXiv:2102.04883](https://arxiv.org/abs/2102.04883)
- [A high-bias, low-variance introduction to Machine Learning for physicists](https://arxiv.org/abs/1803.08823)
- Machine Learning for Physicists lecture by Florian Marquardt: [basic](https://machine-learning-for-physicists.org/) and [advanced lectures](https://pad.gwdg.de/2021_AdvancedMachineLearningForScience)

### Machine Learning Libraries

- [Tensorflow](https://www.tensorflow.org/)
- [Pytorch](https://pytorch.org/)
- [Jax](https://github.com/google/jax)
- [Stable Baselines](https://stable-baselines.readthedocs.io)
and many more

## AI for Quantum Technology

Here we collect repositories that demonstrate works on AI in quantum technology. If you have additonal suggestions, please make a PR or send to [ML4QTech@mpl.mpg.de](ML4QTech@mpl.mpg.de)

### 1) Measurement data analysis and quantum state representation
#### Interpreting Measurements

- [**Unsupervised Phase Discovery with Deep Anomaly Detection**](https://github.com/Qottmann/phase-discovery-anomaly-detection) by Kottmann, Huembeli, Lewenstein, Acín ([paper](https://journals.aps.org/prl/abstract/10.1103/PhysRevLett.125.170603))

#### Approximating Quantum Dynamics
- [**Learning quantum dynamics with latent neural ordinary differential equations**](https://github.com/aspuru-guzik-group/QNODE) by Choi, Flam-Spepherd, Kyaw, Aspuru-Guzik ([paper](https://journals.aps.org/pra/abstract/10.1103/PhysRevA.105.042403))

### 2) Parameter estimation: learning the properties of a quantum system
#### Quantum Metrology
- [**Generalizable control for quantum parameter estimation through reinforcement learning**](https://github.com/MilCOS/Quantum_Parameter_Estimation_with_RL) by Xu, Li, Liu, Wang, Yuan, Wang  ([paper](https://www.nature.com/articles/s41534-019-0198-z))
#### Device calibration
- [**Efficiently measuring a quantum device using machine learning**](https://github.com/returnddd/CVAE_for_QE) by Lennon, Moon, Camenzind, Yu, Zumbühl, Briggs, Osborne, Laird, Ares ([paper](https://www.nature.com/articles/s41534-019-0193-4))

#### Quantum Hamiltonian Learning
- [**Learning models of quantum systems from experiments**](https://github.com/flynnbr11/QMLA) by Gentile, Flynn, Knauer, Wiebe, Paesani, Granade, Rarity, Santagati, Laing ([paper](https://www.nature.com/articles/s41567-021-01201-7))

### 3) Discovering strategies for hardware-level quantum control

#### Quantum control tasks without feedback (open-loop control)
- [**Reinforcement Learning in Different Phases of Quantum Control**](https://github.com/mgbukov/dynamicQL/tree/master/SA) by Bukov, Day, Sels, Weinberg, Polkovnikov, Mehta ([paper](https://doi.org/https://doi.org/10.1103/PhysRevX.8.031086))

#### Quantum feedback control (closed-loop control)
- [**Deep Reinforcement Learning Control of Quantum Cartpoles**](https://github.com/Z-T-WANG/DeepReinforcementLearningControlOfQuantumCartpoles) by Wang, Ashida, Ueda ([paper](https://journals.aps.org/prl/abstract/10.1103/PhysRevLett.125.100401))
- [**Model-Free Quantum Control with Reinforcement Learning**](https://github.com/v-sivak/quantum-control-rl) by Sivak, Eickbusch, Royer, Tsioutsios, Devoret ([paper](https://doi.org/10.1103/PhysRevX.12.011059))

#### Model-free vs model-based RL
- [**Speedup for quantum optimal control from automatic differentiation based on graphics processing units**](https://github.com/SchusterLab/quantum-optimal-control) by Leung, Abdelhafez, Koch, Schuster ([paper](https://doi.org/10.1103/PhysRevA.95.042318))
- [**A differentiable programming method for quantum control**](https://github.com/frankschae/A-differentiable-programming-method-for-quantum-control) by Schäfer, Kloc, Bruder, Lörch ([paper](https://doi.org/10.1088/2632-2153/ab9802))
- [**Protocol Discovery for the Quantum Control of Majoranas by Differentiable Programming and Natural Evolution Strategies**](https://github.com/LuukCoopmans/Majorana-Game) by Coopmans, Luo, Kells, Clark, Carrasquilla ([paper](https://doi.org/10.1103/PRXQuantum.2.020332))
- [**Control of stochastic quantum dynamics by differentiable programming**](https://github.com/frankschae/Control-of-Stochastic-Quantum-Dynamics-with-Differentiable-Programming) by Schäfer, Sekatski, Koppenhöfer, Bruder, Kloc ([paper](https://doi.org/10.1088/2632-2153/abec22))


### 4) Discovering quantum experiments, protocols, and circuits

#### Discovery of Quantum Experiments
- [**Automated Search for new Quantum Experiments**](https://github.com/XuemeiGu/MelvinPython) by Krenn, Malik, Fickler, Lapkiewicz, Zeilinger, implemented by Gu ([paper](https://journals.aps.org/prl/abstract/10.1103/PhysRevLett.116.090405))
- [**Conceptual Understanding through Efficient Automated Design of Quantum Optical Experiments**](https://github.com/aspuru-guzik-group/Theseus) by Krenn, Kottmann, Tischler, Aspuru-Guzik ([paper](https://journals.aps.org/prx/abstract/10.1103/PhysRevX.11.031044))
- [**Designing quantum experiments with a genetic algorithm**](https://github.com/paulk444/AdaQuantum) by Nichols, Mineh, Rubio, Matthews, Knott ([paper](https://iopscience.iop.org/article/10.1088/2058-9565/ab4d89))
- [**Automated design of superconducting circuits and its application to 4-local couplers**](https://github.com/aspuru-guzik-group/scilla) by Menke, Häse, Gustavsson, Kerman, Oliver, Aspuru-Guzik ([paper](https://www.nature.com/articles/s41534-021-00382-6))

#### Discovering Quantum Protocols and Discrete Feedback Strategies
- [**Machine Learning for Long-Distance Quantum Communication**](https://github.com/qic-ibk/ps_quantum_comm) by Wallnöfer, Melnikov, Dür, Briegel ([paper](https://journals.aps.org/prxquantum/abstract/10.1103/PRXQuantum.1.010301))

#### Quantum Circuits
- [**Quantum computer-aided design of quantum optics hardware**](https://github.com/kottmanj/Photonic) by Kottmann, Krenn, Kyaw, Alperin-Lea, Aspuru-Guzik ([paper](https://iopscience.iop.org/article/10.1088/2058-9565/abfc94/meta))


### 5) Quantum Error Correction
- [**Automated Discovery of Autonomous Quantum Error Correction Schemes**](https://github.com/stanfordLINQS/SQcircuit/) by Rajabzadeh, Wang, Lee, Makihara, Guo, Safavi-Naeini ([paper](https://journals.aps.org/prxquantum/abstract/10.1103/PRXQuantum.3.020302))
