# AI-Powered-Paraphrasing-Tool
## Project Overview

This project develops an **AI-powered paraphrasing tool** using a pre-trained **T5 Transformer model** from Hugging Face.

The tool accepts a block of input text and generates multiple paraphrased versions while attempting to preserve the original meaning.

The generated outputs are evaluated using:

- Grammar checking
- Spelling checking
- Fluency scoring
- BLEU score

The project is implemented in Python using a Jupyter Notebook and uses console-based input and output.

---

## Objectives

The main objectives of this project are:

- Take a block of input text from the user.
- Generate multiple paraphrased versions of the input.
- Use a deep learning Transformer model for paraphrasing.
- Preserve the meaning of the original text.
- Check the generated text for grammar errors.
- Check the generated text for spelling errors.
- Calculate a fluency score.
- Evaluate the generated text using BLEU score.
- Display sample results and evaluation metrics.

---

## Technologies Used

### Programming Language

- Python

### Deep Learning / NLP

- Hugging Face Transformers
- T5 Transformer Model
- PyTorch

### NLP Libraries

- NLTK
- LanguageTool
- PySpellChecker

### Evaluation

- BLEU Score
- Grammar Error Count
- Spelling Error Count
- Fluency Score

### Development Environment

- Google Colab
- Jupyter Notebook

---

## Model Used

The project uses a pre-trained **T5 (Text-to-Text Transfer Transformer)** model from Hugging Face.

T5 treats different NLP tasks as text-to-text problems. For this project, the model is used to generate paraphrased versions of the input sentence.

The model is loaded using the Hugging Face Transformers library.

The general workflow is:

```text
Input Text
    ↓
T5 Transformer
    ↓
Multiple Paraphrased Outputs
    ↓
Grammar Checking
    ↓
Spelling Checking
    ↓
Fluency Scoring
    ↓
BLEU Evaluation
    ↓
Final Results
