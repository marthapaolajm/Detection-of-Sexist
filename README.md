# Detection of Sexist Tweets - ChatGPT Prompts

This repository contains the prompt used to generate explanations for why tweets were labeled as **sexist** (1) or **non-sexist** (0) using **GPT-4o (version 2024-08-01)**. The goal is to enhance the transparency and interpretability of our classification model by providing clear explanations for its decisions.

## Overview

The prompt is designed to guide GPT-4o in generating detailed explanations for tweets classified as sexist or non-sexist. Given that the tweets we are analyzing are in **Spanish**, the prompt is written in **Spanish** as well. However, for practical purposes, the prompt has also been translated into **English** in this repository.


# Detection of Sexist Tweets - ChatGPT Prompts

This repository contains the resources and methodology used to generate explanations for why tweets were labeled as **sexist** (1) or **non-sexist** (0) using **GPT-4o (version 2024-08-01)**. Our goal is to enhance the transparency and interpretability of the classification model by providing clear explanations for its decisions.

## Overview

This repository includes:
- The prompt used to generate detailed explanations with ChatGPT-4o.
- Methodology used in our paper.

## Methodology

This section outlines the full methodology used in our paper, from data acquisition to generating explanations with ChatGPT.

### 1. Accessing the EXIST Dataset

The first step involves obtaining the **EXIST (EXtreme Identitification of Sexism)** dataset, which was used for tweet classification.

### 2. Preprocessing the Data

Once you have downloaded the dataset, the following preprocessing steps are applied:
- **Cleaning**: Remove noise such as special characters, emojis, and links.
- **Labeling**: Ensure each tweet is correctly labeled as "sexist" (1) or "non-sexist" (0) as per the dataset.

### 3. Generating Explanations with GPT-4o

We used **ChatGPT-4o** to generate explanations for each classified tweet. To replicate this step:
1. **Prompt Design**: The prompt structure is designed to guide ChatGPT to explain why each tweet is labeled in a certain way. Given that we worked with Spanish tweets, the prompt is also in Spanish but has been translated into English for this repository.

The prompt template is as follows (stored in the file **`Prompt ChatGPT`**)
