# Multi-Channel Sign Language Processing


## System Design
![proposal.png](docs%2Fproposal.png)

## Install
1. Clone this repository and navigate to mcslp folder.
```angular2html
git clone https://github.com/Zhou-Hangyu/mcslp.git
cd mcslp
```
2. Install Package.
```angular2html
conda create -n mcslp python=3.10 -y
conda activate mcslp
pip install --upgrade pip
pip install -e .
```

## Dataset Preparation
- `how2sign`: Use the .sh file [here](https://github.com/how2sign/how2sign-data) to download.
- `phoenix14t`: `wget https://www-i6.informatik.rwth-aachen.de/~koller/RWTH-PHOENIX-2014-T/`
