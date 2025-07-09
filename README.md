# Topic Modeling on 20 Newsgroups Dataset

This repository contains a Jupyter notebook (`Topic_Modeling.ipynb`) demonstrating how to perform topic modeling on the 20 Newsgroups dataset using the [ktrain](https://github.com/amaiya/ktrain) library.

## Table of Contents

- [Overview](#overview)
- [Installation](#installation)
- [Usage](#usage)
- [Notebook Structure](#notebook-structure)
- [Dependencies](#dependencies)
- [Contributing](#contributing)
- [License](#license)

## Overview

Topic modeling is an unsupervised machine learning technique for discovering thematic structures across a collection of documents. In this notebook, you will:

- Fetch the 20 Newsgroups dataset via `scikit-learn`.
- Build a topic model using `ktrain.text.get_topic_model`.
- Display the top words for each topic.
- Apply filtering based on a frequency threshold to refine the model.

## Installation

1. **Clone the repository**:
   ```bash
   git clone https://github.com/<your-username>/topic-modeling-20newsgroups.git
   cd topic-modeling-20newsgroups
   ```
2. **(Optional) Create a virtual environment**:
   ```bash
   python3 -m venv venv
   source venv/bin/activate
   ```
3. **Install dependencies**:
   ```bash
   pip install --upgrade pip
   pip install -r requirements.txt
   ```
   Alternatively, install the main libraries directly:
   ```bash
   pip install ktrain scikit-learn pandas numpy transformers
   ```

## Usage

1. **Launch Jupyter Notebook**:
   ```bash
   jupyter notebook Topic_Modeling.ipynb
   ```
2. **Run the notebook cells sequentially** to:
   - Install and import `tf_keras` and `ktrain`.
   - Load and preprocess the dataset.
   - Build the topic model.
   - Print and filter topics.

## Notebook Structure

- **Setup**: Installation and import of required libraries.
- **Data Loading**: Fetching the 20 Newsgroups dataset.
- **Modeling**: Creating the topic model with `ktrain`.
- **Filtering**: Refining terms and documents below a set threshold.
- **Results**: Displaying topics before and after filtering.

## Dependencies

- Python 3.7+
- ktrain
- scikit-learn
- pandas
- numpy
- transformers

*Note: The notebook also installs `tf_keras` to support legacy optimizers.*

## Contributing

Contributions are welcome! Feel free to open an issue or submit a pull request.

## License

This project is licensed under the MIT License.
