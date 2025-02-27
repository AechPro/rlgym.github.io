
## What is RLGym?
The Rocket League Gym is a python API that can be used to treat the game [Rocket League](https://www.rocketleague.com) as though it were an [OpenAI Gym](https://gym.openai.com)-style environment for Reinforcement Learning projects. 


## How it Works
RLGym comminucates with a [Bakkesmod](https://www.bakkesmod.com/) plugin to control the game while it is running. This enables the Python API to manipulate the game just like a standard Gym environment, with functions like `make()`, `reset()` and `step()`. Bakkesmod also enables RLGym to control the rate at which the physics engine updates while the game is running, so matches inside the game can be run much faster than real-time.

## Requirements
* A Windows 10 PC
* Rocket League (Both Steam and Epic are supported)
* [Bakkesmod](https://www.bakkesmod.com)
* The RLGym plugin for Bakkesmod (It's installed automatically by pip)
* Python >= 3.7

## Installation
RLGym is available on pip, install via
```python
pip install rlgym
```

## Usage
To get set up your first RLGym environment and start training a Rocket League agent, visit our [Getting Started](rlgym.github.io/docs/getting-started) page.
