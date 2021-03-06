# Reinforcement Learning in OpenAI gym

This work aims to use reinforcement learning to solve some [gym] environments.
In [examples] there are some basic algorithms.
Then there are [atari] directory with algorithms for solving
[Atari 2600 games][atari-2600] and [classic] directory with algorithms for
classic control problem from OpenAI gym.

[gym]: https://github.com/openai/gym (gym GitHub repository)
[atari]: examples/
[classic]: classic/

It also uses OpenAI [gym-gridworlds] environments that I implemented myself.

[gym-gridworlds]: https://github.com/podondra/gym-gridworlds

## Blog Post

The blog post will be available on [podondra site][site].

[site]: https://podondra.cz/introduction-to-reinforcement-learning.html

## Setup

	$ git clone https://github.com/podondra/gym-rl	# clone this repository
	$ git submodule init
	$ git submodule update	# clone also gym-gridworlds for browsing
	$ python3.6 -m venv venv	# create virtual environment
	$ source venv/bin/activate	# active virtual environment
	$ pip install -U pip setuptools wheel	# update some packages
	$ pip install -r requirements.txt	# install dependencies

## Algorithms for OpenAI gym

This [survey] list algorithms which can be applied to OpenAI gym environment
such as [Atari 2600][atari-2600] games, HumanoidFlagrun or Kick and Defend.

[survey]: surveys/gym-algorithms-survey.md
[atari-2600]: https://en.wikipedia.org/wiki/Atari_2600

## References

- [Reinforcement Learning: An Introduction](http://incompleteideas.net/book/the-book-2nd.html)
- [David Silver: Reinforcement Learning Course](http://www0.cs.ucl.ac.uk/staff/d.silver/web/Teaching.html)
- [John Schulman: Deep Reinforcement Learning](https://www.youtube.com/watch?v=aUrX-rP_ss4)
- [Learning Reinforcement Learning](http://www.wildml.com/2016/10/learning-reinforcement-learning/)
- [Deep Reinforcement Learning: Pong from Pixels](http://karpathy.github.io/2016/05/31/rl/)
- [Learning from Delayed Rewards](http://www.cs.rhul.ac.uk/~chrisw/thesis.html)
- [Dynamic Programming and Optimal Control](http://web.mit.edu/dimitrib/www/dpchapter.html)
- [OpenAI Baselines](https://github.com/openai/baselines)
