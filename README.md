# Artificial Intelligence for Moderating Mass Discussion Platforms

## Implementing a Module for the Automation of Argument Sorting and Clustering

Author: Aruzhan Zadanova

## Table of Contents
1. [Introduction](#introduction)
2. [Repository Contents](#repository-contents)
3. [Installation](#installation)
4. [Usage](#usage)
5. [Features](#features)
6. [Dataset](#dataset)
7. [Evaluation](#evaluation)
8. [Contributing](#contributing)
9. [License](#license)

## Introduction

This repository contains the implementation of an AI-driven moderation system designed for mass discussion platforms. The project focuses on automating argument sorting, clustering, summarization, and toxic comment detection using machine learning techniques. It also incorporates explainable AI (XAI) components to ensure transparency and build user trust.

## Repository Contents

This repository consists of two Jupyter notebook files:

1. `thesis_version_with_generated_data_XAI.ipynb`: This notebook contains the initial implementation using a generated dataset, with a focus on XAI techniques.

2. `thesis_version_with_larger_dataset.ipynb`: This notebook extends the work to a larger, real-world dataset, demonstrating the scalability and effectiveness of the approach.

## Installation

To run these notebooks, you'll need Jupyter and several Python libraries. Here's how to set up your environment:

1. Clone this repository:
   ```
   git clone https://github.com/zadanova/Development-and-Implementation-of-Artificial-Intelligence-for-Moderating-Mass-Discussion-Platforms.git


   cd Development-and-Implementation-of-Artificial-Intelligence-for-Moderating-Mass-Discussion-Platforms
   ```

2. Install the required packages:
   ```
   pip install jupyter pandas numpy scikit-learn transformers torch seaborn matplotlib wordcloud lime
   ```

## Usage

To use these notebooks:

1. Start Jupyter Notebook:
   ```
   jupyter notebook
   ```

2. Open either `thesis_version_with_generated_data_XAI.ipynb` or `thesis_version_with_larger_dataset.ipynb` in the Jupyter interface.

3. Run the cells in order to see the implementation and results.

## Features

Both notebooks implement the following features:

- Argument Clustering: Using K-means algorithm to group similar comments.
- Automatic Summarization: Generating concise summaries of discussions using pre-trained models.
- Toxic Comment Detection: Identifying potentially harmful comments.
- Explainable AI (XAI): Providing transparency through techniques like LIME and SHAP.
- Visualization: Including cluster visualizations, word clouds, and performance graphs.

## Dataset

- `thesis_version_with_generated_data_XAI.ipynb` uses a small, generated dataset for initial testing and development.
- `thesis_version_with_larger_dataset.ipynb` uses a larger dataset derived from Reddit's r/CasualConversation subreddit, containing 500 three-turn conversations collected between 2016-12-29 and 2019-12-31.

## Evaluation

The notebooks include various evaluation metrics and visualizations:

- Clustering quality assessment using silhouette scores
- Summarization quality evaluation using ROUGE scores
- Toxic comment detection performance metrics (precision, recall, F1-score)
- Visualizations of clustering results, word importance, and system performance

## Contributing

Contributions to this project are welcome. To contribute:

1. Fork the repository
2. Create a new branch (`git checkout -b feature/YourFeature`)
3. Commit your changes (`git commit -m 'Add some feature'`)
4. Push to the branch (`git push origin feature/YourFeature`)
5. Open a Pull Request

## License

This project is licensed under the MIT License - see the `LICENSE.md` file for details.
