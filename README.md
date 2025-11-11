# 🌊 Flood Mapping using Google Alpha Earth Embeddings

⚠️ This repository is currently under construction and serves only as a workspace for uploading Python and notebook files — not a finalized presentation or release.

This project demonstrates the use of **Google Alpha Earth Embeddings** to identify and map flood events across multiple countries using annual aggregated flood masks.

## 🛰 Overview

The goal was to evaluate the potential of **Alpha Earth’s annual embeddings** in representing flood patterns derived from geospatial datasets.  
To achieve this, we processed flood occurrence data to generate **binary flood masks** and linked them with embedding features for spatial analysis and visualization.

<img width="1229" height="430" alt="image" src="https://github.com/user-attachments/assets/e53d298c-0540-42bd-8b1e-3e487a29a0e7" />


## 🧩 Data and Methodology

### 1. Data Sources
- **STRUM Flood Dataset** – provides high-resolution flood occurrence data.
- **Google Alpha Earth Embeddings (2022)** – provides annually aggregated global geospatial embeddings.
  <img width="1351" height="400" alt="image" src="https://github.com/user-attachments/assets/a69a502a-6575-4699-bcc2-1ed21d34987b" />

  <img width="934" height="574" alt="image" src="https://github.com/user-attachments/assets/7d0d4e79-f36b-484e-8b1d-3c331a8a05c5" />



### 2. Processing Steps
1. Scanned flood metadata and occurrence datasets for the selected countries.
2. Generated **annual aggregated flood masks (binary)** from event occurrences.
3. Linked flood masks with **Alpha Earth annual embeddings** (available on a per-year basis).
4. Extracted random **10 km × 10 km** patches (e.g., over **Pakistan, 2022**) for evaluation and visualization.




## 🗺 Example Visualization

<img width="1299" height="428" alt="image" src="https://github.com/user-attachments/assets/95be4f2d-3841-474d-82f8-a3fa87aeb524" />

