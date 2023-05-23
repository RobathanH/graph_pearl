# Important Note:
This repo is deprecated, all project development occurred in https://github.com/RobathanH/modular_pearl, which was forked from the original PEARL repo.



# graph_pearl
Augmenting the PEARL Meta-Reinforcement-Learning algorithm with discrete graph-structured task encodings based on the BOUNCEGRAD meta-learning algorithm.








### Setup Instructions (Windows)
(TODO: Convert to linux instructions)
1. Submodule init: git submodule update --init --recursive
2. Download and install mujoco210: https://github.com/deepmind/mujoco/releases, and add it to PATH
3. Setup Env:
conda create -n graph_pearl python=3.9 -y
conda activate graph_pearl
conda install pytorch torchvision torchaudio pytorch-cuda=11.7 -c pytorch -c nvidia -y
pip install gymnasium[all]
pip install mujoco_py
pip install click gtimer joblib
pip install torch-scatter torch-sparse torch-cluster torch-spline-conv torch-geometric -f https://data.pyg.org/whl/torch-1.13.0+cu117.html
pip install ipykernel ipywidgets networkx
