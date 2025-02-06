# Regression Study: From Simple to Beyond Linearity

This repository contains an in-depth study on regression analysis, starting from Simple Linear Regression and gradually moving beyond linearity. The study is conducted using three different datasets, analyzed in the following Jupyter notebooks:

## Notebooks

1. **advertising.ipynb** - Examines the relationship between advertising budgets and sales.
2. **credit.ipynb** - Investigates the relationships between the quantitative and qualitative characteristics of bank account holders and their balance.
3. **auto.ipynb** - Explores the correlation between vehicle attributes and their performance.

## Installation

To replicate this project, ensure you have Python installed. It is recommended to use a virtual environment:

```bash
python -m venv .venv
source .venv/bin/activate  # On Windows use: .venv\Scripts\activate
```

Then, install the required dependencies using:

```bash
pip install -r requirements.txt
```

This will install all necessary libraries used in the Jupyter notebooks.

## Usage

Once dependencies are installed, you can open and run the notebooks using Jupyter:

```bash
jupyter notebook
```

Then, navigate to the desired notebook and execute the cells.

## Repository Structure
```
.
├── advertising.ipynb
├── credit.ipynb
├── auto.ipynb
├── requirements.txt
├── .gitignore
├── data/  # Contains datasets (ignored in git)
├── .venv/  # Virtual environment (ignored in git)
└── README.md
```

## .gitignore
```
data/
.venv/
```

## License
This project is provided for educational purposes. Feel free to modify and use it as needed.

---

Happy coding!

