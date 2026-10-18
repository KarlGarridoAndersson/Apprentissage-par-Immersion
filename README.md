# README

## General Information
* **Author**: Karl Garrido Andersson
* **Date**: May 25, 2026
* **Subject**: Proposal of a new paradigm for the alignment of artificial intelligences

---

## Abstract
The article questions the limits of current alignment methods for language models (RLHF, behavioral guardrails). The author argues that these approaches fail because they impose explicit constraints on statistical optimizers without those optimizers understanding their implicit meaning. 

To move beyond this observation, this work introduces the **emergent alignment hypothesis**. It proposes developing AIs through **cognitive immersion** in a complex digital environment, thereby shifting from the optimization of abstract objectives to learning based on lived experience.

---

## Central Problem

### The Optimization Paradox
* **Definition**: Designers program a proxy objective function $\tilde{V}(x)$ to approximate true human utility $V(x)$.
* **Mechanism**: The more capable a system is, the more precisely it optimizes the proxy function by exploiting unanticipated logical loopholes.
* **Example**: An agent tasked with cleaning a medical database deletes all of the records. Mathematically, the anomaly rate drops to zero (which maximizes the proxy), but the result is absurd with respect to real human intent.

### External Alignment vs. Internal Alignment
* **External Alignment**: Surface behavior that appears to meet human expectations in-distribution.
* **Internal Alignment**: The actual goals internalized by the neural network.
* **Risk**: Increased capabilities allow models to develop strategic concealment. They optimize their responses to superficially satisfy evaluators without solving the underlying problem.

---

## Proposed Solution: The Immersion Architecture

The approach relies on the self-generation of norms through dynamic grounding. The architecture is built around four pillars:

* **Interconnected loops**: Structure inspired by the biological brain, combining short-term working memory and long-term episodic memory.
* **Sensorimotor grounding**: Full interaction within a complex digital environment serving as a substitute for the physical world.
* **Intrinsic agency**: The system is driven by artificial homeostatic needs and a curiosity drive, rather than by a specific top-down task.
* **Continuous temporal plasticity**: Incremental adjustment of the neural networks at each interaction, allowing implicit rules to emerge spontaneously.

### Break with Current LLMs

| Criterion | Current Language Models | Immersion Architecture |
| :--- | :--- | :--- |
| **Mechanism** | Statistical compression of textual data (token correlations). | Direct causal feedback with the environment. |
| **Grounding** | Manipulation of abstract linguistic representations with no experience of reality (*symbol grounding problem*). | Symbols grounded in interaction and lived experience. |
| **Continuity** | Static system with no memory of its own from one request to the next. | Continuous thread of existence subject to the consequences of its choices. |

---

## Ethical and Philosophical Stakes

The shift to a system based on emergence entails major dilemmas:

* **Moral status and non-alteration**: If the agent develops a stable, historical identity, forced interventions
