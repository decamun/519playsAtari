# 519 Plays Atari
## Description:
A deep reinforcement learning algorithm that learns to play atari games using only a reward function and the pixel input from the screen.

## Authors:
Brian Tong, Devin Caplow, and Aman Sehgal

## Installation instructions:

### VirtualENV:
VirtualENV is a virtual python dev environment. It serves as a 'sandbox' to keep things you install on python from interacting with your outside system.

* run:

pip install virtualenv

* in the project root directory, run:

virtualenv env

* Whenever you work on the project, first go to the project root and run

source env/bin/activate

* Whenever you are finished remember to run:

deactivate

###OpenAI Gym
* In order to install OG from pip run:

pip install gym

* Otherwise, run:

git clone https://github.com/openai/gym
cd gym
pip install -e . # minimal install
