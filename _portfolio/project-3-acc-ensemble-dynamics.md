---
title: "Neural Population Dynamics Structured by Strategy Prevalence"
excerpt: "By analyzing ACC population activity across behavioral sessions, we found that neural ensemble geometry reflects not just current behavior, but the distribution of strategies an animal relies on — a form of implicit knowledge encoding."
collection: portfolio
---

**Related publication:** [Proskurin, Manakov & Karpova (2023), *eLife*, 12:e84897](https://doi.org/10.7554/eLife.84897)

## Overview

How does the brain encode knowledge about *which behaviors work*? Beyond tracking immediate outcomes, the prefrontal cortex may maintain an internal model of the behavioral landscape — representing the relative value and prevalence of different strategies.

In this project, I analyzed large-scale neural population recordings from the anterior cingulate cortex (ACC) while rats performed a task requiring flexible use of multiple strategies. The key question: does the structure of ACC population dynamics reflect the animal's learned behavioral repertoire?

## Key Findings

- ACC neural population activity organizes into **low-dimensional trajectories** that are structured by the *prevalence* of behavioral strategies — not just by current choice or recent outcome.
- Animals that rely more heavily on certain strategies show correspondingly **larger neural representations** of those strategies in ACC population space.
- This structure **emerges gradually** with experience and persists across behavioral sessions, consistent with a learned, stable representation.
- The geometry of neural dynamics predicts **future behavioral choices**, suggesting that population-level state carries actionable information about the animal's behavioral policy.

## Methods & Tools

- High-density silicon probe recordings (Neuropixels)
- Dimensionality reduction (PCA, UMAP, GPFA)
- Hidden Markov Models for behavioral segmentation
- Custom Python analysis pipeline

## Significance

This work introduced the idea that ACC neural geometry serves as a substrate for encoding abstract, statistical knowledge about behavior — not just moment-to-moment decisions. It provides a bridge between systems-level neural dynamics and computational models of reinforcement learning and cognitive control.
