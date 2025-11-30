# Foundation of Computer Science Project

**Authors:** Saad Ur Rehman Baig and Federico Malatesta

## Project Structure

- `FOCS_project.ipynb`: Jupyter Notebook containing the interactive analysis and data exploration.
- `trendingYT.zip`: Compressed dataset containing CSV files and JSON category files.

## Prerequisites

- **Python**: 3.13.5
- **pandas**: 2.2.3
- **numpy**: 2.1.3
- Jupyter Notebook (for running `.ipynb` files)

You can install the dependencies using pip:

```bash
pip install pandas==2.2.3 numpy==2.1.3
```

## Setup & Running

1.  **Unzip Data**: Ensure the `trendingYT.zip` file is unzipped in the project directory. The notebook expects a `trendingYT` folder containing `[country]videos.csv.zst` files.

    ```bash
    unzip trendingYT.zip
    ```

2.  **Run the Notebook**: Open `FOCS_project.ipynb` in Jupyter Notebook or JupyterLab.

    ```bash
    jupyter notebook FOCS_project.ipynb
    ```

3.  **Execute Cells**: Run the cells sequentially to perform the analysis step-by-step.
