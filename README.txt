To use this code:

Download Miniconda3
wget https://repo.anaconda.com/miniconda/Miniconda3-latest-Linux-x86_64.sh
bash Miniconda3-latest-Linux-x86_64.sh
cat -n "snake_game.py"

conda
source ~/miniconda3/etc/profile.d/conda.sh
conda create -n pygame_env python=3.7
conda activate pygame_env

pip install pygame
pip install torch torchvision
pip install matplotlib ipython

Enjoy!
