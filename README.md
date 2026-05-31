# lerobot-learning

A first-principles engineering log and experimental sandbox for end-to-end robot learning, policy training, and simulation using LeRobot.

## The Objective

The goal of this repository is to deconstruct and master the paradigm shift happening in robotics: Physical AI and End-to-End (E2E) Learning.

Instead of building traditional, highly fragmented robotics pipelines—where perception, planning, and control operate in isolated, brittle silos—this space focuses on training unified neural network policies (like Diffusion Policies and Action Chunking Transformers) that map raw sensor inputs directly to motor actions.

I am treating this repository as a structured "Second Brain" to document my engineering notes, track experimental processes, analyze training outcomes, and bridge the gap between simulation and real-world execution.
Key Focus Areas:

- Pipeline Mastery: Implementing the complete data-to-deployment loop—from dataset ingestion/teleoperation to policy training and inference.
- Algorithm Intuition: Deep-diving into imitation learning architectures (ACT, Diffusion, VLA) to understand the mathematics and mechanics behind behavioral cloning.
- Rigorous Tracking: Treating every training run as a scientific experiment, documenting hyperparameters, failure modes, and evaluation benchmarks.
- Framework Exploration: Leveraging the Hugging Face lerobot ecosystem to build scalable, reproducible robotics environments.

## How to Navigate This Repo

    /configs: Custom training configurations and hyperparameter overrides.

    /experiments: My complete logbook. Each subdirectory contains the exact execution script, and a post-mortem summary of the training run.

    /src: Custom utility scripts for dataset visualization, environment management, and eventual hardware interfaces.