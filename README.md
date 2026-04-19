# Monte-Carlo-simulation-for-project-risk-assessment

This project demonstrates how Monte Carlo simulation can be used to analyze uncertainty in project completion time.

Traditional project planning often relies on single-point estimates, which are usually overly optimistic. In reality, project tasks are uncertain and can vary due to multiple risk factors. This project replaces fixed estimates with probability distributions to better understand risk and variability.

Monte Carlo simulation helps answer key questions such as:

What is the probability that a project finishes on time?
What is a realistic project completion duration?
What are the possible worst-case and best-case outcomes?


# Modeling Uncertainty
Each task duration is modeled as a random variable using probability distributions.


# Simulation Process
Generate random values for each task
Compute total project duration
Repeat for 10,000+ iterations
Output Metrics

From the simulation results, below was computed:

Minimum (best case)
Maximum (worst case)
Average duration
