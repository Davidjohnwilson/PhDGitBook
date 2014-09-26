# Advances in Cylindrical Algebraic Decomposition

### David John Wilson

[![Build Status](https://www.gitbook.io/button/status/book/davidjohnwilson/advances-in-cylindrical-algebraic-decomposition)](https://www.gitbook.io/book/davidjohnwilson/advances-in-cylindrical-algebraic-decomposition/activity)

## Summary

Since their conception by Collins in 1975, Cylindrical Algebraic Decompositions (CADs) have been used to analyse the real algebraic geometry of systems of polynomials. Applications for CAD technology range from quantifier elimination to robot motion planning. Although of great use in practice, the CAD algorithm was shown to have doubly exponential complexity with respect to the number of variables for the problem, which limits its use for large examples.

Due to the high complexity of CAD, much work has been done to improve its performance. In this thesis new advances will be discussed that improve the practical efficiency of CAD for a variety of problems, with a new complexity result for one set of algorithms.

A new invariance condition, truth table invariance (TTICAD), and two algorithms to construct TTICADs are given and shown to be highly efficient. The idea of restricting the output of CADs, allowing for greater efficiency, is formalised as sub-decompositions and two particular ideas are investigated in depth. Efficient selection of various formulation choices for a CAD problem are discussed, with a collection of heuristics investigated and machine learning applied to assist in choosing an optimal heuristic. The mathematical expression of a problem is shown to be of great importance, with preconditioning and reformulation investigated.

Finally, these advances are collected together in a general framework for applying CAD in an efficient manner to a given problem. It is shown that their combination is not cumulative and care must be taken. To this end, a prototype software `CADassistant` is described to help users take advantage of the advances without knowledge of the underlying theory.

The effects of the various advances are demonstrated through a guiding example originally considered by Solotareff, which describes the approximation of a cubic polynomial by a linear function. Na\"ively applying CAD to the problem takes $$916.1$$ seconds of construction (from which a solution can easily be derived), which is reduced to $$20.1$$ seconds by combining various advances from this thesis.

## Acknowledgements

I have been fortunate to have been surrounded and supported by some brilliant people whilst completing my doctoral research. Without those listed below, this thesis would not have been possible.

First, I would like to thank my supervisors, Prof. James H. Davenport and Dr Russell J. Bradford. I am forever grateful for their guidance and support during my studies and the opportunities they have given me. I consider myself very fortunate to have been their student and have gained much more than just academic knowledge under their supervision.

I would also like to thank Dr Matthew England and other collaborators (particularly Prof. McCallum, Prof. Moreno Maza, Prof. Chen, Miss Huang). Not only have I been able to complete interesting research with them, but also had an enjoyable time doing so.

Whilst studying for my Masters, I was inspired by Dr Doron Zeilberger to stop thinking of mathematics and computer science as separate subjects and instead look more deeply at their connection. Further, I am thankful to Dr Z. for the initial suggestion of applying Bath to work on computer algebra. I also wish to thank my tutors at Wadham College (Prof. Woodhouse, Dr Marshall, Dr Hodge) and teachers at Coquet High School (particularly Mr. Singh and Mrs. Adams) for nurturing my mathematical interest and encouraging me to pursue further study.

I have been lucky to have been surrounded by supportive and special friends. They have helped me through tough times and celebrated with me through happy times. Thanks to them, I've come through the last three years with a smile on my face.

Finally, I would not be where I am today without the endless support of my family: Mum, Dad, and James. They are a constant inspiration and I love them dearly. Thank you for everything over the last twenty-seven years, I owe it all to you.

**D.J.W.**
