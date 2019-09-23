# Complex Word Identification as a Sequence Labelling Task

This directory contains the state-of-the-art complex word identification (CWI) model from [Gooding and Kochmar (2019)](https://www.aclweb.org/anthology/P19-1109).

# Usage

Additional functions for the CWI models are available in [complex_labeller.py](./sequence-labeler-master/complex_labeller.py). Please refer to the [example notebook](example.ipynb) for details on how to use the models. The  original code for the sequence labeller used in this project can be found at https://github.com/marekrei/sequence-labeler.

# Dataset

The dataset used to train these models was collected by Yimam et al., (2018) and is available [here](https://www.inf.uni-hamburg.de/en/inst/ab/lt/resources/data/complex-word-identification-dataset.html).


# Citing
If you used our models, please kindly cite both our paper and the original sequence labelling paper:

```
@inproceedings{goodingkochmar,
  title={{Complex Word Identification as a Sequence Labelling Task}},
  author={Gooding, Sian and Kochmar, Ekaterina},
  booktitle={Proceedings of the 57th Annual Meeting of the Association for Computational Linguistics (Volume 1: Short Papers)},
  pages={},
  year={2019}
}


@inproceedings{rei2017semi,
  title={{Semi-supervised multitask learning for sequence labeling}},
  author={Rei, Marek},
  booktitle={Proceedings of the 55th Annual Meeting of the Association for Computational Linguistics (Volume 1: Long Papers)},
  pages={2121--2130},
  year={2017}
}

```
