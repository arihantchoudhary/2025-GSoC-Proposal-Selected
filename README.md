# Google Summer of Code 2025 Proposal

![Screenshot 2025-05-07 at 7 03 19 PM](https://github.com/user-attachments/assets/fb7adce4-5eef-4661-a291-4f663c96a61b)

Update on May 7: Got selected by Google DeepMind for the Gemma project!!!

Update on May 8: Got rejected by two other orgs lol.

I’m planning to make all my proposals public in case anyone’s curious about the GSoC application process.

Here’s what I submitted for DeepMind, without any PRs contributed:

- A proposal
- A demo repo (linked in the proposal)
- A blog post (shared under the [demo] tag in the issue section of the Gemma repo):
https://github.com/google-deepmind/gemma/issues/244

Feel free to reach out — and good luck to anyone applying for the 2026 batch!


This repository contains my proposals and demonstration code for Google Summer of Code 2025.

## I have submitted three project proposals:

1. **Liftover_2D: Fast Chromatin Interaction Coordinate Conversion (Open2C)**
2. **Comprehensive Benchmark Suite for Evaluating Gemma Models (Google DeepMind)**
3. **Improving Support for Drug Formulation (DeepChem)**

## Liftover_2D (Open2C)

### Project Overview

Liftover_2D will develop a fast and effective tool for converting chromatin interaction coordinates between different genome assemblies. As part of the Open2C ecosystem, it will enable researchers to "lift over" Hi-C and other 3C+ contact data without re-mapping raw reads, using existing chain files for coordinate translation. The tool will support both `.pairs` and `.cool` formats, using optimized algorithms that preserve pairwise context while achieving high performance through vectorization and parallelization.

### Key Features

- Fast conversion of coordinate pairs between assemblies
- Support for both `.pairs` (coordinate pairs) and `.cool` (binned matrix) file formats
- Optimized interval-based lookups for coordinate mapping (e.g., O(log n) complexity)
- Robust handling of unmappable regions and coordinate conversion edge cases
- Clean integration with the Open2C ecosystem and its existing toolchain

The implementation is available at: [github.com/heilcheng/liftover_2d](https://github.com/heilcheng/liftover_2d)

## Comprehensive Benchmark Suite for Gemma Models (Google DeepMind)

### Project Overview

This benchmark suite enables researchers and practitioners to systematically evaluate Google's Gemma language models across a variety of tasks. The project has been implemented and is available as an open-source repository.

### Key Features

- Systematic evaluation of Gemma models across standard academic benchmarks
- Comparison between different Gemma model sizes and variants
- Benchmarking against other open models like Llama 2 and Mistral
- Generation of informative visualizations for easy interpretation
- Automation of the benchmarking process with reproducible scripts
- Statistical validation of observed performance differences

### Implementation

The benchmark suite is structured with a modular architecture:
- Core framework for loading models and datasets
- Task-specific implementations (MMLU, coding, math reasoning, etc.)
- Efficiency evaluation modules for measuring latency and memory usage
- Visualization components for generating charts and reports

The implementation is available at: [github.com/heilcheng/gemma-benchmark](https://github.com/heilcheng/gemma-benchmark)

## Improving Support for Drug Formulation (DeepChem)

### Project Overview

This project aims to develop comprehensive tutorials and examples for using DeepChem in drug formulation tasks. The tutorials will guide users through loading relevant datasets (ESOL, Lipophilicity, Tox21, BBBP), featurizing molecular data, training models, and visualizing results to aid formulation decisions.

### Proposed Tutorials

- Loading and visualizing molecular datasets relevant to drug formulation
- Training models for solubility, lipophilicity, toxicity, and blood-brain barrier permeability prediction
- Evaluating model performance with appropriate metrics
- Interpreting results in the context of drug formulation decisions
- Demonstrating how computational predictions can reduce costly trial-and-error in formulation research

The implementation is available at: [github.com/heilcheng/pharma-pred](https://github.com/heilcheng/pharma-pred)

*These proposals are submitted for Google Summer of Code 2025.*
