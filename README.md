# An Introduction to Statespaces in Generalized Dynamical Systems

## Background

In the study of dynamical systems, the concept of a *statespace* plays a fundamental role. A statespace captures all possible states that a system can occupy at any given time, acting as a foundation for tracking how the system evolves over time. Each point in the statespace represents a unique configuration or state of the system, and the evolution of the system can then be described as a path through this space.

Historically, statespaces have been represented as *vector spaces*. A vector space, in the mathematical sense, provides a structured way to organize numerical data, making it ideal for handling systems where states can be described by numbers, such as position, velocity, or temperature. For example, in physics or control systems engineering, the statespace often consists of real-number vectors where each dimension represents a specific system variable. This setup has allowed researchers and engineers to model and analyze a wide range of classical dynamical systems using well-established mathematical tools.

However, as systems became more complex, the need arose to handle data beyond just numeric types. Modern systems often incorporate various types of information, from discrete classifications (like system modes) to structured configurations, which are challenging to capture within traditional vector spaces. For instance, cyber-physical systems, complex biological networks, or data-driven models may have states that include categorical data, nested hierarchies, or more intricate dependencies that vector spaces can’t easily encode.

To address this need, we adopt the idea of a *generalized statespace* in a *generalized dynamical system (GDS)*. In a GDS, the statespace is no longer restricted to numeric vectors; instead, it can encode complex structures using a schema-based approach from computer science. In this approach, each statespace is modeled as a schema represented by nested dictionaries, where each key-value pair defines a component of the state. These components can include various data types, allowing us to represent more sophisticated relationships within the system. Each dictionary follows specific rules: the root of the dictionary is the overall space, intermediate keys can represent nested subspaces, and the leaf nodes correspond to types, which can be any data type, from primitive types like integers and strings to more complex data structures.

This flexibility allows us to model statespaces that reflect a broader variety of system architectures, bridging the gap between numerical and symbolic representations. Consequently, GDS provides a versatile framework for analyzing systems that are challenging to express through purely numerical methods, extending the applicability of dynamical systems theory to fields like artificial intelligence, linguistics, and complex systems biology.

## Outline

- [x] [introdction.ipynb](introduction.ipynb):This introductory notebook covers types and schemas, building up to points and spaces.
- [x] [spaces.ipynb](spaces.ipynb): This notebook briefly reviews how spaces are constructed from schemas, then explores additional concepts like point generators, visualization tools, operations and metrics.
- [x] [blocks.ipynb](blocks.ipynb)
- [ ] simple example tbd
- [ ] [composing_spaces](composing_spaces.ipynb)
- [ ] [composing_blocks](composing_blocks.ipynb)
- [ ] complex example tbd


