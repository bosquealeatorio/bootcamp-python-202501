# Bootcamp Python Environment Setup

This guide explains how to set up a Python environment using Conda and the provided `environment.yml` file.

## Prerequisites

Ensure you have the following installed:
- [Miniconda](https://docs.conda.io/en/latest/miniconda.html) or [Anaconda](https://www.anaconda.com/)

## Steps to Create the Environment

1. **Clone the Repository** (if applicable):
   ```bash
   git clone <repository-url>
   cd <repository-folder>
   ```

2. **Create the Environment:**
    Use the provided environment.yml file to create a Conda environment named bootcamp-python:
    ```bash
    conda env create --file environment.yml --name bootcamp-python
    ```

3. **Activate the Environment:**
    Once the environment is created, activate it using:
    ```bash
    conda activate bootcamp-python
    ```

4. **Verify Installation:**
    Ensure all required packages are installed:
    ```bash
    conda list
    ```
    
**Notes**

The environment.yml file specifies the required dependencies and their versions for reproducibility.
If you encounter issues, ensure your Conda installation is up-to-date:

```bash
conda update -n base -c defaults conda
```

Enjoy your Python bootcamp environment!