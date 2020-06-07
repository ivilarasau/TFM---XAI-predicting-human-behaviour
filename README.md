# UOC - TFM 
# Predicting human behaviour in PGGs using a game theoretical approach

Author: **Ignasi Vilarasau**
Tutor: **Julià Vicens**

## Motivation

The interest of our proposal is based on two things. The first one, is the creation of supervised ML models that, with the maximum accuracy, classifies individuals into discrete behavioural types and it could be applied into simulating societies, policy-making scenario building, and even a variety of business applications. The second one, is based on the applicability of the *eXplainable Artificial Intelligence (XAI)* methods in the post-hoc analysis in order to understand our ML models' results with the maximum information about the features making those results as much human comprehensible as possible, [1]. And another interesting point is that to apply this XAI techniques we will use a solution concept of fairly distributing both gains and costs to several actors working in coalition, based on game theory.
This new sort of techniques are in the trend because humans do not want to accept the models ”as-is” we want to know what is happening in their core, [4].

## Abstract
Social interactions are present on every daily situation, and social situations that involve strategic behaviour are the keys of every social interaction. Those situations can be extrapolated to the *Evolutionary Game Theory* through *Public Good Games (PGG)*[1]. On this sense, studying the behaviour of individuals from the theoretical and experimental point of view can lead to an understanding of how individuals would react and act on those strategic situations and it could be very relevant in order to be able to anticipate the outcomes of every kind of concflict ot social situation.

In order to be able to understand that behaviour we will try to identify discrete behavioural types (clusters) of individuals in experimental data and try to classify each individual's behaviour to one of the types of discrete behaviours previously identified. In addition, we will also apply more machine learning supervised models in order to be able to classify the individuals with the maximum accuracy.

Speaking of machine learning models allows us to also speak about *eXplainable Artificial Intelligence (XAI)*. XAI will create a number of techniques to explain our machine learning (ML) models' prediction by attributing it to the corresponding input features of the different experiments on PGG. For the explaniability of our models we will focus on methods based on Shapley
values from cooperative game theory being prominent among them.

## Objectives

The main goal of this work is to cluster the participants identifying discrete behavioural types. Then we the objective is to create different ML supervised models to predict classify the individuals on those discrete behavioural types depending on their behaviour during the PGGs studying the accuracy and effectiveness of all models. 
The secondary goal is to apply to those supervised ML models XAI techniques (focusing on *SHapley Additive exPlanations (SHAP)*) to explain and better understand the results and see if it can help us getting to much more interesting results and conclusions.

## Structure of the repository

* **Data:** Datasets used on our analysis. Those datasets are from the experiments performed on the studied papers, [6], [8], [9], [10].

* **ML_Models_Pipeline.ipynb:** Script used to create a first EDA approach on each of the different datasets used for the study [8],[9],[10],[11]. Later we apply unsupervised and supervised ML models to Pereda, M.,et Al. 2019. and Vicens, J., et, Al., 2019 to classify different kinds of individual behaviour in contributions. Finally, we use *eXplainable Artificial Intelligence* focusing on the *SHapley Additive exPlanations (SHAP)* to explain and better understand the output of the supervised machine learning models.

## Bibliography

1. **Colin F. Camerer, 2003.** *Behavioral Game Theory: Experiments in Strategic Interaction.* Princeton University Press, 5 de set. 2003.
2. **MCristoph Molnar, 2020.** *A Guide for Making Black Box Models Explainable - Interpretable Machine Learning.* Lulu, 1st edition, March 24, 2019; eBook (GitHub, 2020-04-27).
3. **Fallucchi, et, Al., 2018.** *Identifying discrete behavioural types: a re‑analysis of public goods game contributions by hierarchical clustering.* J Econ Sci Assoc 5, 238–254 (2019). doi:10.1007/s40881-018-0060-7.
4. **Georgios Sarantitis, 2018.** *Interpretable Machine Learning with SHAP.* gsarantitis.wordpres.com.
5. **Arrieta, et, Al., 2019.** *Explainable Artificial Intelligence (XAI): Concepts, Taxonomies, Opportunities and Challenges toward Responsible AI.* doi:10.1016/j.inffus.2019.12.012.
6. **Fraser, S., Nettle, D. 2019.** *Hunger affects social decisions in a Public Goods Game but not an Ultimatum Game.* PsyArXiv. October 2. doi:10.31234/osf.io/67abq.
7. **Allen, J. 2018.** *The public goods game on multiplex networks.* Doctoral thesis, University of Surrey.
8. **Dannenberg, A, et, Al., 2019.** *Voting on the threat of exclusion in a public goods experiment.* Exp Econ 23, 84–109. April 9. doi:10.1007/s10683-019-09609-y.
9. **Pereda, M.,et Al. 2019.** *Large scale and information effects on cooperation in public good games.* Sci Rep 9, 1502. October 21. doi:10.1038/s41598-019-50964-w.
10. **Vicens, J., et, Al., 2019.** *Resource heterogeneity leads to unjust effort distribution in climate change mitigation.* 13(10): e0204369. October 31. doi:10.1371/journal.pone.0204369.
11. **Pereda, M., et, Al., 2019.** *Group size effects and critical mass in public goods games.* Sci Rep 9, 5503. April 2. doi:10.1038/s41598-019-41988-3.
