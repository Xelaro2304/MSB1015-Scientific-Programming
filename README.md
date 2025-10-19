# MSB1015-Scientific-Programming
Maastricht University's MSB1015 Scientific Programming course final project as part of the Systems Biology and Bioinformatics Master's programme

## Chess Data Analysis and Modeling

This repository contains the Jupyter Notebook `Chess.ipynb`, which is used for **Exploratory Data Analysis (EDA)** and **predictive modeling** on a dataset of chess games. The project utilizes various data science libraries and integrates with the **Stockfish chess engine** for advanced game analysis and feature creation.

As an alternative, a cell to download a processed file with the evaluation and prior steps is provided as commented code

---

### Preparation and Setup

#### 1. Duplicate the Repository

Start by cloning this repository to your local machine:

```bash
git clone https://github.com/your-username/your-repo-name.git
cd your-repo-name
```

#### 2. Requirements

The notebook requires **Python 3** and a standalone installation of the **Stockfish chess engine**.

##### Stockfish Engine Installation

It is **necessary to install an adequate Stockfish version** on your operating system. The notebook's core functionality for evaluating positions and generating engine-based features relies on having the Stockfish executable available and the path specified within the code.

Please refer to the official [Stockfish download page](https://stockfishchess.org/download/) for the appropriate installation and path setup instructions.


#### Lichess token

Token is required to communicate with Lichess API as part of the code. Token should be inserted into the BERSERK_TOKEN environmental variable in (`ENV`). More instructions about token are found in [Lichess website](https://lichess.org/account/oauth/token) 

#### 3. Conda Environment (Recommended)
  > For reproducibility, create and activate the provided environment (`ENV`) using conda:  
  ```bash
  conda env create ENVIRONMENT_NAME -f ENV.yml
  conda activate ENVIRONMENT_NAME
  ```

### Running the Notebook
Install Dependencies: Ensure Stockfish is installed and run the package installation cell in the notebook.

Load Data: The notebook automatically downloads a games.csv file from a Google Drive URL to perform the analysis.

Execute Cells: Run the cells sequentially to proceed through the data cleaning, feature engineering, and exploratory data analysis sections.

Link to [Google Colab Notebook](https://colab.research.google.com/github/Xelaro2304/MSB1015-Scientific-Programming/blob/main/Chess.ipynb)
