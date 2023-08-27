---
title: "PROC2PDDL: Predicting Domain Definitions Based on Natural Language for Symbolic Planning"
excerpt: ""
collection: portfolio
---

This work explores the causal reasoning of events. It treats causal links as the pre- and post-conditions between actions, represented in the symbolic language. For example, an action 'go' requires (as pre-condition) an 'avatar 1' at 'location 1' and 'location 1' can be connected to 'location 2'; the result is (as post-condition) an 'avatar' at 'location 2'. To implement a sequence of actions, the pre-conditions should be satisfied before executing each action, and the post-conditions will be acquired after the action. 

The core theory of this approach is **tracking the dynamics** of **entities** and **their attributes**, such as 'avatar 1' with attribute 'at location 1' or 'at location 2', in a series of unit actions. We decompose a complicated goal into a bunch of reusable unit actions, e.g. 'go', 'get'. The unit action is viewed as an external method to change the internal states of the entity. Our focus is on the dynamics of entity states.

See our [paper]() and [code]().