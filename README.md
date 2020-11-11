# Literature_xAI
In this repository there are some found literature on explainability

## Interpretable ML book
The book focuses on machine learning models for tabular data (also called relational or structured data)
 and less on computer vision and natural language processing tasks. 
https://christophm.github.io/interpretable-ml-book/


## Limitations of Interpretable Machine Learning Methods
This book explains limitations of current methods in interpretable machine learning. 
The methods include partial dependence plots (PDP), Accumulated Local Effects (ALE), permutation feature importance, 
leave-one-covariate out (LOCO) and local interpretable model-agnostic explanations (LIME).
 All of those methods can be used to explain the behavior and predictions of trained machine learning models.
  But the interpretation methods might not work well in the following cases:

 - if a model models interactions (e.g. when a random forest is used)
 - if features strongly correlate with each other
 - if the model does not correctly model causal relationships
- if parameters of the interpretation method are not set correctly


This book is the outcome of the seminar “Limitations of Interpretable Machine Learning” which took place in summer 2019 at the Department of Statistics, LMU Munich.

https://compstat-lmu.github.io/iml_methods_limitations/

## XAI Stories
This book is the result of a student projects for Interpretable
 Machine Learning course at the University of Warsaw and the Warsaw University of Technology.
 Each team has prepared one case study for selected XAI technique.

https://pbiecek.github.io/xai_stories/

## Interpreting random forests

Turning a black box into a white box: decision paths
When considering a decision tree, it is intuitively clear that for each decision that a tree (or a forest) makes there is a path (or paths) from the root of the tree to the leaf, consisting of a series of decisions, guarded by a particular feature, each of which contribute to the final predictions.
A decision tree with M leaves divides the feature space into M regions Rm,1≤m≤M

http://blog.datadive.net/random-forest-interpretation-with-scikit-learn/
http://blog.datadive.net/interpreting-random-forests/

## Shapley

Github and python implementation
https://github.com/slundberg/shap

AI Simplified: SHAP Values in Machine Learning - short youtube video with an introduction
to shapley vlaues
https://www.youtube.com/watch?v=Tg8aPwPPJ9c&ab_channel=DataRobot


Presentation of Shapley Values, interesting questions at 33:10 -- 40:50
 https://www.youtube.com/watch?v=B-c8tIgchu0&t=3870s&ab_channel=MicrosoftResearch



Nature paper about Tree Explainer: **Explainable AI for Trees: From Local Explanations to Global
Understanding**
https://www.nature.com/articles/s42256-019-0138-9
https://arxiv.org/pdf/1905.04610.pdf

## AI4EU
This page is meant to be an accessible entry point to what is meant by
 “Explainable AI”, and to the resources on Explainable AI that are available
  in the AI4EU AI on-demand platform.
   This guide is part of the broader AI4EU scientific vision
    on “Human-centered AI”.
    
    https://www.ai4eu.eu/simple-guide-explainable-artificial-intelligence
    
**AAAI 2019 Tutorial On Explainable AI:From Theory to Motivation, Applications and Limitations:** 
   Great tutorial with a lot of slides

   https://xaitutorial2019.github.io/
   https://github.com/xaitutorial2019/xaitutorial2019.github.io/raw/master/slides/aaai_2019_xai_tutorial.pdf
   
 **T3: SHAP-Tree-MCDA:** an explanation module for hierarchical Multi-Criteria Decision Aid (MCDA) models.
  The module computes the level of contribution of each node in the tree when comparing two options
   described by a value over each attribute.

 - Link to the tool: https://www.ai4eu.eu/resource/shap-tree-mcda
 - Research paper: https://www.ijcai.org/Proceedings/2018/0046.pdf
 
 ## Review papers
 Principles and Practice of Explainable Machine Learning
 https://arxiv.org/abs/2009.11698
 
 Stop explaining black box machine learning models
  for high stakes decisions and use interpretable models instead
   https://www.nature.com/articles/s42256-019-0048-x
   
   Explaining explanation in AI https://arxiv.org/abs/1811.01439
   
   Explanation in Artificial Intelligence: Insights from the Social Sciences
    https://arxiv.org/abs/1706.07269
 
 
## Decision Tree and RF Path explainers

A. Saabas. treeinterpreter Python package. url: https://github.com/andosa/treeinterpreter.

Blog http://blog.datadive.net/interpreting-random-forests/ 

Understanding Random Forests: From Theory to Practice 
Phd thesis https://arxiv.org/abs/1407.7502

## Lime


## Consensus


## Python Implementations
Shapley - https://github.com/slundberg/shap
Lime - https://github.com/marcotcr/lime

Alibi - Conterfactual, ALE, anchors for images, integrated gradients for text https://github.com/SeldonIO/alibi

## Counterfactual explanations
The paper: https://arxiv.org/pdf/1905.07697.pdf
Implementation: https://github.com/interpretml/DiCE