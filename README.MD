# RLHF Enhancing LLMs

This repository contains examples and explanations for collecting human feedback with Amazon SageMaker Ground Truth and fine-tuning Large Language Models (LLMs) using Reinforcement Learning from Human Feedback (RLHF). The project aims to showcase the effectiveness of RLHF in aligning LLM behavior with human expectations.

## Table of Contents

- [Overview](#overview)
- [Repository Structure](#repository-structure)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Overview

Reinforcement Learning from Human Feedback (RLHF) is a key technique for improving the alignment of LLMs with human expectations. This project demonstrates the application of RLHF to detoxify and fine-tune pre-trained models, making them more responsive to human preferences.

The notebooks provided in this repository walk through the following:
1. **Collect Human Feedback**: How to collect human feedback with Amazon SageMaker Ground Truth.
2. **Fine-tuning LLMs with RLHF**: How to use RLHF to fine-tune a pre-trained LLM.

## Repository Structure

- **`FINETUNED_MODEL/`**: Directory containing the fine-tuned model checkpoints and outputs.
- **`Amazon_SageMaker_Ground_Truth_for_Human_Feedback_Labeling.ipynb`**: A notebook showcasing the process of labeling data using Amazon SageMaker Ground Truth for human feedback.
- **`RLHF_Fine_Tune_Model_to_Detoxify_Summaries.ipynb`**: A notebook example that demonstrates how to fine-tune a pre-trained LLM using RLHF to detoxify and align the model's outputs with desired behavior.
  
## Installation

To run the notebooks and code examples, you will need to install the necessary dependencies.

### Prerequisites

- Python 3.8+
- Jupyter Notebook
- PyTorch or TensorFlow (depending on the model)
- Hugging Face's Transformers library (optional but recommended for working with pre-trained LLMs)
- Amazon SageMaker SDK (if using SageMaker for labeling)

### Steps

1. Clone the repository:
    ```bash
    git clone https://github.com/diaxz12/rlhf-enhancing-llms.git
    ```

2. Navigate to the project directory:
    ```bash
    cd rlhf-enhancing-llms
    ```

3. Launch Jupyter Notebook:
    ```bash
    jupyter notebook
    ```

## Usage

To use the provided notebooks:

1. Open the relevant notebook in Jupyter (e.g., `RLHF_Fine_Tune_Model_to_Detoxify_Summaries.ipynb`).
2. Follow the step-by-step instructions within each notebook.
3. Modify the hyperparameters and model settings as needed for your use case.

## Contributing

Contributions are welcome! Feel free to submit issues or pull requests to improve this project.

### To Contribute:

1. Fork the repository.
2. Create a new branch for your feature or fix: `git checkout -b feature-name`.
3. Commit your changes: `git commit -m 'Add new feature'`.
4. Push to the branch: `git push origin feature-name`.
5. Open a Pull Request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
