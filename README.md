# Taghche Graph sentiment anaysis

This repository contains implementations of graph-based machine learning models using Node2Vec and Graph Neural Networks (GNNs). These models are designed to analyze and extract insights from graph-structured data.

## Taghche Dataset

The Taghche dataset is an Iranian book review dataset containing user reviews and ratings for various books. It provides valuable insights into user preferences and sentiments regarding different literary works. The dataset can be used for tasks such as recommendation systems and sentiment analysis.

## Sentiment Analysis Task

One of the key tasks in this repository is sentiment analysis, where the goal is to classify user reviews as positive, negative, or neutral. This helps in understanding user opinions and trends in book reviews. By leveraging graph-based techniques, we aim to enhance the accuracy of sentiment classification using contextual relationships between users and books.

## Contents

- `taghche_node2vec.ipynb`: Implementation of the Node2Vec algorithm for learning low-dimensional node embeddings.
- `taghche-GNN.ipynb`: Implementation of a Graph Neural Network (GNN) for node classification and graph-based predictions.

## Installation

To run these notebooks, install the necessary dependencies:

```sh
pip install -r requirements.txt
```

Alternatively, install the required Python libraries manually:

```sh
pip install numpy pandas networkx torch torch-geometric matplotlib
```

## Usage

1. Clone this repository:
   ```sh
   git clone https://github.com/saharEskandari/taghche.git
   cd taghche
   ```
2. Open Jupyter Notebook:
   ```sh
   jupyter notebook
   ```
3. Run the notebooks in the Jupyter interface.

## Dependencies

- Python 3.x
- Jupyter Notebook
- PyTorch & PyTorch Geometric
- NetworkX
- NumPy & Pandas
- Matplotlib

## Results

- The `taghche_node2vec.ipynb` notebook demonstrates how to generate and visualize node embeddings.
- The `taghche-GNN.ipynb` notebook trains a GNN model and evaluates its performance on a dataset.

## Contributors

- **sahar Eskandari**

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

