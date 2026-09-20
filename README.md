# reinforcement-learning-cybersecurity

This project develops an intelligent automated cybersecurity solution to counter sophisticated cyberattacks. This solution mitigates network vulnerabilities by simulating real-time attack and defense scenarios using state-of-the-art Reinforcement Learning (RL) techniques. 

The system introduces an advanced defensive optimization architecture built within the complex network simulation environment: 
* **Custom Environment Adaptation:** Implementation of a specialized `DefenderWrapper` to transform the multi-agent `gym-idsgame` interface into a streamlined single-agent framework, allowing the defense agent to react dynamically to internalized attacker bot behaviors. 
* **Dual-Algorithm Training Engine:** Deploying a dynamic SARSA table logic to mitigate standard "random attack" configurations, combined with a Deep Learning PyTorch architecture implementing a Double Deep Q-Network (DDQN) to suppress both "random" and highly persistent "maximal attack" vectors. 
* **Targeted Reward Shaping:** Designing custom reward functions to heavily reinforce defensive victories and minimize the impact of catastrophic network compromises, accelerating gradient convergence and stabilizing target network updates. 

The final evaluation demonstrates the clear superiority of the Deep RL approach over traditional baselines, establishing a robust, automated framework for vulnerable system identification and resource optimization in medical network security. 

To see more, extended explanation in the project.
