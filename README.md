# Personalized Stock Recommendation with Reinforcement Learning | Spring 2025

This is the repository for the final project of the Reinforcement Learning course during Spring 2025. The project focuses on personalized stock recommendation by modeling users with diverse investment styles and preferences in a simulated trading environment. The objective is to explore how reinforcement learning (RL) methods can outperform traditional and feature-based approaches in recommending stocks that both maximize return and align with individual user preferences.

Project Highlights:

1. User Simulation and Environment Design: Constructed a synthetic environment with 10000 users across 4 distinct investment styles (e.g., growth, value, trader, conservative), each with style-specific risk preferences and behavior evolution. Users interact with a fixed universe of 50 stocks over time in a Gym-compatible environment.

2. Modeling Approaches: Rule-Based Recommender (a heuristic Top-K approach based on user style–stock mapping) vs. Feature-Based Classifier (supervised learning using Random Forest with user–stock pair features) vs. Reinforcement Learning Agents (single-agent PPO trained across all users & multi-agent PPO with style-specific policies for personalized learning).

3. Reward Function: Combines financial return with alignment to user style, encouraging agents to balance profit-seeking with preference satisfaction.

4. Key findings: PPO agents outperform baseline models in both Sharpe ratio and return, while multi-agent PPO achieves 2.6× higher style alignment compared to single-agent PPO, without sacrificing financial performance.

Please feel free to email me at ruoheng.du@columbia.edu for any more information.

<img width="500" alt="results" src="https://github.com/ruoheng-du/reinforcement-learning/raw/main/assets/results.png">
