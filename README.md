# CLT simulation
[Live Link Preview] (https://veeedant.github.io/CLT_simulation/)
## Project Type: Statistical Modeling & Data Simulation

## Tools Used: Python (NumPy, Matplotlib), Jupyter Notebook, HTML Export

# Objective
The primary goal of this project is to demonstrate the Central Limit Theorem (CLT) by simulating how random sample means transform into a Gaussian Bell Curve. By taking 20,000 iterations from a massive population of 1 million numbers, this simulation visually proves that as the sample size (k) increases from 4 to 50, the resulting distribution becomes significantly sharper and more precise. This transition highlights the core mathematical phenomenon where increasing sample sizes reduces variability, forcing the averages to converge tightly around the true population mean of 150 regardless of the initial data's shape.

# Methodology
The methodology involves generating a massive Population of 1,000,000 random integers (ranging from 0 to 300) to act as a diverse, high-entropy data source. From this "universe," we execute 20,000 independent sampling trials for different group sizes (k=4,20,50). By calculating the mean of each trial, we track how the distribution of these averages transitions from a wide spread into a low-variance Gaussian curve. This large population ensures that each sample is independent, effectively eliminating sampling bias.

# Key Observations
The Transition: At small sample sizes (k=4), the distribution is wide and flat, showing high variability. As we increase to k=50, the curve becomes a tall, narrow "Bell Shape."
Concentration at the Mean: Regardless of k, the peak of every curve consistently points towards 150, which is the mathematical midpoint of our population.

# Precision & Standard Error
The narrowing of the curve at k=50 is a visual proof of decreasing Standard Error. It demonstrates that larger samples provide a much more accurate estimate of the population.

# Conclusion
This simulation validates the Central Limit Theorem's power to find order within chaos. It proves that with a sufficiently large sample size, we can make highly accurate predictions about a population's behavior. This project serves as a foundational exercise in understanding statistical inference and the mathematical stability of the Gaussian distribution in real-world data science.
