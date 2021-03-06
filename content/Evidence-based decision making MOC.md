---
tags:
aliases: EBDM
Literature:
---
# Evidence-based decision making MOC
[[Evidence-based practice process involves the 5A approach]]
### Asking a clinical question
[[There are two types of clinical questions in evidence-based practice]]
[[What is a PICO question?]]
[[Why bother asking PICO questions?]]
[[There are two types of evidence in evidence-based practice]]
### Acquiring the appropriate evidence
[[Textbooks are usually more useful for answering background questions]]
[[Textbooks are limited as they tend to be narrative reviews and do not provide the most up to date information]]
[[Pubmed is a research database for research articles and abstracts]]
[[Point of care tools are more useful for answering foreground questions]]
[[Information of point of care tools may still require critical appraisal by the user]]
### Apraising the evidence
- #### Occurence measures
	- Two types of occurence measures
		- Prevelance - Number of existing cases cases in a population in a designated time
			- Point prevelance
			- Period prevelance
			- ![[Pasted image 20220601120638.png]]
		- Incidence - Number of new cases in a population arising during a given period of time
			- Cumulative incidence
			- Incidence rate
			- ![[Pasted image 20220601120815.png]]
- #### Effect measures
	- [[Effect measures]]
		- Effect measures such as [[Risk ratio]] and [[Odds ratio]] allows us to examine association, the relationship between exposure and outcome
			- [[Risk ratio]]
				- To understand risk ratio, one must first understand the concept of risk.
				- Risk refers to the probability of the outcome, i.e.:
				- Risk/ P(E) = probability of outcome of interest/ probability of all outcomes = number of outcome of interest/number of all outcomes
				- Risk ratio refers to how much more likely the exposed groups is to get the outcome than unexposed groups. 
				- It is a comparison between the incidence of outcome in exposed groups and unexposed groups.
				- ![[Pasted image 20220601121814.png]]
				- When RR < 1, exposure is *associated* with a **lower risk** to the outcome.
				- When RR > 1, exposure is *associated* with a **higher risk** to the outcome.
			- [[Odds ratio]]
				- To understand odds ratio, one must first understand odds.
				- Odds refers to the ratio between the probability of outcome occurring, and the probability of the outcome not occuring,i.e.:
				- Odds = Probability of outcome occuring/Probability of outcome not occuring
				- Odds ratio refers to the ratio between odds of outcome in the exposed group and the unexposed group.
				- ![[Pasted image 20220601123155.png]]
				- When OR < 1, exposure is *associated* with a **lower odds** to the outcome.
				- When OR > 1, exposure is *associated* with a **higher odds** to the outcome.
- #### Examining associations
	- [[Null hypothesis]]
		- ![[Null hypothesis]]
	- [[Random errors]]
		- Random errors are errors due to chance
		- There are two types of random errors: 1) Type 1 random error and Type 2 random error
		- Type 1 errors - Falsely rejecting [[null hypothesis]] when it is true ^16ab77
		- Type 2 errors - Failure to reject a null hypothesis when it is failse
	- P values
		- Probability of [[#^16ab77|Type 1 error]]
		- What are the chances that the results are as extreme or more extreme than current result if repeated many times?
		- P values assumes that null hypothesis is true
		- Significant levels set as P<0.05
	- Confidence interval 
		- 95% confidence interval - 95% convidence that convidence levels include true value
		- Informs range, precision and statistical significance
		- Statistically significant? Does it cross null value (RR/OR = 1)
- #### Study design
	- Observational vs interventional
		- Observational - you just observe the exposure and outcome
		- Interventional - you modify the exposure and wait for outcome
	- Observational study types
		- **Cross sectional studies**
			- Study frequencies of exposure and outcomes at a **particular point of time**
			- Strengths of cross sectional studies
				- Quick and economical
				- Great for generating insights and hypothesis about associations between exposure and outcome
				- Can simutaneously assess multiple associations between exposures and outcomes
			- Weaknesses of cross-sectional studies
				- Cannot measure incidence
				- Cannot establish temporal order between exposure and outcome
				- Potential effects of bias and confounding
		- **Cohort studies**
			- Prospective cohort studies - follows a defined population that do not have the outcome of interest individually
			- ![[Pasted image 20220607121813.png]]
			- Retrospective cohort studies - Outcomes have occured at time of enrollment
			- Benefits of cohort studies
				- Can estimate incidence
				- Can establish temporal sequence between exposure and outcome
			- Limitations of cohort studies
				- Time consuming (especially for those that have long time interval between exposure and outcome)
				- Costly (especially for rare outcomes, requiring large sample size)
				- Potential effects of bias and confounding
		- **Case-control studies**
			- Cases with the outcome is compared to controls without the outcome to assess whether their exposures differ
			- Benefits of case-control studies
				- Cheaper and quicker than cohort studies (especially for rare outcomes)
				- Can look at multiple exposures at the same time
			- Limitations of case-control studies
				- Cannot measure incidence
				- More inefficient for rare exposures
				- Potential effects of bias and confounding
	- Interventional study types
		- Interventional study types involve modifying the exposure and examining its effect on the outcome
		- Individuals are classified into intervention group and control group
		- **Randomised control trials** ^c0c00d
			- Gold standard of study types (due to randomization)
			- What is randomization?
				- Randomly assign participants into different groups
				- Best protection against confounding, as confounders are distributed among the intervention group and control group
			- What is allocation concealment?
				- Ensure investigators who randomize participants have no influence over which group the participant goes to
				- Prevents selection bias (cannot cherry-pick healthier participants into intervention group)
			- What is blinding?
			- Keeping investigators and researchers unaware of which intervention is administered to which patients
			- Prevents reporting/information bias
			- ![[Pasted image 20220607124100.png]]
- #### Systematic errors
	- Information bias
	- Selection bias
		- Selection into study or likelihood being rettained in the study leads to different results
		- Selection bias can occur in all study types, even in randomized control trials (if patients in placebo arm drops out)
		- Selection bias can be minimised by maximizing response rate, minimising attrition and selecting the right population to begin with
- #### Confounding
	- Confounder
		- A confounder is a factor that influence both the exposure and outcome, thus distorting the view of association between the two
		- A confounder must 1) cause the exposure, 2) cause the outcome, and 3) not be on the causal pathway ([[A mediator differs from a confounder as it partakes in the causal pathway between exposure and outcome]])
	- Minimizing confounders to inform true association between exposure and outcome
		- [[#^c0c00d|Randomization in RCT]]
		- Restriction (in accordance to different confounders)
		- Matching (group participants by certain confounders)
			- But may introduce selection bias in case-control trials
		- Stratification (Further stratify by confounders, and compare the strength of association between the different strata)
		- Multivariable analysis (adjustment according to confounders)
- #### Causal inference
	- [[Bradford Hill's Criteria of causal inference]] can be used to infer causal relationships
		- ![[Bradford Hill's Criteria of causal inference]]
- #### Summarizing evidence
	- Systematic review
		- A systematic review reviews all available evidence on a specific topic
		- Strategies ([[Systematic reviews usually involve two or more reviewers to avoid bias]]) are applied to prevent biases in selection, appraisal and synthesis of evidence
		- At the end, a systematic review often performs a [[meta-analysis]] to synthesize new evidence from individual evidence
	- [[meta-analysis]]
		- A statistical method of combining results from individual studies
		- This is usually by weighted average of all data
		- The data is usually presented as a forest plot
		- ![[Pasted image 20220608175216.png]]
	- Strengths of systematic reviews
		- Increases statistical power of individual studies
		- More objective than narrative reviews
	- Limitations of systematic reviews
		- Reporting biases (+ve results are often published while null results are not published)
		- Limited by quality of studies used
		- Meta-analysis may not be appropriate when the results are too heterogenous