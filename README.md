# A Minimal Workflow for Interactive Geospatial ML Mapping

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Akramz/flexible_geospatial_mapping/blob/main/end2end_geospatial_ml_mapping.ipynb)                                                        

### Workshop Material for [AMLD Africa](https://appliedmldays.org/events/amld-africa-2024)

<div style="text-align:center"><a href="https://appliedmldays.org/"><img style="width:100%" src="static/AMLD_banner.png"></a></div>

## Getting Started

You can run the main notebook from [Colab](https://colab.research.google.com/github/Akramz/flexible_geospatial_mapping/blob/main/end2end_geospatial_ml_mapping.ipynb), or set up the repo locally:

```bash
git clone git@github.com:Akramz/flexible_geospatial_mapping.git
cd flexible_geospatial_mapping
mamba create -n mapping python=3.10
conda activate mapping
pip install -r requirements.txt 
jupyter lab
```

## Q/A

### What do we want to solve?

- Map an object of interest in satellite imagery.
- Use as little resources as possible by focusing on: **open-source software**, **1-or-no GPU**, **publicly available satellite data**.
- Go from no imagery/labels to vectorized predictions over the region of interest in a **single notebook run**.

### Why is this Problem interesting?

Similar workflows can accelerate ML-assisted geospatial mapping by minimizing potential costs & adopting the best conventions.

### How can I contribute?

You can join our community [here](https://docs.google.com/forms/d/e/1FAIpQLScccNYYM5T3CoSAXMyJZCtcpUH7qw1kZ_1IZUQV29IwjRPUOA/viewform).
