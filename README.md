# 🌊 Flood Mapping using Google Alpha Earth Embeddings

This project demonstrates the use of **Google Alpha Earth Embeddings** to identify and map flood events across multiple countries using annual aggregated flood masks.

## 🛰 Overview

The goal was to evaluate the potential of **Alpha Earth’s annual embeddings** in representing flood patterns derived from geospatial datasets.  
To achieve this, we processed flood occurrence data to generate **binary flood masks** and linked them with embedding features for spatial analysis and visualization.

## 🧩 Data and Methodology

### 1. Data Sources
- **STRUM Flood Dataset** – provides high-resolution flood occurrence data.
- **Google Alpha Earth Embeddings (2022)** – provides annually aggregated global geospatial embeddings.

### 2. Processing Steps
1. Scanned flood metadata and occurrence datasets for the selected countries.
2. Generated **annual aggregated flood masks (binary)** from event occurrences.
3. Linked flood masks with **Alpha Earth annual embeddings** (available on a per-year basis).
4. Extracted random **10 km × 10 km** patches (e.g., over **Pakistan, 2022**) for evaluation and visualization.

### 3. Key Constraints
- Alpha Earth embeddings are **available annually**, so flood data had to be **aggregated by year**.
- Mask generation required **binary classification (flooded vs. non-flooded)** for compatibility with embedding layers.

## 🗺 Example Visualization
A random 10 km × 10 km patch over **Pakistan (2022)** was used to visualize flood extent and embedding responses.

<img width="1299" height="428" alt="image" src="https://github.com/user-attachments/assets/95be4f2d-3841-474d-82f8-a3fa87aeb524" />

