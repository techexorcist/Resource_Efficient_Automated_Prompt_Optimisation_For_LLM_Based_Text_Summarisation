# Resource Efficient Automated Prompt Optimisation For LLM-Based Text Summarisation

This repository contains the complete implementation and analysis for a thesis project focused on developing resource-efficient automated prompt optimization techniques for large language model-based text summarization.

## Project Overview

The project investigates methods to optimize prompts for text summarization tasks while maintaining cost efficiency and performance quality. It implements a 5-stage experimental pipeline to systematically develop, test, and validate prompt optimization strategies.

## Repository Structure

### Core Notebooks
- `thesis_notebooks/Stage-1/01_dataset_analysis_eda.ipynb` - Dataset analysis and exploratory data analysis
- `thesis_notebooks/Stage-2/02_base_prompt_development.ipynb` - Base prompt development and initial testing
- `thesis_notebooks/Stage-3/03_prompt_variation_generation.ipynb` - Prompt variation generation strategies
- `thesis_notebooks/Stage-4/04_optimization_experiments.ipynb` - Optimization experiments and analysis
- `thesis_notebooks/Stage-5/05_validation_and_final_testing_anthropic.ipynb` - Final validation and testing

### Output Data
- `thesis_output_run/` - Contains comprehensive experimental outputs organized by stages:
  - `01_stage_output_anthropic_full/` - Dataset processing and EDA results
  - `02_stage_output_anthropic_full/` - Base prompt development outputs
  - `03_stage_output_anthropic_full/` - Prompt variation generation results
  - `04_stage_output_anthropic_full/` - Optimization experiment data
  - `05_stage_output_anthropic_full/` - Final validation results

### Datasets
- `datasets/` - Source datasets used for the experiments
- Each stage output includes processed datasets and subsets used for specific experiments

## Key Features

- **5-Stage Pipeline**: Systematic approach from dataset analysis to final validation
- **Cost-Efficiency Focus**: Emphasis on resource-efficient prompt optimization
- **Comprehensive Analysis**: Detailed performance metrics, cost analysis, and statistical validation
- **Reproducible Results**: Complete experimental outputs and checkpoints
- **Visual Analytics**: Extensive visualization outputs for analysis and presentation

## Experimental Stages

1. **Stage 1**: Dataset Analysis & EDA
2. **Stage 2**: Base Prompt Development
3. **Stage 3**: Prompt Variation Generation
4. **Stage 4**: Optimization Experiments
5. **Stage 5**: Validation & Final Testing

## Results

The project demonstrates effective prompt optimization techniques that balance performance quality with computational cost efficiency. Detailed results, visualizations, and analysis are available in the respective stage output directories.

## Usage

Each notebook is self-contained and can be run independently, though they build upon results from previous stages. The output directories contain all generated data, allowing for analysis without re-running expensive API calls.

## Dependencies

- Python 3.x
- Jupyter Notebook
- Various ML/NLP libraries (see individual notebooks for specific requirements)
- Anthropic API access (for replication)

---

*This project represents research into resource-efficient automated prompt optimization for LLM-based text summarization tasks.*