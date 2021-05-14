# Attack The Castle(Game)


The game will be used to experiment some AI Algorithms. There are two AI Algorithms that have been already implemented:
1. AlphaZero
2. Minimax

## Requirement

1. Python 3.6 (Anaconda Python is preferred)
2. Pandas
3. Tensorflow (For implementing AlphaZero)
4. Keras (For implementing AlphaZero)
5. PtQt5 (For the GUI)

Install Python Anaconda if you haven't
https://www.anaconda.com/download/

install each packages by using `pip install`

## Configuration
You can see `config.py` for the configuration of this program and edit it.
See the `config.py` for further information


## How to use
1. Clone the git repository
2. Do the following accordingly:

*Train AlphaZero without pre-trained model (the model that you have previously trained)*:  
`python main.py train -azt`

*Train AlphaZero from pre-trained model*:  
`python main.py train -aztc`

*Play the game with PyQt5 GUI* :  
`python main.py play -p GUI`

CLI is currently unavailable






