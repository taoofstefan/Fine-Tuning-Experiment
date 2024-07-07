# README

## Overview

Welcome to the repository for my Master's thesis: **"Enhancing Function-Calling Precision in LLMs: A Comparative Analysis"**. This repository contains all the experimental results, the code used to test both baseline and fine-tuned models, and the scripts for fine-tuning Llama 2 7B and Mistral Instruct 7B.

## Table of Contents

- [Introduction](#introduction)
- [Structure](#structure)
- [Results](#results)
- [Contributing](#contributing)
- [License](#license)
- [Acknowledgements](#acknowledgements)

## Introduction

This repository accompanies my thesis, which investigates the function-calling capabilities of Large Language Models (LLMs). The primary focus is on enhancing the precision of these capabilities through focused fine-tuning. The models explored include Llama 2 7B and Mistral Instruct 7B, with comparative analysis against GPT-3.5 and GPT-4 series models.

## Structure

The repository is structured as follows:

```
.
├── Code
│   ├── Fine tuning and testing
│   │   ├── Fine tune-llama-2_S.ipynb
│   │   └── Fine tune mistral instruct_S.ipynb
│   ├── base model testing
│   │   ├── Llama 2.ipynb
│   │   ├── Mistral 7B.ipynb
│   │   └── OpenAI.ipynb
│   ├── Evaluation
│   │   ├── Statistical Evaluation.ipynb
│   │   └── Visuals.ipynb
├── results
│   ├── base evaluation
│   │   ├── result_llama2_chat_completion_format.xlsx
│   │   ├── result_mistral_chat_completion_format.xlsx
│   │   ├── result_openai_gpt-3.5-turbo-0125.xlsx
│   │   ├── result_openai_gpt-4-turbo-2024-04-09.xlsx
│   │   └── result_openai_gpt-4o-2024-05-13.xlsx
│   ├── fine tuned evaluation
│   │   ├── result_mt-ft-llama2-s.xlsx
│   │   └── result_mt-ft-mistral-instruct-s.xlsx
│   ├── data_evaluation_overview_tables.xlsx
└── README.md
```

- **Code/Fine tuning and testing**: Contains scripts for fine-tuning and direct testing of Llama 2 7B and Mistral Instruct 7B.
- **Code/base model testing**: Includes scripts for testing both baseline models.
- **Code/Evaluation**: Includes scripts used for visuals and statistical evaluation of the data.
- **results/base evaluation**: Stores the results of the experiments for both baseline models, along with the evaluation metric calculations.
- **reslts/fin tuned evaluation**: Stores the results of the experiments for the fine tuned models, along with the evaluation metric calculations.
- **results/data_evaluation_overview_tables.xlsx**: Is a table aggregating the results in table form


## Results

The results of the experiments are stored in the `results` directory. This includes XLSX files with detailed performance metrics for both baseline and fine-tuned models.

## Contributing

Contributions are welcome! Please fork this repository and submit a pull request with your improvements or suggestions. Ensure that your code adheres to the repository's coding standards and includes appropriate documentation.

## Acknowledgements

I would like to thank Brev.dev for their financial support, which made the fine-tuning of Llama 2 and Mistral Instruct possible. Special thanks to Anish and Ishan for their prompt assistance. Additionally, I am grateful to my professor for the invaluable guidance and feedback throughout this research project.

Thank you for your interest in this project. If you have any questions or feedback, please feel free to contact me.
