# Bayesian-Soft-Actor-Critic

    Adopting reasonable strategies is challenging but crucial for an intelligent agent with limited resources working in hazardous, unstructured, and dynamic changing environments to improve the system utility, decrease the overall cost, and increase mission success probability. Deep Reinforcement Learning (DRL) helps organize agents' behaviors and actions based on their state and represents complex strategies (composition of actions). This project proposes a novel hierarchical strategy decomposition approach based on Bayesian chaining to separate an intricate policy into several simple sub-policies and organize their relationships as Bayesian strategy networks (BSN). We integrate this approach into the state-of-the-art DRL method, soft actor-critic (SAC), and build the corresponding Bayesian soft actor-critic (BSAC) model by organizing each sub-policies as a joint policy. We compare the proposed BSAC method with the SAC and other state-of-the-art methods such as TD3, DDPG, and PPO on the standard continuous control benchmarks such as the Hopper-v2, Walker2d-v2, and the Humanoid-v2 domains in the OpenAI Gym environment. The results demonstrate the promising potential of the BSAC method in terms of training efficiency.
