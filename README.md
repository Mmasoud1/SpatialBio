# SpatialBio  [![Version](https://img.shields.io/badge/Version-0.1.0-brightgreen)]() [![MIT-License ](https://img.shields.io/badge/license-MIT-green)](https://github.com/Mmasoud1/MeshFL/blob/main/LICENSE) [![Python](https://img.shields.io/badge/Python-blue)]() 

Concise spatial biology workflows for spatial transcriptomics, multiplex imaging, and multimodal biomedical analysis.

it explores modern spatial omics workflows using the scverse ecosystem and extends toward AI-assisted biological analytics, multimodal data integration, and foundation-model exploration.


## Interactive Notebooks

### Spatial Transcriptomics Workflow

[Notebook](notebooks/SpatialBio_Transcriptomics_workflow.ipynb), [Open in Colab](https://colab.research.google.com/github/Mmasoud1/SpatialBio/blob/main/notebooks/SpatialBio_Transcriptomics_workflow.ipynb)

Demonstrates:

- Visium spatial transcriptomics preprocessing
- Quality control (QC)
- Highly variable gene selection
- UMAP visualization
- Leiden clustering
- Marker gene discovery
- Differential expression analysis
- Spatial autocorrelation (Moran's I)



### AnnData Copilot

[Notebook](notebooks/ai_assistant/anndata_copilot.ipynb), [Open in Colab](https://colab.research.google.com/github/Mmasoud1/SpatialBio/blob/main/notebooks/ai_assistant/anndata_copilot.ipynb)

Demonstrates:

- LLM-assisted biological analytics
- Marker gene interpretation
- Cluster summarization
- Natural-language exploration of AnnData objects
- Spatial transcriptomics result interpretation


### Foundation Model Morphology Embeddings for Visium

[Notebook](notebooks/foundation_models/01_visium_dinov2_foundation_embeddings_demo.ipynb), [Open in Colab](https://colab.research.google.com/github/Mmasoud1/SpatialBio/blob/main/notebooks/foundation_models/01_visium_dinov2_foundation_embeddings_demo.ipynb)

Demonstrates:

- H&E patch extraction around Visium spots
- DINOv2 image embeddings
- Foundation-model-based morphology representation
- Morphology–transcriptomics integration
- UMAP visualization of image embeddings
- Comparison of morphology clusters with transcriptomic Leiden clusters


### Foundation Model Comparison

[Notebook](notebooks/foundation_models/02_visium_foundation_models_comparison.ipynb), [Open in Colab](https://colab.research.google.com/github/Mmasoud1/SpatialBio/blob/main/notebooks/foundation_models/02_visium_foundation_models_comparison.ipynb)

Demonstrates:

DINOv2
PLIP
UNI
CONCH
Virchow 

Comparison metrics:

ARI
NMI
Cluster visualization
Morphology–transcriptomics agreement


### Biological Annotation

[Notebook](notebooks/biological_annotation/03_visium_biological_annotation.ipynb), [Open in Colab](https://colab.research.google.com/github/Mmasoud1/SpatialBio/blob/main/notebooks/biological_annotation/03_visium_biological_annotation.ipynb)

Demonstrates:

Identify transcriptomic regions
Annotate tissue compartments


### Dataset

This repository uses the 10x Genomics dataset, license: **CC BY 4.0**

## Quick Start

```bash
pip install -r requirements.txt
jupyter lab notebooks/spatialbio_transcriptomics_workflow.ipynb
