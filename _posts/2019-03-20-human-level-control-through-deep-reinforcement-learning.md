---
layout: post
share: true
title: Human Level Control Through Deep Reinforcement Learning.
author:
  name: Kabir Ahuja
  email: f2015791@pilani.bits-pilani.ac.in
categories:
- Reinforcement Learning
tags:
- Medium
date: 2019-03-20 10:46:34 +0000

---
**Abstract:** The theory of reinforcement learning provides a normative account1, deeply rooted in psychological2 and neuroscientific3 perspectives on animal behaviour, of how agents may optimize their control of an environment. To use reinforcement learning successfully in situations approaching real-world complexity, however, agents are confronted with a difficult task: they must derive efficient representations of the environment from high-dimensional sensory inputs, and use these to generalize past experience to new situations. Remarkably, humans and other animals seem to solve this problem through a harmonious combination of reinforcement learning and hierarchical sensory processing systems4,5, the former evidenced by a wealth of neural data revealing notable parallels between the phasic signals emitted by dopaminergic neurons and temporal difference reinforcement learning algorithms3. While reinforcement learning agents have achieved some successes in a variety of domains6,7,8, their applicability has previously been limited to domains in which useful features can be handcrafted, or to domains with fully observed, low-dimensional state spaces. Here we use recent advances in training deep neural networks9,10,11 to develop a novel artificial agent, termed a deep Q-network, that can learn successful policies directly from high-dimensional sensory inputs using end-to-end reinforcement learning. We tested this agent on the challenging domain of classic Atari 2600 games12. We demonstrate that the deep Q-network agent, receiving only the pixels and the game score as inputs, was able to surpass the performance of all previous algorithms and achieve a level comparable to that of a professional human games tester across a set of 49 games, using the same algorithm, network architecture and hyperparameters. This work bridges the divide between high-dimensional sensory inputs and actions, resulting in the first artificial agent that is capable of learning to excel at a diverse array of challenging tasks.

**Paper Link:** [https://www.nature.com/articles/nature14236](https://www.nature.com/articles/nature14236 "https://www.nature.com/articles/nature14236")

**Guidelines:** 

1\. Train DQN algorithm on Breakout and Pong

2\. Obtain the plots for loss and average score with training iterations as given in paper.

3\. Implement at least one DQN variant like Double DQN, DQN with Prioritized experience replay and Dueling DQN. Compare its performance with original DQN by plotting the curves of average reward with training iterations.

4\. Visualize the last layer activations of DQN using TSNE as given in the paper