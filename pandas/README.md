# 🐼 Pandas Mastery: Data Manipulation & Analysis

![Pandas Version](https://img.shields.io/badge/Library-Pandas-blue?style=for-the-badge&logo=pandas)
![Python Version](https://img.shields.io/badge/Language-Python-yellow?style=for-the-badge&logo=python)
![Learning Path](https://img.shields.io/badge/Learning-Data%20Science-green?style=for-the-badge)

Welcome to the **Pandas** module of the `Data-Analysis-Learning` repository. This directory is dedicated to mastering **Pandas**, the backbone of data manipulation and analysis in the Python ecosystem.

Whether you are transitioning from Excel or diving deep into Data Science, this guide covers everything from basic Series to complex Time-Series analysis.

---

## 📑 Table of Contents
- [🎯 Learning Objectives](#-learning-objectives)
- [🚀 Roadmap](#-roadmap)
- [🛠️ Core Concepts](#️-core-concepts)
- [📂 Directory Structure](#-directory-structure)
- [💻 Quick Start Example](#-quick-start-example)
- [📚 Resources](#-resources)

---

## 🎯 Learning Objectives
By the end of this module, you will be able to:
- [x] Understand the architecture of `Series` and `DataFrame`.
- [x] Perform advanced data cleaning and handling missing values.
- [x] Master slicing, indexing, and boolean masking.
- [x] Execute complex GroupBy operations and Pivot Tables.
- [x] Perform efficient Time-Series manipulations.

---

## 🚀 Roadmap

### 🟢 Phase 1: The Fundamentals
*Introduction to data structures, loading CSV/Excel, and basic inspection (`head`, `info`, `describe`).*

### 🟡 Phase 2: Data Selection & Manipulation
*Indexing (`loc`, `iloc`), filtering data, adding/dropping columns, and handling duplicates.*

### 🟠 Phase 3: Data Cleaning
*Dealing with `NaN` values, data type conversion, string operations, and handling outliers.*

### 🔴 Phase 4: Advanced Analysis
*Merging/Joining DataFrames, GroupBy mechanics, Pivot Tables, and Reshaping data.*

---

## 🛠️ Core Concepts

| Concept | Description | Key Methods |
| :--- | :--- | :--- |
| **Series** | 1-Dimensional labeled array. | `pd.Series()` |
| **DataFrame** | 2-Dimensional labeled data structure. | `pd.DataFrame()` |
| **Vectorization** | Performing operations on whole arrays without loops. | `df['col'] * 2` |
| **Broadcasting** | Aligning arrays of different shapes during math ops. | `df + 10` |
| **Boolean Masking**| Filtering data based on logical conditions. | `df[df['age'] > 25]` |

---

## 📂 Directory Structure
```bash
pandas/
├── 01_basics/              # Series, DataFrames, and I/O operations
├── 02_indexing_selection/  # loc, iloc, and slicing
├── 03_cleaning/            # Handling missing data and types
├── 04_transformation/     # GroupBy, Pivot, and Merging
├── notebooks/             # Interactive Jupyter Notebooks for practice
└── README.md               # This file


## 💻 Quick Start Example

To get started, ensure you have pandas installed:
`pip install pandas`

## 📚 Resources

📖 Official Pandas Documentation
🎥 Pandas Tutorials on YouTube
🧪 Kaggle Datasets for Practice
