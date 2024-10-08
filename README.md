# Automatic Generation of Fashion Images using Prompting in Generative Machine Learning Models

This repository contains the code and data associated with the paper titled **"Automatic Generation of Fashion Images using Prompting in Generative Machine Learning Models"**.

## Abstract

The advent of artificial intelligence has contributed to a groundbreaking transformation of the fashion industry, redefining creativity and innovation in unprecedented ways. This work investigates methodologies for generating tailored fashion descriptions using two distinct Large Language Models and a Stable Diffusion model for fashion image creation. Emphasizing adaptability in AI-driven fashion creativity, we depart from traditional approaches and focus on prompting techniques, such as zero-shot and few-shot learning, as well as Chain-of-Thought (CoT), which results in a variety of colors and textures, enhancing the diversity of the outputs. Central to our methodology is Retrieval-Augmented Generation (RAG), enriching models with insights from fashion sources to ensure contemporary representations. Evaluation combines quantitative metrics such as CLIPscore with qualitative human judgment, highlighting strengths in creativity, coherence, and aesthetic appeal across diverse styles. Among the participants, RAG and few-shot learning techniques are preferred for their ability to produce more relevant and appealing fashion descriptions.

## Table of Contents

- [Introduction](#introduction)
- [Dataset](#dataset)
- [Evaluation](#evaluation)
- [Results](#results)
- [Contributing](#contributing)
- [Citation](#citation)

## Introduction

Fashion is a dynamic and influential industry that not only reflects cultural and societal trends but also drives economic growth on a global scale. The integration of artificial intelligence (AI) within the fashion industry has revolutionized various aspects, from design and manufacturing to marketing and retail. This paper seeks to develop an automated process for generating fashion images that align with a specified style, match a particular occasion, and suit an individual wearer.

## Dataset

The dataset used in this study, "fashion-style-instruct," includes style recommendations based on input triplets of body type, personal clothing style, and event context. The dataset is processed to focus on body types and occasions, creating final triplets for various types and occasions.

## Evaluation

The evaluation of generated images and descriptions includes both quantitative metrics such as CLIPscore for text-image alignment and qualitative human judgment surveys to assess visual appeal, relevance, creativity, and overall impression.

## Results

The results of our experiments show the effectiveness of different prompting techniques and the use of Retrieval-Augmented Generation (RAG) in producing relevant and appealing fashion descriptions. The human evaluation results and CLIPscore values indicate medium text-image alignment and validate the quality of our generated images. We present some qualitative results.

![myresults1](https://github.com/user-attachments/assets/92e1aa8f-2e13-4c6c-8acd-719af86bd3ff)


## Contributing

We welcome contributions from the community. If you find any issues or have suggestions for improvement, please feel free to open an issue or submit a pull request.

## Citation

If you use this code in your research, please cite our paper:

```
@misc{argyrou2024automaticgenerationfashionimages,
      title={Automatic Generation of Fashion Images using Prompting in Generative Machine Learning Models}, 
      author={Georgia Argyrou and Angeliki Dimitriou and Maria Lymperaiou and Giorgos Filandrianos and Giorgos Stamou},
      year={2024},
      eprint={2407.14944},
      archivePrefix={arXiv},
      primaryClass={cs.CV},
      url={https://arxiv.org/abs/2407.14944}, 
}

```
