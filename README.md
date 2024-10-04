# minGRU4Rec

Implementation of minGRU4Rec, an efficient RNN-based sequential recommendation model that leverages [minGRU](https://arxiv.org/abs/2410.01201v1) as the core operator for user behavior modeling. minGRU4Rec demonstrates comparable performance to [Mamba4Rec](https://arxiv.org/abs/2403.03900).

minGRU4Rec adheres to the three gold principles for sequential recommendation highlighted in [RecBLR](https://arxiv.org/abs/2406.12580), offering:

- Strong recommendation performance
- Parallelizable efficient training
- Low-cost efficient inference


## Usage

### Requirements

- PyTorch 1.12+
- CUDA 11.6+
- RecBole: `pip install recbole`

### Run

```python run.py```

Please config the model, dataset, and hyperparameters in config.yaml before running.


## Citation

```bibtex
@inproceedings{Feng2024WereRA,
    title   = {Were RNNs All We Needed?},
    author  = {Leo Feng and Frederick Tung and Mohamed Osama Ahmed and Yoshua Bengio and Hossein Hajimirsadegh},
    year    = {2024},
    url     = {https://api.semanticscholar.org/CorpusID:273025630}
}
```

```bibtex
@article{liu2024mamba4rec,
      title={Mamba4Rec: Towards Efficient Sequential Recommendation with Selective State Space Models}, 
      author={Chengkai Liu and Jianghao Lin and Jianling Wang and Hanzhou Liu and James Caverlee},
      journal={arXiv preprint arXiv:2403.03900},
      year={2024}
}
```

```bibtex
@article{liu2024behavior,
  title={Behavior-Dependent Linear Recurrent Units for Efficient Sequential Recommendation},
  author={Liu, Chengkai and Lin, Jianghao and Liu, Hanzhou and Wang, Jianling and Caverlee, James},
  journal={arXiv preprint arXiv:2406.12580},
  year={2024}
}
```

## Acknowledgment

This project references [minGRU-pytorch](https://github.com/lucidrains/minGRU-pytorch) and [RecBole](https://github.com/RUCAIBox/RecBole). Thanks for their commitment to open source.
