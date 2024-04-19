# Recipe Generation with GPT-2

This project uses the GPT-2 model to generate cooking recipes automatically. Leveraging a dataset from Hugging Face's datasets library, specifically "darkraipro/recipe-instructions", this notebook explores the ability of the GPT-2 model to understand and produce detailed recipe instructions.

## Project Overview

The objective of this project is to showcase the power of language models like GPT-2 in generating coherent and creative cooking recipes. By fine-tuning GPT-2 on a targeted dataset containing structured culinary instructions, we delve into the intersection of AI and culinary arts.

## Dataset

The dataset employed is the "recipe-instructions" from Hugging Face, curated by [darkraipro](https://huggingface.co/datasets/darkraipro/recipe-instructions). It consists of detailed cooking recipes, providing a rich source of culinary vocabulary and structured instructions.

## Model

The model utilized is GPT-2, a renowned text generation model developed by OpenAI. For more details about GPT-2, visit its [official model page on Hugging Face](https://huggingface.co/gpt2).

## Requirements

To execute the Jupyter notebook in this repository, ensure you have Python 3 and the following packages installed:

- jupyter
- transformers
- datasets

You can install these packages using pip with the following command:

```bash
pip install jupyter transformers datasets
```

## Usage
To view and run the notebook:

1. Clone this repository to your local machine.
2. Navigate to the cloned directory.
3. Start the Jupyter Notebook server:
```bash
jupyter notebook
```
4. Open gen-ai-fine-tuning-llms.ipynb in the Jupyter interface that opens in your browser.

## Contributing
Contributions to this project are welcome! To contribute, please fork the repository, make your changes, and submit a pull request.


## Acknowledgments
* Thanks to **darkraipro** for creating and sharing the "recipe-instructions" dataset.
* Thanks to **OpenAI** for developing the GPT-2 model.
