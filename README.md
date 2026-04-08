# `<User Identity Linkage across Social Media via Attentive Time-aware User Modeling>`

> `UserNet: An attentive time-aware framework for user identity linkage across social media, featuring temporal post correlation modeling and a newly released large-scale multimodal dataset.`

## Authors

**Xiaolin Chen**<sup>1</sup>, **Xuemeng Song**<sup>1</sup>\*, **Siwei Cui**<sup>2</sup>, **Tian Gan**<sup>1</sup>, **Zhiyong Cheng**<sup>3</sup>, **Liqiang Nie**<sup>1</sup>

<sup>1</sup> `<Shandong University>`  
<sup>2</sup> `<Texas A, and M University>`  
<sup>3</sup> `<Qilu University of Technology (ShandongAcademy of Sciences)>` 
\* Corresponding author

## Links

- **Paper**: [`Paper Link`](<https://ieeexplore.ieee.org/document/9246515>)
- **Testing Dataset**: [`Testing Dataset`](<https://drive.google.com/drive/folders/1ZPyST2mzwS_X6iegCkwUJm2T3tc5p-Yf?usp=sharing>)
- **Training Dataset&Feature**:[`Testing Dataset`](<https://pan.baidu.com/s/1gqv1HJ1hs4VW_qm6AQggsA>) (pwd: yw9f)

---

## Table of Contents

- [Updates](#updates)
- [Introduction](#introduction)
- [Method / Framework](#method--framework)
- [Project Structure](#project-structure)
- [Installation](#installation)
- [Dataset / Benchmark](#dataset--benchmark)
- [Usage](#usage)
- [Citation](#citation)
- [Acknowledgement](#acknowledgement)
---

## Updates

> - [07/2019] Initial release of the UserNet implementation.

---

## Introduction

We present **`<User Identity Linkage across Social Media via Attentive Time-aware User Modeling>`**, a framework for **`<User Identity Linkage>`**.  
Our method addresses **`<identifying accounts belonging to the same real-world entity across different social networks>`** by introducing **`<an attentive time-aware user modeling approach>`**.  
This repository provides the official implementation, and dataset.

---

## Method / Framework

### Framework Figure

```markdown
![Framework](framework.png)
```
**Figure 1.** Overall framework of UserNet.

---

## Project Structure

```text
.
├── Time-M2M-Thread.py     
├── README.md             
├── requirements.txt      
└── data/                 
```
---

## Installation

### 1. Clone the repository

```bash
git clone https://github.com/iLearn-Lab/UserIdentityLinkage-UserNet.git
cd UserIdentityLinkage-UserNet
```

### 2. Install dependencies
- Python 3.5.2
- Tensorflow 1.9.0
- Numpy 1.16.4

```bash
pip install numpy==1.16.4 tensorflow==1.9.0
```
---

## Dataset / Benchmark

- **Testing Dataset**: [`Testing Dataset`](<https://drive.google.com/drive/folders/1ZPyST2mzwS_X6iegCkwUJm2T3tc5p-Yf?usp=sharing>)
- **Training Dataset&Feature**:[`Testing Dataset`](<https://pan.baidu.com/s/1gqv1HJ1hs4VW_qm6AQggsA>) (pwd: yw9f)

## Usage

### Train and Evaluate

```bash
python Time-M2M-Thread.py
```

## Citation
```bibtex
@ARTICLE{9246515,
  author = {Chen, Xiaolin and Song, Xuemeng and Cui, Siwei and Gan, Tian and Cheng, Zhiyong and Nie, Liqiang},
  journal = {IEEE Transactions on Multimedia},
  title = {User Identity Linkage Across Social Media via Attentive Time-Aware User Modeling},
  year = {2021},
  volume = {23},
  pages = {3957-3967},
}
```
---

## Acknowledgement

- Thanks to our supervisor and collaborators for valuable support.
- Thanks to the open-source community for providing useful baselines and tools.
---

## License

This project is released under the Apache License 2.0.
