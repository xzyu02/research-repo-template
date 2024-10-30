# Research Repository Template

Repo Description here

## Environment

Please use following commands to setup environment:

```sh
PIP_EXISTS_ACTION=w conda env create -f environment.yml
conda activate <env_name>
```

```sh
# web
pip install beautifulsoup4 fastapi flask selenium
# visualization
pip install geopandas plotly seaborn
# more ml
pip install tensorflow[and-cuda] scikit-video scikit-image xplique numba lightning
```

To install conda on your remote Linux server, please use the following commands:

```sh
mkdir -p ~/miniconda3
wget https://repo.anaconda.com/miniconda/Miniconda3-latest-Linux-x86_64.sh -O ~/miniconda3/miniconda.sh
bash ~/miniconda3/miniconda.sh -b -u -p ~/miniconda3
rm -rf ~/miniconda3/miniconda.sh
```

For local devices, please check the [official site](https://docs.anaconda.com/free/miniconda/).

## Run Experiments
```
sh main.sh
```

