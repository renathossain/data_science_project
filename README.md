# Navigating the Social Landscape: An Examination of Agreeableness in Generalists vs. Specialists on Reddit

## Abstract

The idea of our project is to compare agreeableness of generalists vs. specialists. Our hypothesis is that generalists are more agreeable than specialists because generalists tend to be more interested in staying on the platform and learning, while specialists are more passionate about their field and have stronger opinions. The motivation of our project is to assess how specialists interface differently with online community forums compared to generalists, particularly their communication styles. We will be building upon the GS score calculations derived in the paper Generalists and Specialists: Using Community Embeddings to Quantify Activity Diversity in Online Platforms, https://dl.acm.org/doi/pdf/10.1145/3308558.3313729. We will be partitioning our dataset independently based on GS-score, as well as an AD-score, which will be derived based on word embeddings to determine whether a user’s comments are more agreeable or disagreeable. We will also explore how generalists and specialists change over time.

## Research Questions

### PRIMARY RESEARCH QUESTION

Do generalists behave in a more or less agreeable manner than specialists?

### SECONDARY RESEARCH QUESTIONS

- How do specialists communicate differently from generalists?
- Can we differentiate generalist/specialist users within communities based on the vocabulary and sentence structure used in their comments?
- Do generalists adapt their communication styles to fit the culture of communities more flexibly than specialists?
- How do generalists/specialists change over time?
- Do generalists tend to become specialists the longer they use the platform?
- Are there instances where a specialist transforms into a different type of specialist?
- If so, how far does their center of mass (in word2vec encoding) shift?
- What are the characteristics of these shifts if they happen?
- Do they tend to be biased in specific directions, and do shifts in specialization occur bidirectionally or unidirectionally?

## Methods

- We did some data cleaning to prepare the data.
- We use the word-to-vec algorithm to create the embedding.
- We use the GS score as defined in the paper to calculate how specialist or generalist a user is.
- We use sentiment analysis to calculate the agreeableness of a user on Reddit (AD-score).
- We ran correlations and other statistics to find out how specialists and generalists differ in agreeableness.
- We visualize GS-score vs AD-score on a scatter plot.
- Partition data based on user and time (perhaps months or years) and calculate GS-score and AD-score for a user at each time partition, and plot histograms of changes (deltas) in GS / AD score.
- Calculate word community embedding center of mass for each time interval and plot histogram of changes (deltas), and also view example trajectories.

## List of contributions from each team member

### Renat Hossain

- Did the title
- Did the methods

### Anis Saha

- Did the abstract
- Did the research questions
