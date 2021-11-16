# Chess Bot

A basic chess bot based upon the tensorflow linear classifier model.

Chess bot is trained on the 2000+ games of grandmasters i.e, BOTVINIK, FISCHER, etc;. It can be configured to use the pre-trained models present in the [chess-processing-script repo](https://github.com/Khushiyant/chess-processing-script/tree/main/model)

Given pre-trained models provide the 50%-ile elimination for best game moves so, chess-bot optimise the efficiency while implementing the minimax algorithm ( alpha-beta ) 

Instead of using GUI based interaction for I/O, it uses [UCI](https://www.chessprogramming.org/Algebraic_Chess_Notation) based text input

# Usage
---
To run this project 

Run a unit test via google colab link for [notebook](https://colab.research.google.com/github/Khushiyant/chess-linear-ml/blob/main/chess-ml/chess_engine.ipynb) 

For contributing to the training model optimizations, use the [train_engine.ipynb](https://colab.research.google.com/github/Khushiyant/chess-linear-ml/blob/main/chess-ml/train_engine.ipynb) in colab

## Development & Requirements
---
![Alpha Beta Pruning](https://static.javatpoint.com/tutorial/ai/images/alpha-beta-pruning-step3.png)

Understanding of aplha-beta pruning is required for configuration changes

### Depedencies for deployment
* tensorflow
* pandas
* numpy
* cairosvg
* cv2

## Optimizations
---
Although the project is in its initial prototyping stage and, require major improvements in classifier model, GUI input and project app deployment


# Team

### Mentor
[@rajatgupta24](https://github.com/rajatgupta24)
