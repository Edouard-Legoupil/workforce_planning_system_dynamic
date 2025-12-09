# System Dynamics for Workforce Planning

This notebook demonstrates the system dynamics approach to workforce planning 

You can consult the notebook [here](https://edouard-legoupil.github.io/workforce_planning_system_dynamic/) or listen to an [intro podcast here](https://github.com/Edouard-Legoupil/workforce_planning_system_dynamic/raw/refs/heads/main/Workforce%20Reduction_%20System%20Dynamics%20for%20HR%20Strategy.wav)


This accounts for:


## Feedback Loops Modeled:

 * Burnout-Attrition Loop: Increased workload → higher attrition → more burnout

 * Skill Erosion Loop: Reduced hiring → aging workforce → future capability gaps

## Realistic Workforce Categories:

 * Senior (experience carriers, high productivity)

 * Mid (core performers, balanced)

 * Junior (future pipeline, higher training needs)

## Two Strategic Approaches:

 * Across-the-board cuts: Uniform reduction leading to skill erosion

 * Strategic protection: Preserve critical talent while cutting non-core areas

## Dynamic Factors Modeled:

 * Morale impact on attrition

 * Workload non-linear increases

 * Experience/skill transfer between levels

## Executive Insights Provided:

 * Cost Trajectory: Shows how initial savings can be eroded by increased attrition costs

 * Productivity Impact: Quantifies the hidden productivity loss from uniform cuts

 * Skill Erosion: Measures organizational knowledge drain over time

 * Attrition Spiral: Demonstrates the compounding effect of burnout

 * Visual Dashboard: Comparative charts showing 5-year outcomes



To Run:

```bash
# Create virtual environment with Python 3.12
uv venv --python 3.12

# Activate virtual environment
source .venv/bin/activate

# Install dependencies
uv pip install -r requirements.txt  
quarto index.qmd
```

