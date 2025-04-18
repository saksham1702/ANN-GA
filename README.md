# NeuroGenetic: Neural Network Architecture Optimization using Genetic Algorithms

This project implements a genetic algorithm to optimize neural network architectures for manufacturing data analysis. It combines the power of artificial neural networks (ANN) with genetic algorithms to find optimal network architectures and hyperparameters.

## Features

- Genetic Algorithm for Neural Network Architecture Optimization
- Support for multiple layer configurations (1-4 layers)
- Various activation functions (ReLU, tanh, sigmoid, elu)
- Multiple optimizer options (Adam, Adagrad, RMSprop, SGD)
- Automatic hyperparameter tuning
- Performance metrics tracking (RMSE, MAE, R²)

## Project Structure

```
NeuroGenetic/
├── main_NeuroGenetic.py    # Main genetic algorithm implementation
├── genetic.py             # Genetic algorithm operators
├── ann.py                 # Neural network implementation
├── data_input.py          # Data preprocessing
└── README.md              # Project documentation
```

## Requirements

- Python 3.x
- TensorFlow
- NumPy
- Pandas
- scikit-learn

## Installation

1. Clone the repository:
```bash
git clone https://github.com/yourusername/NeuroGenetic.git
cd NeuroGenetic
```

2. Install dependencies:
```bash
pip install -r requirements.txt
```

## Usage

1. Prepare your data in CSV format
2. Run the genetic algorithm:
```bash
python main_NeuroGenetic.py
```

## Parameters

- `num_generations`: Number of generations (default: 4)
- `sol_per_pop`: Solutions per population (default: 40)
- `num_parents_mating`: Number of parents for mating (default: 8)
- `mutation_percent`: Mutation percentage (default: 50)

## Results

The algorithm outputs:
- Best neural network architecture
- Performance metrics (RMSE, MAE, R²)
- Training and validation results
- Final results saved to results.csv

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.
