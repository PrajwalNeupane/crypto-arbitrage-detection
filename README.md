# Cryptocurrency Arbitrage Detection using GNN

This project models the cryptocurrency trading ecosystem using Graph Neural Networks (GNNs) to detect arbitrage opportunities across multiple exchanges. The graph representation captures the relationships between different cryptocurrencies and exchanges, helping identify profitable trading cycles in a volatile market.

## Project Structure
- `test.ipynb`: Jupyter notebook for initial data exploration and graph representation.
- `requirements.txt`: List of dependencies required to run the project.
- `.gitignore`: Configuration to ignore unnecessary files (e.g., virtual environments, notebook checkpoints).

## Setup Instructions

1. Clone this repository.
2. Set up a Python virtual environment:
   ```bash
   python -m venv env

## Install Dependencies:
    ```bash
    pip install -r requirements.txt

## Run the Jupyter ntebook to start exploring the data 

    ```bash 
    jupyter notebook test.ipynb 


Notes
This project uses real-time cryptocurrency price data from multiple exchanges via the ccxt library.
Future work will involve implementing a GNN model to detect arbitrage opportunitie