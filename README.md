# noscope

# Installation

## Requirements
- python
The project is a python 2.7 project (not 3 compatible yet) and it is probably easist to setup with an Anaconda distribution. 
- ffmpeg 
The ffmpeg utility is required for some of the scripts which convert video
- Python / PIP
The python requirements are listed in the requirements.txt file. The most complicated package is opencv3 which requires a number of compilation steps to install on most platforms, if using Anaconda there are prepackaged versions which make setup much easier.

## Steps

```bash
git clone https://github.com/stanford-futuredata/noscope.git
cd noscope
python setup.py install
```

# Usage

There are a number of scripts in the ```exp/``` and ```scripts/``` directory which can be used to start training and using models on various datasets.
