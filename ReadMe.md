## Databricks Asset Bundle Template for MLOps Project

### Overview
This repository contains a Customized Databricks asset bundle template designed to streamline the development and deployment of MLOps projects. The template provides a structured approach to managing machine learning workflows in Databricks.

## Features
- **Easy Integration**: Seamlessly integrates with existing Databricks environments.
- **Scalability**: Designed to scale with your data and compute needs.
- **Version Control**: Supports versioning of assets for better management.
- **Collaboration**: Facilitates collaboration among data scientists and engineers.
- **CICD**: Integrates Github Actions CICD Pipelines to different project instances.

## Getting Started
### Prerequisites
- Databricks account
- Basic knowledge of Python and Databricks notebooks
- Familiarity with ML workflows

### Installation
1. Install the Databricks CLI by following the instructions at [Databricks CLI Installation](https://docs.databricks.com/en/dev-tools/cli/install.html).

2. Verify Installation using
    ```bash
    databricks --version

3. Clone the repository:
   ```bash
   git clone https://github.com/Prosperibe12/databricks-mlops-template.git

4. Create your project directory
    ```
    mkdir <dir-name>
    cd <dir-name>

5. Run the Databricks bundle init command
    ```
    databricks bundle init <path-to-cloned-repo>
    Answer the on screen questions.