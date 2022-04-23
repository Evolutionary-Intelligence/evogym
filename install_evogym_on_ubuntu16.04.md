# Install evogym on Ubuntu16.04

```bash
$ sudo apt-get update
$ sudo apt-get install xorg-dev libglu1-mesa-dev libglew-dev -y
$ git clone --recurse-submodules https://github.com/EvolutionGym/evogym.git
$ cd evogym/
$ conda env create -f environment.yml
$ conda activate evogym
$ python setup.py install
$ cd examples/
$ python gym_test.py
```
