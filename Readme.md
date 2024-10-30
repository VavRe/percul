# Persian Cultural Understanding Benchmark for LLMs [Double-Blind]

This repository contains the implementation code for our research paper submitted to NAACL 2025, presenting a comprehensive evaluation framework for assessing Large Language Models' understanding of Persian cultural concepts through story-based multiple-choice questions.

> **Note**: This is a work in progress. The code is being cleaned and organized for better accessibility and reproducibility.

## Project Overview

This research introduces a novel evaluation framework that tests LLMs' understanding of Persian cultural concepts across 11 distinct cultural categories. The evaluation is conducted through culturally-rich stories followed by multiple-choice comprehension questions, providing a nuanced assessment of cultural competency in language models.

## Evaluated Models

### Commercial Models
-
-
-

### Open Source Models
-
-
-

## Key Components

### Annotation User Interfaces
Implemented various streamlit based user interfaces for different rounds of annotation inclusing
- Story Correction / Evaluation
- Distractor Selection
- Seed Topic and Metadata Collection
- Final Human Baseline Evaluation

### Model Serving Infrastructure
- Implementation for serving open-source language models
- Integration with OpenRouter platform for API-based model access
- Unified interface for both open and closed-source model evaluation

### Dynamic Story Generation
- Excel-based seed topic and metadata management
- Category-specific story generation
- Automated story creation pipeline across 11 cultural categories
- Dynamic prompt engineering and configuration

### Distractor Generation
- Automated generation of plausible distractor options
- API-based distractor validation and quality assurance
- Multiple LLM integration for diverse distractor creation

### Evaluation Framework
- Comprehensive benchmarking system for LLM evaluation
- Support for both API-based and open-source models
- Dynamic evaluation pipeline with configurable parameters
- Performance metrics across cultural categories

### Analysis Tools
- Visualization suite for result analysis
- Exploratory data analysis scripts
- Performance comparison across models and categories
- Statistical analysis tools

## Results

### Overall Performance

| Model | Accuracy | Cultural Consistency | Reasoning Score |
|-------|----------|---------------------|-----------------|
| Model 1 | XX.X% | XX.X% | XX.X% |
| Model 2 | XX.X% | XX.X% | XX.X% |
| ... | ... | ... | ... |

### Performance by Cultural Category

| Model | Category 1 | Category 2 | ... | Category 11 | Average |
|-------|------------|------------|-----|-------------|---------|
| Model 1 | XX.X% | XX.X% | ... | XX.X% | XX.X% |
| Model 2 | XX.X% | XX.X% | ... | XX.X% | XX.X% |
| ... | ... | ... | ... | ... | ... |

### Error Analysis

| Model | Cultural Misunderstanding | Logical Error | Context Confusion | Other |
|-------|--------------------------|---------------|-------------------|--------|
| Model 1 | XX.X% | XX.X% | XX.X% | XX.X% |
| Model 2 | XX.X% | XX.X% | XX.X% | XX.X% |
| ... | ... | ... | ... | ... |

## Repository Structure
```
📦 root
 ┣ 📂 model_serving
 │  ┣ 📂 open_source
 │  ┗ 📂 api_integration
 ┣ 📂 story_generation
 │  ┣ 📂 prompts
 │  ┗ 📂 metadata
 ┣ 📂 distractor_generation
 ┣ 📂 evaluation
 ┣ 📂 analysis
 │  ┣ 📂 visualization
 │  ┗ 📂 eda
 ┣ 📂 utils
 ┗ 📂 configs
```

## Setup and Installation
[Coming Soon]

### Prerequisites
- Python 3.8+
- Required GPU specifications for open-source models
- API keys for commercial models

## Usage

### Data Preparation
```bash
# Example commands for preparing seed data
[Coming Soon]
```

### Story Generation
```bash
# Example commands for story generation
[Coming Soon]
```

### Evaluation
```bash
# Example commands for running evaluations
[Coming Soon]
```

## Results Visualization
```bash
# Example commands for generating visualizations
[Coming Soon]
```

## Citation
Please note that citation information will be provided after the double-blind review process.

## License
[Coming Soon]

## Contact
For any questions regarding this repository, please open an issue in the repository's issue tracker.

## Acknowledgments
We thank the reviewers for their valuable feedback. Detailed acknowledgments will be added post-review.