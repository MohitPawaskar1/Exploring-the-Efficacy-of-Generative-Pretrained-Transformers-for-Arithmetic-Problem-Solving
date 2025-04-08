# 🧠 Solve Maths using DeepSeek-Math-7B-instruct LLM

A comparative study investigating the capabilities of Large Language Models (LLMs) like ChatGPT, Cohere, Gemma, Zephyr, Meta-Llama, and **DeepSeekMath-7B-instruct** for arithmetic problem-solving and math word problems — without the use of calculators.

## 📌 Overview

This project explores how modern LLMs, initially built for natural language understanding, can be leveraged for mathematical reasoning. Through rigorous experimentation, we:
- Compared the arithmetic-solving capabilities of six popular LLMs.
- Developed a custom **API** for arithmetic computation using **DeepSeekMath-7B-instruct**.
- Evaluated models on tasks including arithmetic operations and math word problems.

## ✨ Highlights

- 📊 **Performance Benchmarking** of LLMs on math tasks.
- ⚙️ **Custom API** built on DeepSeekMath for solving arithmetic problems.
- 📚 Insights into strengths/limitations of various GPT-based models.
- 🚀 Applications in **education**, **AI research**, and **automated tutoring**.

## 🧪 Models Compared

| Model         | Arithmetic Accuracy |
|---------------|---------------------|
| DeepSeekMath  | **55%**             |
| ChatGPT       | 50%                 |
| Cohere        | 50%                 |
| Zephyr        | 37%                 |
| Meta-Llama    | 40%                 |
| Gemma         | 27%                 |

## 🛠️ Methodology

### 1. Arithmetic Tasks
We evaluated models on basic arithmetic using:
- 🧮 Integers
- 🔢 Decimals
- ⚖️ Fractions
- 💯 Percentages
- ➖ Negative numbers

Operations included:
- Addition, Subtraction, Multiplication, Division, Exponentiation, Mixed Computations

### 2. Math Word Problems
We tested models on their ability to:
- Understand contextual problem statements
- Apply appropriate mathematical logic
- Generate correct solutions

Metrics used:
- **Accuracy**
- **Precision**
- **Recall**
- **F1 Score**

## 🌐 API Integration

We built an API to interface with the **DeepSeekMath-7B-instruct** model to:
- Handle custom arithmetic expressions
- Return clean and accurate answers in real time

## 📈 Key Insights

- DeepSeekMath outperforms other models on arithmetic reasoning tasks.
- LLMs show varying ability in interpreting math word problems.
- There’s strong potential for LLMs to support **education** and **automated tutoring**.

## 📚 References

- [DeepSeek-Math GitHub](https://github.com/deepseek-ai/DeepSeek-Math)
- [ChatGPT by OpenAI](https://mkai.org/chatgpt-optimizing-language-models-for-dialogue/)
- [Gemma on Hugging Face](https://huggingface.co/google/gemma-2b-it)
- [Zephyr on Hugging Face](https://huggingface.co/HuggingFaceH4/zephyr-7b-alpha)
- [Meta-Llama](https://huggingface.co/meta-llama)
- [LLM Evaluation Metrics](https://www.linkedin.com/pulse/evaluating-large-language-models-llms-standard-set-metrics-biswas-ecjlc)

## 📌 Future Work

- Fine-tune LLMs specifically for math education
- Expand dataset to include symbolic mathematics
- Integrate the solution into educational platforms
