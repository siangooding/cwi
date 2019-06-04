# Complex Word Identification as a Sequence Labelling Task

This github contains the state-of-the-art complex word identification (CWI) models from Gooding and Kochmar (2019).

In order to run the CWI models, you will need to download the original sequence labeller from this repository: https://github.com/marekrei/sequence-labeler 

# Usage

Additional functions for the CWI models are available in complex_word.py. Please refer to the Example notebook for details on how to use the models. 

# Dataset

The dataset used to train these models was collected by Yimam et al., (2018) and is available [here]https://www.inf.uni-hamburg.de/en/inst/ab/lt/resources/data/complex-word-identification-dataset.html


# Citing
If you used our models, please kindly cite both our paper and the original sequence labelling paper:

```
@inproceedings{goodingkochmar,
  title={{Complex Word Identification as a Sequence Labelling Task}},
  author={Gooding, Sian and Kochmar, Ekaterina},
  booktitle={Proceedings of the 55th Annual Meeting of the Association for Computational Linguistics (Volume 1: Short Papers)},
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
