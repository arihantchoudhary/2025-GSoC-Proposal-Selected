# Google Summer of Code 2025 Proposal for Google DeepMind

My blog on Medium:

(How I Landed a Google DeepMind Project in Google Summer of Code 2025: A Step-by-Step Guide)

https://medium.com/@heilcheng2-c/how-i-landed-a-google-deepmind-project-in-google-summer-of-code-2025-a-step-by-step-guide-ccb2dee66769

Update on May 7: Got selected by Google DeepMind for the Gemma project!

Update on May 8: Got rejected by two other orgs lol.

I’m planning to make all my proposals public in case anyone’s curious about the GSoC application process.

Here’s what I submitted for DeepMind:

- A proposal
- A demo repo
- A blog post (shared under the [demo] tag in the issue section of the Gemma repo):
https://github.com/google-deepmind/gemma/issues/244

Feel free to reach out. And good luck to anyone applying for the 2026 batch!


## Comprehensive Benchmark Suite for Gemma Models 

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
