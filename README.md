# 519 Plays Atari
## Description:
A deep reinforcement learning algorithm that learns to play atari games using only a reward function and the pixel input from the screen.

## Authors:
Brian Tong, Devin Caplow, and Aman Sehgal

## Installation instructions:

### Setup
Install initial dependencies.

* OSX:

brew install cmake boost boost-python sdl2 swig wget

* Ubuntu:

apt-get install -y python-numpy python-dev cmake zlib1g-dev libjpeg-dev xvfb libav-tools xorg-dev python-opengl libboost-all-dev libsdl2-dev swig

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

### OpenAI Gym
* Make sure you have virtualenv activated.
* In order to install OG from pip run:

pip install 'gym[all]'

* Otherwise, run:

git clone https://github.com/openai/gym

cd gym

pip install -e '.[all]'

### Tensorflow
* Follow [instructions](https://www.tensorflow.org/versions/r0.11/get_started/os_setup.html#virtualenv-installation) for installing Tensorflow in VirtualENV

### Test
* Test installation by running:

python quicktest.py
