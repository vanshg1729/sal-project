# GOPT: Transformer-Based Multi-Aspect Multi-Granularity Non-Native English Speaker Pronunciation Assessment

## Data
The SpeechOcean762 dataset used in ths paper is an open dataset licenced with CC BY 4.0. It can be downloaded from [this link](https://www.openslr.org/101).

## Prepare the environment
Clone or download this repository and set it as the working directory, create a virtual environment and install the dependencies.

```
# use absolute path of this repo
gopt_path=your_gopt_path
cd $gopt_path
python3 -m venv venv-gopt
source venv-gopt/bin/activate
pip install -r requirements.txt 
```

## Run Training and Evaluation
The model can be trained using ``gopt/src/traintest.py``, which then calls ``gopt/src/models/gopt.py``.
```sh
cd src
python traintest.py
```