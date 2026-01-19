# embeddings_in_TorchGeo
## Tutorial on how to implement a TorchGeo notebook with embeddings

The goal of this project is to develop a representation learning pipeline for crop monitoring. Instead of building a simple "black-box" classifier, we are focusing on **embedding generation**, transforming complex satellite time-series data into a low-dimensional, meaningful vector space.

**Key Objectives:**
* **Time-Series Embeddings:** Use `TorchGeo` enconders to compress temporal and spectral data into a 1D feature vector.
* **Binary Classification Focus:** To maximize data density and global applicability, we are focusing on the binary classification (crop vs. non crop) using the *GeoWiki-landcover-2017* sub-dataset.
* **Feature Extraction:** Leveraging the latent space of a model to distinguish agricultural patterns from natural land covers and analyse if different geographical locations produce similar embeddings for the same land class.

**Environment:**

On the terminal just run:
```
uv sync
```

