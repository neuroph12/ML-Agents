# Installation (part 2/2)

## Install ML-Agents

###Install Git Large File Storage

The first step is to install Git LFS which allows to download all the files in the Github repesitory.

```bash
brew install git-lfs
```



### Clone the ML-Agents Toolkit Repository

Once installed and the virtual environment launched, you will want to clone the ML-Agents Toolkit GitHub repository.

```bash
git clone https://github.com/marserret/ML-Agents.git
```

The `UnitySDK` subdirectory contains the Unity Assets to add to your projects.
It also contains many [example environments](Learning-Environment-Examples.md) to help you get started.

The `ml-agents` subdirectory contains Python packages which provide
trainers and a Python API to interface with Unity.

The `gym-unity` subdirectory contains a package to interface with OpenAI Gym.



### Install ML-Agents Package

To install the dependencies and `mlagents` Python package, enter the
`ml-agents/` subdirectory and run from the command line:

```bash
pip install -e .
```

If you installed this correctly, you should be able to run
`mlagents-learn --help`



### Install Gym-Unity Package

Come back in the main folder, enter the `gym-unity` subdirectory and run from the command line:

``` bash
pip install -e .
```



### Install Matplotlib

We advise you to install the `matplotlib` package if you want to see the agent observations and launch the notebooks:

```bash
conda install matlplotlib
```



## Next Steps

The next step show you how to [run an environment]() with a notebook and the main command line to interact with it.

