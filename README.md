# BEARING-ONLY-LOCALIZATION-IMPLEMENT
this course is the 1st project assignment from Estimation and Filtering course XJTU

## Project Overview
This project implements a distributed multi-agent system for target localization and pointing control using only bearing measurements, based on the paper "Networked pointing system: Bearing-only target localization and pointing control" by Li et al. The system enables a network of agents to cooperatively estimate a target's position and align their headings toward it, with only two agents having direct bearing measurements to the target.

## Key Features
- Distributed Estimation: Implements a bearing-only estimator that allows all agents to estimate target position

- Pointing Control: Controls agent headings to converge toward the target direction

- Heterogeneous Sensing: Works with both Sensing Agents (direct measurements) and Non-Sensing Agents (communication only)

- Hierarchical Communication: Three-layer topology ensuring information flow

- Convergence Analysis: Monitors estimation and pointing error convergence

## System Architecture
#### Agent Types
- Sensing Agents (SA): 2 agents with direct bearing measurements to target
- Non-Sensing Agents (NSA): 4 agents relying on neighbor communication
