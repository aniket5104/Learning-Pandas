# Learning Pandas 🐼

This repository documents my journey of learning the pandas library, the cornerstone for data analysis and manipulation in Python. It serves as a personal collection of notes, code snippets, and small projects as I explore the powerful features of pandas.

---

## 📜 About This Repository

The main goal is to create a structured and practical reference guide for myself and anyone else looking to learn pandas. The content ranges from fundamental concepts like `Series` and `DataFrame` objects to more advanced topics like time series analysis and data wrangling.

---

## 📂 Repository Structure

The repository is organized to keep code, data, and notes separate and easy to navigate.
learning-pandas/
│
├── 📁 data/
│   └── # Sample datasets (.csv, .xlsx, etc.) used in notebooks
│
├── 📁 notebooks/
│   └── # Jupyter notebooks with detailed, commented examples
│
├── 📁 scripts/
│   └── # Standalone Python scripts for specific tasks
│
└── 📄 README.md


---

## 🚀 Topics Covered

This repository will cover a wide range of topics, including but not limited to:

* **Core Concepts:** Understanding `Series`, `DataFrame`, and `Index` objects.
* **Data I/O:** Reading from and writing to various file formats like `$CSV$`, `Excel`, `JSON`, and `SQL` databases.
* **Selection & Indexing:** Mastering data retrieval using `.loc[]`, `.iloc[]`, boolean indexing, and multi-level indexing.
* **Data Cleaning:** Techniques for handling missing data (`.dropna()`, `.fillna()`), removing duplicates, and converting data types.
* **Data Wrangling:** Grouping data with `groupby`, and combining datasets using `merge`, `join`, and `concat`.
* **Reshaping Data:** Pivoting and melting dataframes for analysis using `pivot_table` and `melt`.
* **Operations & Functions:** Applying custom functions with `.apply()`, `.map()`, and `.applymap()`.
* **Time Series Analysis:** Working with date and time data, resampling, and window functions.
* **Visualization:** Creating basic plots directly from pandas DataFrames for quick data exploration.

---

## 🛠️ Getting Started

To run the notebooks and scripts locally, follow these steps:

1.  **Clone the repository:**
    ```bash
    git clone [https://github.com/aniket5104/Learning-Pandas.git](https://github.com/aniket5104/Learning-Pandas.git)
    ```
2.  **Navigate to the project directory:**
    ```bash
    cd learning-pandas
    ```
3.  **Install the required packages:**
    It's recommended to use a virtual environment.
    ```bash
    pip install -r requirements.txt
    ```
    *(Note: You will need to create a `requirements.txt` file containing libraries like `pandas`, `numpy`, `jupyterlab`, `matplotlib`, etc.)*

---

## 🤝 Contributing

While this is a personal learning project, suggestions are always welcome! If you find an error or have an idea for improvement, feel free to open an issue or submit a pull request.
