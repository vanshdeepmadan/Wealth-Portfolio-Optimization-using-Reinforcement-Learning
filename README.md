# Wealth-Portfolio-Optimization-using-Reinforcement-Learning

Key Steps Undertaken:
	•	Data Collection:
	•	Fetched historical stock prices using yfinance for assets like AAPL, MSFT, and GOOGL.
	•	Calculated daily percentage returns for these assets to model market behavior.
	•	Attempt to Create a Gym Environment:
	•	Designed a custom environment (PortfolioEnv) to simulate portfolio allocation and market conditions.
	•	Encountered challenges in aligning observation space dimensions and data types with Gymnasium requirements.

 Next Steps for Completion:
	•	Fix Environment Issues:
	•	Ensure the observation space matches the actual data returned by _get_observation().
	•	Verify reset() and step() methods return correctly formatted outputs.
	•	Train the RL Agent:
	•	Use the PPO algorithm to train the agent in the corrected environment.
	•	Evaluation and Comparison:
	•	Test the agent’s performance and compare it to baseline strategies (e.g., buy-and-hold, Markowitz Model).
