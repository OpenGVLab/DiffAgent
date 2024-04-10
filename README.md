# DiffAgent: Fast and Accurate Text-to-Image API Selection with Large Language Model


[![MIT license](https://img.shields.io/badge/License-MIT-blue.svg)](https://lbesson.mit-license.org/)  [![arXiv](https://img.shields.io/badge/arXiv-2404.01342-red)](https://arxiv.org/abs/2404.01342) 

## Abstract

<details><summary>CLICK for the full abstract</summary>

> Text-to-image (T2I) generative models have attracted significant attention and found extensive applications within and beyond academic research. For example, the Civitai community, a platform for T2I innovation, currently hosts an impressive array of 74,492 distinct models. However, this diversity presents a formidable challenge in selecting the most appropriate model and parameters, a process that typically requires numerous trials. Drawing inspiration from the tool usage research of large language models (LLMs), we introduce DiffAgent, an LLM agent designed to screen the accurate selection in seconds via API calls. DiffAgent leverages a novel two-stage training framework, SFTA, enabling it to accurately align T2I API responses with user input in accordance with human preferences. To train and evaluate DiffAgent's capabilities, we present DABench, a comprehensive dataset encompassing an extensive range of T2I APIs from the community. Our evaluations reveal that DiffAgent not only excels in identifying the appropriate T2I API but also underscores the effectiveness of the SFTA training framework.
> </details>

We are open to any suggestions and discussions and feel free to contact us through [liruizhao@stu.xmu.edu.cn](mailto:liruizhao@stu.xmu.edu.cn).


## TODO

- [ ] data collection script
- [ ] dataset
- [ ] pretrain model
- [ ] training code

## News

- 


## Contents

- [Install](#install)
- [Dataset](#dataset)
- [Usage](#usage)
- [Citation](#citation)

## Install

```
conda create -n diffagent python=3.9.17
conda activate diffagent
git clone https://github.com/OpenGVLab/DiffAgent.git
cd diffagent
pip install -r requirements.txt
```

## Dataset


## Usage


## Citation

If you use our work or our dataset in this repo, or find them helpful, please consider giving a citation.

```
@article{zhao2024diffagent,
  title={DiffAgent: Fast and Accurate Text-to-Image API Selection with Large Language Model},
  author={Zhao, Lirui and Yang, Yue and Zhang, Kaipeng and Shao, Wenqi and Zhang, Yuxin and Qiao, Yu and Luo, Ping and Ji, Rongrong},
  journal={arXiv preprint arXiv:2404.01342},
  year={2024}
}
```

