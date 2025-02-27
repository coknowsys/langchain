# Agent Simulations

Agent simulations involve interacting one of more agents with eachother.
Agent simulations generally involve two main components:

- Long Term Memory
- Simulation Environment

Specific implementations of agent simulations (or parts of agent simulations) include

## Simulations with One Agent
- [Simulated Environment: Gymnasium](agent_simulations/agent_with_simulated_environment.ipynb): an example of how to create a simple agent-environment interaction loop with [Gymnasium](https://github.com/Farama-Foundation/Gymnasium) (formerly [OpenAI Gym](https://github.com/openai/gym)).

## Simulations with Two Agents
- [CAMEL](agent_simulations/camel_role_playing.ipynb): an implementation of the CAMEL (Communicative Agents for “Mind” Exploration of Large Scale Language Model Society) paper, where two agents communicate with each other.
- [Two Player D&D](agent_simulations/two_player_dnd.ipynb): an example of how to use a generic simulator for two agents to implement a variant of the popular Dungeons & Dragons role playing game.

## Simulations with Multiple Agents
- [Multi-Player D&D](agent_simulations/multi_player_dnd.ipynb): an example of how to use a generic dialogue simulator for multiple dialogue agents with a custom speaker-ordering, illustrated with a variant of the popular Dungeons & Dragons role playing game.
- [Decentralized Speaker Selection](agent_simulations/multiagent_bidding.ipynb): an example of how to implement a multi-agent dialogue without a fixed schedule for who speaks when. Instead the agents decide for themselves who speaks by outputting bids to speak. This example shows how to do this in the context of a fictitious presidential debate.
- [Authoritarian Speaker Selection](agent_simulations/multiagent_authoritarian.ipynb): an example of how to implement a multi-agent dialogue, where a privileged agent directs who speaks what. This example also showcases how to enable the privileged agent to determine when the conversation terminates. This example shows how to do this in the context of a fictitious news show.
- [Generative Agents](agent_simulations/characters.ipynb): This notebook implements a generative agent based on the paper [Generative Agents: Interactive Simulacra of Human Behavior](https://arxiv.org/abs/2304.03442) by Park, et. al.
