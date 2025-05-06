## env setup
```sh
# install conda
wget https://github.com/conda-forge/miniforge/releases/latest/download/Miniforge3-Linux-x86_64.sh
bash Miniforge3-Linux-*.sh
# init env
source ~/miniforge3/bin/activate
conda init
# setup dependency
conda create -n lunar_lander_youtube python=3.8
conda activate lunar_lander_youtube
pip install "pip<24.1"
pip install -r requirements.txt
```