# Decision Tree - Introduction to Artificial Intelligence

## Project Description

This project involves data analysis, preprocessing, and building predictive models on three datasets:
- **Bank Marketing** ([bank/](bank/)): Predict whether a customer will subscribe to a term deposit.
- **Heart Disease** ([heart+disease/](heart+disease/)): Predict the risk of heart disease.
- **Penguins** ([penguins/](penguins/)): Classify penguin species.

**See detailed description in the report:** [Detailed Report](https://drive.google.com/file/d/1gtpDaFVN9H-cPqxMGMvzb34SsryGOb7c/view?usp=sharing)

### Main Notebooks:
- [bank.ipynb](bank.ipynb): Processing and prediction on the Bank dataset.
- [heart_disease.ipynb](heart_disease.ipynb): Processing and prediction on the Heart Disease dataset.
- [penguins.ipynb](penguins.ipynb): Processing and prediction on the Penguins dataset.

Data preprocessing functions are defined in [process.py](process.py).

## Requirements

- Python 3.8+
- Libraries listed in [requirements.txt](requirements.txt)

## Installation

1. **Clone the repository** (if needed):

    ```sh
    git clone <https://github.com/pqkkkkk/DecisionTree.git>
    cd <DecisionTree>
    ```
2. **Install Graphviz on your machine**
- Download from the [Graphviz homepage](https://graphviz.org/download/).
- Add the path to the folder containing `dot.exe` to your system's PATH environment variable.
    For example, on Windows:
    - Download and install Graphviz.
    - Add the path to the `bin` folder of Graphviz (e.g., `C:\Program Files\Graphviz\bin`) to the PATH environment variable.
3. **Install required libraries:**

    ```sh
    pip install -r requirements.txt
    ```

## Usage

1. **Run the notebooks:**

    - Open each notebook file (`bank.ipynb`, `heart_disease.ipynb`, `penguins.ipynb`) using Jupyter Notebook or Visual Studio Code.
    - Execute each cell sequentially to perform preprocessing, train the model, and evaluate results.

2. **Data Preprocessing:**
    - Preprocessing functions are defined in [`penguins_data_preprocessing`](process.py#L30) and [`bank_data_preprocessing`](process.py#L53) ([process.py](process.py)).
    - Data will be automatically processed when running the notebooks.

3. **Results:**
    - Model results, accuracy charts, and confusion matrices will be displayed directly in the notebook.

## Data Directory Structure

- **bank/**: Contains bank data.
- **heart+disease/**: Contains heart disease data.
- **penguins/**: Contains penguin data.

> Please ensure the original data files are placed in the correct directories as shown above for the notebooks to work properly.
