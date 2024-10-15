# Blob Generation LLM with LLaMA2

This repository demonstrates how to set up and run a Blob Generation Language Model (LLM) using LLaMA2.

## Prerequisites

Ensure you have the following installed:
- [Anaconda](https://www.anaconda.com/products/distribution)
- Python 3.8 or later
- Git

## Installation

1. **Clone the Repository**:
    ```bash
    git clone https://github.com/yourusername/blob-generation-llm.git
    cd blob-generation-llm
    ```

2. **Create a Conda Environment**:
    ```bash
    conda create -n blob-gen-llm python=3.9 -y
    conda activate blob-gen-llm
    ```

3. **Install Dependencies**:
    ```bash
    pip install -r requirements.txt
    ```

## Downloading LLaMA2 Model Locally

1. **Navigate to the Models Directory**:
    ```bash
    cd models
    ```

2. **Download LLaMA2 Model**:
    Download the LLaMA2 model files from the official repository or a trusted source. Place the downloaded `.bin` file into the `models` folder. If available from Hugging Face:
    ```bash
    wget https://huggingface.co/llama2/llama-2-7b-chat/resolve/main/llama-2-7b-chat.bin -O llama-2-7b-chat.bin
    ```


## Running the Blob Generation LLM

1. **Run the Streamlit App**:
    ```bash
    streamlit run app.py
    ```

