# Flappy Bird NEAT

Welcome to the repository of Flappy Bird NEAT, a modern take on the classic Flappy Bird game enhanced with the power of the NeuroEvolution of Augmenting Topologies (NEAT) algorithm. This project demonstrates the fascinating capabilities of genetic algorithms in evolving a neural network that masters the game autonomously.

## Introduction

The traditional Flappy Bird game involves navigating a bird through a series of obstacles by tapping the screen to make the bird flap its wings and avoid hitting the pipes. In this project, we apply the NEAT algorithm to train the bird to play the game on its own. The NEAT algorithm dynamically adjusts both the topology and weights of the neural network during evolution.

This project was inspired by and guided through tutorials by the YouTube channel **Tech With Tim**. His series on game development and AI integration was instrumental in the creation of this NEAT-based Flappy Bird.

## Features

- **Autonomous Gameplay**: Watch as the AI learns to navigate through pipes on its own with increasing proficiency.
- **NEAT Implementation**: Integration of the Python-NEAT library, which handles the evolution of neural networks.
- **Graphical Interface**: Visual representation of the game and real-time viewing of the neural network's decision-making process.
- **Statistics Tracking**: Detailed logging of generation count, best fitness scores, and other evolutionary metrics.

## Installation

To get started with Flappy Bird NEAT, ensure Python is installed on your system. Follow these steps:

1. Clone this repository:

    ```bash
    git clone https://github.com/yourusername/flappybird-neat.git
    cd flappybird-neat
    ```

2. Install the required Python libraries:

    ```bash
    pip install -r requirements.txt
    ```

## Usage

Run the game by executing the following command from the root directory of the project:

```bash
python flappy_bird_game.py
```

The game window will open, and you can observe how the NEAT algorithm trains the bird to play the game over successive generations.

## Configuration

Customize various aspects of the NEAT algorithm and the game itself by modifying the `config-feedforward.txt` file. This includes settings such as population size, fitness criteria, mutation rates, and more.

## Contributing

Contributions to Flappy Bird NEAT are welcome! Whether it's reporting bugs, proposing new features, or submitting pull requests, your help is appreciated. Please read `CONTRIBUTING.md` for more details on how to contribute.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE.md) file for details.

## Acknowledgments

- **Tech With Tim** for the educational content that inspired and guided this implementation.
- The NEAT-Python library for enabling the integration of the NEAT algorithm.
- The original Flappy Bird game creators for the game concept.
- The open-source community for tools and libraries that facilitated this project.

Enjoy exploring the capabilities of evolutionary algorithms with Flappy Bird NEAT!
