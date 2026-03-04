# Spark Training

A hands-on PySpark training.

## Option 1: Databricks Community (Recommended)
1.  **Sign Up:** Create a free account at [Databricks Community Edition](https://community.cloud.databricks.com/login.html).
2.  **Clone Repo:**
    *   Go to **Workspace** (left sidebar) -> **Git Folders** (or Repos).
    *   Click **Add** -> **Repo** and paste this repository's URL.

## Option 2: Docker (Local)
Requires Docker installed.

1.  Run the following command in your terminal inside this repository's folder:
    ```bash
    docker run -p 8888:8888 -v "$PWD":/home/jovyan/work jupyter/pyspark-notebook
    ```
    *(Windows users: replace `"$PWD"` with `"%cd%"`)*
2.  Click the `http://127.0.0.1:8888...` link printed in your terminal.
3.  Open the notebook inside the `work` folder.