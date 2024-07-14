# Kidney-Disease-Classification-Deep-Learning-Project

## How to Run?

### STEPS:
1. **Clone the repository**

    ```sh
    https://github.com/andrewrobson3000/Kidney-Disease-Classification-Deep-Learning-Project.git
    ```

2. **Create a conda environment after opening the repository**

    ```sh
    conda create -n cnncls python=3.8 -y
    conda activate cnncls
    ```

3. **Install the requirements**

    ```sh
    pip install -r requirements.txt
    ```

4. **Finally run the following command**

    ```sh
    python app.py
    ```

5. **Open up your local host and port**

## MLflow

### Documentation
- **MLflow tutorial**

    ```sh
    mlflow ui
    ```

### DagsHub
- **DagsHub**

    ```sh
    MLFLOW_TRACKING_URI=https://dagshub.com/entbappy/Kidney-Disease-Classification-MLflow-DVC.mlflow
    MLFLOW_TRACKING_USERNAME=entbappy
    MLFLOW_TRACKING_PASSWORD=6824692c47a369aa6f9eac5b10041d5c8edbcef0
    python script.py
    ```

- **Run this to export as env variables:**

    ```sh
    export MLFLOW_TRACKING_URI=https://dagshub.com/entbappy/Kidney-Disease-Classification-MLflow-DVC.mlflow
    export MLFLOW_TRACKING_USERNAME=entbappy 
    export MLFLOW_TRACKING_PASSWORD=6824692c47a369aa6f9eac5b10041d5c8edbcef0
    ```

## DVC

### Commands

```sh
dvc init
dvc repro
dvc dag
