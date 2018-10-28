
# Learning to Communicate with Deep Multi-Agent Reinforcement Learning

Jakob N. Foerster, Yannis M. Assael, Nando de Freitas, Shimon Whiteson

## PyTorch

\- [PyTorch Implementation by @minqi](https://github.com/minqi/learning-to-communicate-pytorch)

## Abstract

<p align="center">
<img alt="Learning to Communicate" src="http://blog.yannisassael.com/wp-content/uploads/2016/09/switch_vis_768.jpg" />
</p>

We consider the problem of multiple agents sensing and acting in environments with the goal of maximising their shared utility. In these environments, agents must learn communication protocols in order to share information that is needed to solve the tasks. By embracing deep neural networks, we are able to demonstrate end-to-end learning of protocols in complex environments inspired by communication riddles and multi-agent computer vision problems with partial observability. We propose two approaches for learning in these domains: Reinforced Inter-Agent Learning (RIAL) and Differentiable Inter-Agent Learning (DIAL). The former uses deep Q-learning, while the latter exploits the fact that, during learning, agents can backpropagate error derivatives through (noisy) communication channels. Hence, this approach uses centralised learning but decentralised execution. Our experiments introduce new environments for studying the learning of communication protocols and present a set of engineering innovations that are essential for success in these domains.

## Links

\- [PDF](https://papers.nips.cc/paper/6042-learning-to-communicate-with-deep-multi-agent-reinforcement-learning)

\- [Montreal Deep Learning Summer School 2016 talk](http://videolectures.net/deeplearning2016_foerster_learning_communicate/)

## Execution
```
$ # Requirements: nvidia-docker
$ # Build docker instance (takes a while)
$ ./build.sh
$ # Run docker instance
$ ./run.sh
$ # Run experiment e.g.
$ ./run_switch_3-dial.sh
```

## Bibtex
    @inproceedings{foerster2016learning,
        title={Learning to communicate with deep multi-agent reinforcement learning},
        author={Foerster, Jakob and Assael, Yannis M and de Freitas, Nando and Whiteson, Shimon},
        booktitle={Advances in Neural Information Processing Systems},
        pages={2137--2145},
        year={2016} 
    }


## License

Code licensed under the Apache License v2.0
