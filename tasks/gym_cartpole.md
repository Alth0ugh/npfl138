### Assignment: gym_cartpole
#### Date: Deadline: Mar 12, 22:00
#### Points: 3 points

Solve the [CartPole-v1 environment](https://gymnasium.farama.org/environments/classic_control/cart_pole/)
from the [Gymnasium library](https://gymnasium.farama.org/), utilizing only provided supervised
training dataset of 100 examples. Start with the
[gym_cartpole.py](https://github.com/ufal/npfl138/tree/master/labs/02/gym_cartpole.py) template.

The solution to this task should be a _model_ which passes evaluation on random
inputs. This evaluation can be performed by running the
[gym_cartpole.py](https://github.com/ufal/npfl138/tree/master/labs/02/gym_cartpole.py)
with `--evaluate` argument (optionally rendering if `--render` option is
provided), or directly calling the `evaluate_model` method. In order to pass,
you must achieve an average reward of at least 475 on 100 episodes. Your model
should have two outputs (i.e., corresponding to a categorical distribution with
2 output classes).

_When designing the model, you should consider that the size of the training
data is very small and the data is quite noisy._

When submitting to ReCodEx, do not forget to also submit the trained
model.
