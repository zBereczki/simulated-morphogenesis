---
layout: page
title: Theoretical considerations
permalink: /theoretical-considerations/
---

# Procedural method

The essence of the procedural approach is to examine objects, buildings, and cities not as standalone entities, but as the result of a process. The subject of analysis and interpretive modeling based on analysis is thus not the objects, buildings, and cities themselves, but the processes that create them. These processes can be assessed using algorithms.

>„Gothic architecture was governed by procedural conventions, rather than by fixed canons of proportion. The Gothic tradition, in other words, treated the finished building as the physical trace of a dynamic design process whose internal logic mattered more than the shape of the final product.” [Robert Bork](https://geometriesofcreation.lib.uiowa.edu), *Geometry of Creation*, p. 2.

>„Prior to the early-modern standardization of mechanically
reproduced images, we lived for centuries in a world that was algorithmic and normative, not visual and repetitive.” [Mario Carpo](http://architettura.it/extended/20060305/index_en.htm)

>„To find the 'lines of force' in the urban fabric, on which one can build, developing an architectural response from it, or to find the specific logic of the program and superimpose it on this fabric. From these two comes the creation, which is like a birth. It is not in our heads, but actually develops over time." Tamás Noll, *A Miskolci Építész Műhely*, p. 089.

# Simulated Morphogenesis

If the input parameters for creating a generative algorithm are extracted from the analysis of existing structures, then structures similar to the existing structures in the desired aspects but not identical to them can be generated. Using a biological analogy, the extracted data can be considered the genotype, the generated structures the phenotype, and the process itself, according to my own definition, simulated morphogenesis. The method deliberately avoids the use of artificial intelligence: both analytical methods and generative algorithms are based on human intuition, pattern recognition, and design decisions. This is because in the case of generative artificial intelligence, the result, the goal is the generated image, while the process remains hidden. In the case of simulated morphogenesis, on the other hand, the goal is precisely to understand and model the process, i.e. the process description.

# Key concepts

## Semilattice

The concept of semilattice was introduced to the field of architecture in the context of natural cities by Christopher Alexander in 1965 in his seminal work [A City is Not a Tree](https://bp.ntu.edu.tw/001/Upload/1352/ckfile/176357fb-2068-4e40-8c50-593780261ce7.pdf). In this work, the author demonstrates the distinction between artificial and natural cities through a simple mathematical model. The mathematical model of artificial cities is a tree structure, where each element has one and only one parent. In contrast, the mathematical model of natural cities is a semilattice, where an element can be associated with multiple parents, resulting in a much more complex system of relationships, allowing for overlaps and a significantly greater number of possible variations.

![Tree and semilattice, based on Alexander. Source: A City is Not a Tree, p 6., 7.](tree-semilattice.png)

## Recursive definitions

The essence of a recursive definition is that the same description is repeated multiple times, at multiple hierarchical levels, seemingly embedded within itself. In this case, the elements at the lower level inherit their input parameters from the element(s) at the higher level, and pass their output to the element(s) at the lower level. If any instance of the description is modified, all other instances are also modified. Fractals are examples of recursive definitions.

## Open-ended systems

I use the term "open-ended systems" in the sense that both the procedure itself can be dynamically extended and modified, and the parameters and variables within it can be changed - by their very nature - to generate different and different geometries. If the relationships between the elements in a semilattice are changed, the result will also change significantly. If a single element is changed in a recursive system, the whole system is transformed. The system can also be extended at any time, existing outputs can serve as inputs for new elements, either in a semilattice or in a recursive manner, but most often in a combination of the two. A genuine Gothic building was rarely built in one phase and is never "finished" (in this way it differs from its neo-Gothic counterparts), just as a natural city is never finished (in this way it differs from the "ideal", planned cities of the Renaissance and Modernism).

# Related articles

[The Miskolc Method: Modelling the Evolution of a Natural City with Recursive Algorithms Using Simulated Morphogenesis](https://www.researchgate.net/publication/385077914_The_Miskolc_Method_Modelling_the_Evolution_of_a_Natural_City_with_Recursive_Algorithms_Using_Simulated_Morphogenesis)

[The Procedural Nature of Gothic Architecture and Microarchitecture](https://www.researchgate.net/publication/389574843_The_Procedural_Nature_of_Gothic_Architecture_and_Microarchitecture)