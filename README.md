# Emotion Dataset

This is a dataset that can be used for emotion classification. It has already been preprocessed based on the approach described in our [paper](https://www.aclweb.org/anthology/D18-1404/). It is also stored as a pandas dataframe and ready to be used in an NLP pipeline.

Note that the version of the data provided here corresponds to a six emotions variant that's meant to be used for educational and research purposes. 

## Download 

Hugging Face: https://huggingface.co/datasets/emotion

Download link: https://www.dropbox.com/s/607ptdakxuh5i4s/merged_training.pkl

Papers with Code Public Leaderboad: https://paperswithcode.com/sota/text-classification-on-emotion

## Notebooks

Here is a [notebook](https://colab.research.google.com/drive/1nwCE6b9PXIKhv2hvbqf1oZKIGkXMTi1X#scrollTo=t23zHggkEpc-) showing how to use it for fine-tuning a pretrained language model for the task of emotion classification.

Here is another [notebook](https://colab.research.google.com/drive/176NSaYjc2eeI-78oLH_F9-YV3po3qQQO?usp=sharing) which shows how to fine-tune T5 model for emotion classification along with other tasks.

Here is also a hosted [fine-tuned model](https://huggingface.co/mrm8488/distilroberta-base-finetuned-sentiment) on HuggingFace which you can directly use for inference in your NLP pipeline. 

Feel free to reach out to me on [Twitter](https://twitter.com/omarsar0) for more questions about the dataset.

## Usage 

The dataset should be used for educational and research purposes only. If you use it, please cite:

```
@inproceedings{saravia-etal-2018-carer,
    title = "{CARER}: Contextualized Affect Representations for Emotion Recognition",
    author = "Saravia, Elvis  and
      Liu, Hsien-Chi Toby  and
      Huang, Yen-Hao  and
      Wu, Junlin  and
      Chen, Yi-Shin",
    booktitle = "Proceedings of the 2018 Conference on Empirical Methods in Natural Language Processing",
    month = oct # "-" # nov,
    year = "2018",
    address = "Brussels, Belgium",
    publisher = "Association for Computational Linguistics",
    url = "https://www.aclweb.org/anthology/D18-1404",
    doi = "10.18653/v1/D18-1404",
    pages = "3687--3697",
    abstract = "Emotions are expressed in nuanced ways, which varies by collective or individual experiences, knowledge, and beliefs. Therefore, to understand emotion, as conveyed through text, a robust mechanism capable of capturing and modeling different linguistic nuances and phenomena is needed. We propose a semi-supervised, graph-based algorithm to produce rich structural descriptors which serve as the building blocks for constructing contextualized affect representations from text. The pattern-based representations are further enriched with word embeddings and evaluated through several emotion recognition tasks. Our experimental results demonstrate that the proposed method outperforms state-of-the-art techniques on emotion recognition tasks.",
}
```

## Research Opportunities
We are expanding this dataset to include more languages. If you would like to know more about this research project, feel free to reach out to me on [Twitter](https://twitter.com/omarsar0).

