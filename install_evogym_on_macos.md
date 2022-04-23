## Install evogym on MacOS

```bash
$ git clone --recurse-submodules https://github.com/EvolutionGym/evogym.git
$ conda create -n evogym python=3.7
$ conda activate evogym
$ pip install -r requirements.txt
$ ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"
$ brew install glew glfw
$ cd evogym
$ python setup.py install
$ cd examples
$ python gym_test.py
```
