# Data Science & Programming Digital Library (Books)

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)
[![Category: Books & Guides](https://img.shields.io/badge/Category-Books%20%26%20Reference-purple.svg)](#)
[![Topic: Data Science & AI](https://img.shields.io/badge/Topic-Data_Science_%26_AI-orange.svg)](#)
[![Format: PDF Books](https://img.shields.io/badge/Format-PDF_Books-critical.svg)](#)

English | [فارسی](README_FA.md)

A curated collection of authoritative technical books, practical manuals, cheat sheets, and visual career roadmaps covering **Data Science**, **Machine Learning**, **Deep Learning**, **Statistics**, **Python**, and **SQL**.

---

## Overview

Navigating the vast landscape of data science and artificial intelligence requires structured, reliable learning resources. This repository serves as an organized personal and community reference library designed for developers, data scientists, and students at all levels.

Key highlights:
- **Carefully Categorized**: Partitioned by domain (data analysis, statistics, deep learning, EDA, packages, and career roadmaps).
- **Practical & Hands-On Focus**: Features renowned cookbooks, cheat sheets, and practical engineering guides.
- **Visual Career Roadmaps**: Step-by-step career blueprints for AI Engineers, Data Scientists, Computer Vision specialists, and Big Data professionals.

---

## Library Catalog Matrix

| Category | Topics Covered | Key Works & Resources |
| :--- | :--- | :--- |
| [`data-analysis`](data-analysis/) | Data collection, wrangling, exploration & visualization | *Hands-On Data Analysis with Pandas* |
| [`deep-learning`](deep-learning/) | Modern deep learning architectures, FastAI & PyTorch workflows | *Deep Learning for Coders with Fastai and PyTorch* |
| [`eda`](eda/) | Exploratory data analysis, time series modeling, data mining | *Hands-On Exploratory Data Analysis with Python*, *Practical Time Series Analysis* |
| [`python-packages`](python-packages/) | Data visualization, scientific computing, tabular processing | *Pandas Cookbook*, *Hands-On Matplotlib*, *Learning Pandas* |
| [`statistics`](statistics/) | Probability, inferential statistics, cheat sheets, machine learning math | *Statistics for Data Science*, *Statistics for Machine Learning*, Formula Sheets |
| [`sql`](sql/) | Relational database querying, aggregation, analytical SQL | *SQL for Data Science* |
| [`roadmap`](roadmap/) | Career guides and skill trees for data and AI roles | AI, Data Scientist, Machine Learning, Computer Vision, Big Data |

---

## Getting Started

### Cloning the Repository

To clone the entire collection locally:
```bash
git clone https://github.com/soheilabbasnia/books.git
cd books
```

### Git LFS / Partial Checkout

If you only need a specific folder (e.g. `roadmap/` or `statistics/`), you can use Git sparse-checkout:
```bash
git clone --filter=blob:none --no-checkout https://github.com/soheilabbasnia/books.git
cd books
git sparse-checkout init --cone
git sparse-checkout set roadmap statistics
git checkout main
```

---

## Project Structure

```text
books/
├── data-analysis/          # Practical data wrangling and analytics textbooks
├── deep-learning/          # Deep learning, neural networks, PyTorch & FastAI
├── eda/                    # Exploratory data analysis and time-series guides
├── python-packages/        # Pandas, Matplotlib, and scientific Python manuals
├── roadmap/                # Visual skill trees and career roadmaps
├── sql/                    # SQL and relational database analytics books
├── statistics/             # Statistics, probability, formula sheets & cheat sheets
├── rename-app.py           # Utility script for standardized kebab-case file naming
├── LICENSE                 # Repository license
└── README.md               # English library index
```

---

## Contributing

Contributions, resource recommendations, and updated roadmaps are welcome!
1. Fork the repository.
2. Create your branch (`git checkout -b suggest/awesome-resource`).
3. Commit your recommendation (`git commit -m 'Add recommendation for Reinforcement Learning'`).
4. Push to your branch (`git push origin suggest/awesome-resource`).
5. Open a Pull Request.

---

## License

The curation structure and utility scripts in this repository are licensed under the [MIT License](LICENSE).
Individual book copyrights remain with their respective authors and publishers.

