# A Flexible Workflow for Interactive Geospatial Mapping

### What do you want to solve?

- Conducting ML-assisted geospatial mapping starting with no labels require a lot of effort.
- **Steps**: image acquisition, image preparation/preprocessing, setting up a labeling environment & budget, preparing a compute environment, and finally training a deep learning model.
- The required resources makes it difficult to use deep learning models in regions where it is needed most, especially in Africa.

### Why this is an interesting problem?
The need for accelerating such workflows using open-source software, publicly available satellite imagery, and free compute is essential in low-resource environments.

### What do we want to achieve?
In this session, we aim to showcase an end-to-end workflow for mapping objects in satellite imagery using publicly available resources with minimal costs on the user.

### What follows from the workflow?
You can adapt & customize the workflow to your needs. You can build on it to make it easier to be used to empower geospatial machine learning applications in the continent.

## Getting Started

You can run the notebook from [Colab](https://colab.research.google.com/github/Akramz/flexible_geospatial_mapping/blob/main/flexible_workflow_for_geospatial_mapping.ipynb), or set up the repo locally:

```bash
git clone git@github.com:Akramz/flexible_geospatial_mapping.git
cd flexible_geospatial_mapping
mamba create -n mapping python=3.10
conda activate mapping
pip install -r requirements.txt 
jupyter notebook
```
