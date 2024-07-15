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
    MLFLOW_TRACKING_URI=https://dagshub.com/andrewrobson3000/my-first-repo.mlflow
    MLFLOW_TRACKING_USERNAME=andrewrobson3000
    MLFLOW_TRACKING_PASSWORD=xx
    python script.py
    ```

- **Run this to export as env variables:**

    ```sh
    export MLFLOW_TRACKING_URI=https://dagshub.com/andrewrobson3000/my-first-repo.mlflow
    export MLFLOW_TRACKING_USERNAME=
    export MLFLOW_TRACKING_PASSWORD=
    ```

## DVC

### Commands

```sh
dvc init
dvc repro
dvc dag
