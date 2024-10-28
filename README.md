# formal-capacity

This repository is the official implementation of [hoge](https://arxiv.org/abs/2501.99999).


## Setup

```shell
conda env create -f environment.yml
conda activate timestep
```

## Experiments

### Regular Language

Download data from `data.zip`

```shell
python main.py --mode train --run_name testrun --dataset Parity --model_type SAN --gpu 0
```

### Context-Free Grammer



## Acknowledgement

- [Code for "On the Ability and Limitations of Transformers to Recognize Formal Languages"](https://github.com/satwik77/Transformer-Formal-Languages)
- hoge