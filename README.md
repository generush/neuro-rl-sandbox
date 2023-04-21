# neuro-rl-sandbox

conda activate -n neuro-rl python=3.8.16

Install isaacgym (https://developer.nvidia.com/isaac-gym/download)
cd isaacgym/python pip install -e .

Install IsaacGymEnv
git clone https://github.com/NVIDIA-Omniverse/IsaacGymEnvs cd IsaacGymEnvs pip install -e .

Downgrade numpy
pip install "numpy<1.24"

Random:

This is helpful: https://dev.to/milu_franz/git-explained-an-umbrella-structure-using-git-submodules-20dl

This is a bit more advanced: https://gist.github.com/gitaarik/8735255
