# Fine-Tuning PHI-2 on Instruction Tuned Dataset

Welcome to the `fine-tunning-phi2` repository! This project focuses on fine-tuning the Microsoft PHI-2 model using an instruction-tuned dataset from Tim Dettmer's OpenAssistant-Guanaco. The main script for this process is encapsulated in the Jupyter notebook `fine_tuning_phi2_on_instruction_tunened_dataset.ipynb`.

## Table of Contents

- [Overview](#overview)
- [Requirements](#requirements)
- [Installation](#installation)
- [Usage](#usage)
- [Dataset](#dataset)
- [Model](#model)
- [Results](#results)
- [Contributing](#contributing)
- [License](#license)

## Overview

Fine-tuning large language models on instruction-tuned datasets can significantly enhance their performance on specific tasks. This repository demonstrates how to fine-tune the Microsoft PHI-2 model using the OpenAssistant-Guanaco dataset.

## Requirements

To run the fine-tuning process, you need the following dependencies:

- Python 3.8+
- Jupyter Notebook
- PyTorch
- Transformers (Hugging Face)
- Datasets (Hugging Face)
- CUDA (for GPU support)

## Installation

Clone the repository and install the required packages:
    ```bash
    git clone https://github.com/imanoop7/fine-tunning-phi2.git
    cd fine-tunning-phi2
    pip install -r requirements.txt

## Usage
Open the Jupyter notebook and follow the steps to fine-tune the PHI-2 model:

- Start Jupyter Notebook:
    ```bash
    jupyter notebook

- Open fine_tuning_phi2_on_instruction_tunened_dataset.ipynb in your browser.

- Follow the instructions within the notebook to load the dataset, configure  
  the model, and initiate the fine-tuning process.

## Dataset
The dataset used for fine-tuning is timdettmers/openassistant-guanaco, an instruction-tuned dataset that facilitates enhanced performance on instruction-following tasks. More details about the dataset can be found here.

## Model
The model used in this project is the Microsoft PHI-2, a powerful language model designed for various NLP tasks. More information about the PHI-2 model can be found on the official page.

## Results
After fine-tuning, the performance of the PHI-2 model can be evaluated on different benchmarks to assess improvements. Detailed results and evaluation metrics will be included in future updates to this repository.

## Contributing
Contributions are welcome! Please open an issue or submit a pull request for any improvements, bug fixes, or suggestions.

## License
This project is licensed under the MIT License. See the LICENSE file for details.

Happy fine-tuning! If you have any questions or need further assistance, feel free to open an issue.


