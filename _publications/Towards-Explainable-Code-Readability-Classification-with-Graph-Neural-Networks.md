---
title: "Towards Explainable Code Readability Classification with Graph Neural Networks"
collection: Expected publications (Major Review)
category: manuscripts
permalink: /publication/Towards-Explainable-Code-Readability-Classification-with-Graph-Neural-Networks
excerpt: 'This paper is about the number 3. The number 4 is left for future work.'
venue: 'Journal of Software: Evolution and Process'
---

""Context"": Code readability is of central concern for developers, since a more readable code indicates higher
maintainability, reusability, and portability. In recent years, many deep learning-based code readability
classification methods have been proposed. ""Objective"": Among them, a Graph Neural Network (GNN)-
based model has achieved the best performance in the field of code readability classification. However, it is
still unclear what aspects of the model’s input lead to its decisions, which hinders its practical use in the
software industry. To enhance the interpretability of the model and identify code characteristics influencing
the model’s predictions regarding readability, we propose an explanation framework with GNN explainers.
""Method"": First, we propose a simplified Abstract Syntax Tree (AST)-based code representation method,
which transforms Java code snippets into ASTs and discards lower-level nodes with limited information.
Then, we retrain the state-of-the-art GNN-based model together with our simplified program graphs. Finally,
we employ SubgraphX to explain the model’s code readability predictions at the subgraph-level and visualize
the explanation results to further analyze what causes such predictions. ""Result"": The experimental results
show that sequential logic, code comments, selection logic, and nested structure are the most influential
code characteristics when classifying code snippets as readable or unreadable. Further investigations indicate
the model’s proficiency in capturing features related to complex logic structures and extensive data flows
but point to its limitations in identifying readability issues associated with naming conventions and code
formatting. ""Conclusion"": The explainability analysis conducted in this research is the first step toward more
transparent and reliable code readability classification. We believe that our findings are useful in providing
constructive suggestions for developers to write more readable code and delimitating directions for future
model improvement
