<p align="center"><img src="cfilt-dark-vec.png" alt="Computation for Indian Language Technology Logo" width="150" height="150"/>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<img src="aisurrey.svg" alt="Computation for Indian Language Technology Logo" width="250"/></p>

# HiNER - Hindi Named Entity Recognition Dataset

[![GitHub issues](https://img.shields.io/github/issues/cfiltnlp/HiNER?style=flat-square)](https://github.com/cfiltnlp/HiNER/issues)
[![GitHub forks](https://img.shields.io/github/forks/cfiltnlp/HiNER?style=flat-square)](https://github.com/cfiltnlp/HiNER/network)
[![GitHub stars](https://img.shields.io/github/stars/cfiltnlp/HiNER?style=flat-square)](https://github.com/cfiltnlp/HiNER/stargazers)
[![GitHub license](https://img.shields.io/github/license/cfiltnlp/HiNER?style=flat-square)](https://github.com/cfiltnlp/HiNER/blob/main/LICENSE)
[![Twitter Follow](https://img.shields.io/twitter/follow/cfiltnlp?color=1DA1F2&logo=twitter&style=flat-square)](https://twitter.com/cfiltnlp)
[![Twitter Follow](https://img.shields.io/twitter/follow/PeopleCentredAI?color=1DA1F2&logo=twitter&style=flat-square)](https://twitter.com/PeopleCentredAI)

## About

This repository contains the Hindi Named Entity Recognition dataset (HiNER) published at the Langauge Resources and Evaluation conference (LREC) in 2022. 

### Recent Updates
* Version 0.0.5: HiNER initial release

## Usage

You should have the 'datasets' packages installed to be able to use the :rocket: HuggingFace datasets repository. Please use the following command and install via pip:

```code
    pip install datasets
```

To use the original dataset with all the tags, please use:<br/>

```python
    from datasets import load_dataset
    hiner = load_dataset('cfilt/HiNER-original')
```

To use the collapsed dataset with only PER, LOC, and ORG tags, please use:<br/>

```python
    from datasets import load_dataset
    hiner = load_dataset('cfilt/HiNER-collapsed')
```
However, the CoNLL format dataset files can also be found on this Git repository under the [data](data/) folder.

## Model(s)

Our best performing models are hosted on the HuggingFace models repository

| Dataset | XLM-R<sub>large</sub> | MuRIL<sub>base</sub> | Description |
| --- | --- | --- | --- |
| [`HiNER - Original`](https://huggingface.co/datasets/cfilt/HiNER-original) | [HiNER-Original-XLM-R-Large](https://huggingface.co/cfilt/HiNER-original-xlm-roberta-large) | [HiNER-Original-MuRIL-Base](https://huggingface.co/cfilt/HiNER-original-muril-base-cased) | Models obtained by fine-tuning on the XLM-R<sub>large</sub> multilingual language model |
| [`HiNER - Collapsed`](https://huggingface.co/datasets/cfilt/HiNER-collapsed) | [HiNER-Collapsed-XLM-R-Large](https://huggingface.co/cfilt/HiNER-collapsed-xlm-roberta-base) | [HiNER-Collapsed-MuRIL-Base](https://huggingface.co/cfilt/HiNER-collapsed-muril-base-cased) | Models obtained by fine-tuning on the MuRIL<sub>base</sub> multilingual language model |


## Maintainer(s)

[Diptesh Kanojia](https://dipteshkanojia.github.io)<br/>
[Rudra Murthy V](https://murthyrudra.github.io/)<br/>

## Citation

TBA

### BiBTeX Citation
```latex
TBA
```
