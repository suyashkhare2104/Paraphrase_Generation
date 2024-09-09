# Custom Paraphrase Generator (CPG)

This project implements a **Custom Paraphrase Generator (CPG)** using the **T5 model** for generating paraphrases of text passages. The model is fine-tuned on the **Quora Question Pairs dataset** and evaluated using industry-standard metrics such as **BLEU**, **ROUGE**, and **METEOR**. The application generates paraphrases for passages of 200-400 words and ensures that the paraphrased output is at least 80% of the input text length.

## Features

- **Custom Paraphrase Generator**: Fine-tuned T5 model to generate paraphrases.
- **Length Constraints**: Ensures the paraphrased text meets at least 80% of the input length.
- **Comparison**: Can be compared with LLM-based generators like GPT for performance and quality.
- **Evaluation**: Provides evaluation of paraphrased text using BLEU, ROUGE, and METEOR metrics.

## Installation

To get started, clone the repository and install the required dependencies:

```bash
git clone https://github.com/suyashkhare2104/Paraphrase_Generation.git
cd custom-paraphrase-generator
pip install -r requirements.txt
```
