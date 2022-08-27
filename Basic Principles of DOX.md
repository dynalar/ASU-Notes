# Principles
---
## Randomization
- Running the trials in an experiment in random order
- Idea of balancing out effects of "lurking" variables.
- Just run things randomly to mess around with variance.

## Replication
- Sample size (improving precision of effect estimation, estimation of error or background noise)
	- What should my sample size?
		- Ask yourself how big of a change are you looking for?
		- The bigger the change, the less of amount of testing you have to do.
		- How much does it cost?
		- Can impact randomization.
		- We want enough of a sample size that gives us **Adequate Power**
			- Means that we have an acceptable probability of detecting a non-zero effect of a size that is meaningful to the study.
			- Not easy to do.
- Replication vs repeat measurements?
	- People get confused between replication and repeat measurements.
	- Example: Etching wafers
		- We have a multi wafer etcher, and we put 8 wafers and we put it through etcher.
		- We can see the thickness of these 8 wafers
			- Is this a sample size of 8 replicates?
				- No, we have 1 run, and 8 repeat measurements within that run.
			- Variability of wafers tells me how much variability there is in that tool, PER RUN!
		- THIS IS NOT A REPLICATE!
			- A replicate is a complete rerun of the experiment. Maybe change the settings.
			- It's a complete rerun of the trial.
		- We want to see variabality between runs vs within runs. 
		- Typically, variability between runs is BIGGER than variability between runs.
			- If you mess this up, it can be bad since you can be misled
	- Important distinction between REPLICATION and REPEAT MEASUREMENT

## Blocking
- Dealing with nuisance factors.
	- Factors that have impact on result, but theyre things we're not interested in studying at this point in time.
	- Example: wafers again!
		- What if the operators in an experiment are different? How do we account for variability between operators in an experiment?
			- Try to make that variability go away.
			**- Blocking MINIMIZES the source of that variability.**
- When designing experiments, you have to separate variables into groups.
	- One you're going to study and vary
	- One set that are BLOCKING factors (nuisance factors)
	- 