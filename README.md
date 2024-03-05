# ASR Bangla: Exploring Advanced Speech Recognition for Bengali Language

## Overview

This repository is dedicated to advancing Automatic Speech Recognition (ASR) for the Bengali language, leveraging state-of-the-art machine learning models such as wav2vec 2.0, T5, ARPA, BERT, and BART. This project is part of an experiment to understand and improve ASR performance in processing and recognizing Bengali speech, aiming to create more accurate and efficient ASR systems for Bengali, the seventh most spoken language in the world.

## Dataset

The project utilizes a dataset provided by Bengali AI, accessible [here](https://bengali.ai/datasets/). This dataset is specifically designed for Bengali language speech recognition tasks and was used in the context of the BUET DLSprint 2022, organized by the Department of Computer Science and Engineering, Bangladesh University of Engineering and Technology (BUET).

## Models Explored

1. **wav2vec 2.0**: A self-supervised learning framework for speech recognition that learns powerful speech representations from unlabeled audio data.
2. **T5 (Text-to-Text Transfer Transformer)**: A model that frames all NLP tasks as a text-to-text problem, allowing it to perform multiple tasks without task-specific model architectures.
3. **ARPA**: A statistical language model format often used in speech recognition, named after the Advanced Research Projects Agency.
4. **BERT (Bidirectional Encoder Representations from Transformers)**: A transformer-based machine learning technique for natural language processing pre-training developed by Google.
5. **BART (Bidirectional and Auto-Regressive Transformers)**: A model that combines bidirectional conditioning with auto-regressive generation, suitable for both understanding and generation tasks.

## Live Demo 

live Demo [Huggingface](https://huggingface.co/mushrafi88/wav2vec2_xlsr_bn_lm)

## Objective

The main goal of this project is to explore and identify the most effective models and techniques for Bengali ASR. By experimenting with a variety of models, this project aims to tackle the challenges associated with speech recognition for Bengali, such as accent diversity, phonetic complexities, and lack of sufficient labeled data for training advanced models.

## Results and Future Work

The repository does not specify the results explicitly; however, it implies ongoing efforts to benchmark the performance of different models on the Bengali AI dataset. Future work may include refining models based on experimental outcomes, expanding the dataset with more diverse speech samples, and integrating these ASR models into applications to serve the Bengali-speaking community better.

## Contribution

Contributions to the project are welcome. Interested researchers and developers can contribute by experimenting with different model configurations, proposing improvements, or expanding the dataset. The project is open for collaboration to enhance the capabilities and reach of Bengali ASR systems.

## Acknowledgments

Special thanks to Bengali AI for providing the dataset and to BUET CSE for hosting the BUET DLSprint 2022, facilitating this exploration into Bengali ASR technologies.
