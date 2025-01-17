# Qiskit_Hackathon_IITR_2021
Team Random Chaos' repository for Qiskit Fall Fest Hackathon, IITR 2021

## Aim of the project
  * Develop a basic understanding of the quantum computing
  * Explore different ways to create a quantum random number generator
  * Take video input from user and identify different hand gesture .
  * Develop a interface to play Rock-Paper-Scissor-Lizard-Spock against quantum computer.
  * Analysing human psychology based strategy against complete randomness .

## What we achieved in this project

  * Created a Quantum random generator using noise only over QuasmSimulator in Qiskit.
  * Linked Qrng with web game .
  * Train a classical machine learning model using python to identify different hand gestures for rock, paper, scissors, lizard and spock.
  * Developed web interface for game using html, css ,javascript.



## Instructions
1. Clone this repo into your local machine using the command: 
```
$ git clone https://github.com/tushdon2/Qiskit_Hackathon_IITR_2021.git
```
2. Change your working directory to the cloned repo and create a Virtual Environment. For example, a virtual environment named `venv` can be created using venv by the command: 
```
$ python -m venv venv
```
3. Activate the environment:
  * use `.\venv\Scripts\activate` command in **Windows** 
  * use `$ source venv/bin/activate` in **MacOS** or **Linux**
  * It can later be deactivated by using the `deactivate` command
4. Install the required libraries and packages from the [`requirements.txt`](./requirements.txt) file 
```
$ pip install -r requirements.txt
```

## How to use GUI?
  * Click on configure to configure the webcam
  * Now make the hand gesture of whichever symbol you want to choose (i.e rock,paper,scissor,lizard,spock)
  * Click on “Take Snapshot”
  * Continue playing until either of you or computer scores 5 points
  * Whoever scores 5 points first , wins the game 
  * Start new game for reloading the game .
 
## Rules of the game
   Scissors decapitate Scissors cuts paper, paper covers rock, rock crushes lizard, lizard poisons Spock, Spock smashes scissors, scissors decapitates lizard, lizard eats paper, paper disproves Spock, Spock vaporizes rock, and as it always has, rock crushes scissors.

