# HDI Estimation Using Satellite Imagery and Convolutional Neural Networks

**Research Publication:**  
Estimating Global Subnational HDI Using Satellite Imagery and Convolutional Neural Networks  
🔗 https://nhsjs.com/2023/estimating-global-subnational-hdi-using-satellite-imagery-and-convolutional-neural-networks/

---

## Overview
The **Human Development Index (HDI)** is a multidimensional metric used to quantify human well-being and development across countries and subnational regions. Traditionally, HDI relies on survey-based and government-reported statistics, which can be expensive, slow to collect, or unavailable for many regions.

This project explores an alternative, data-driven approach: **estimating subnational HDI using satellite imagery and population data**. The core intuition is simple but powerful:

- Regions with **high nighttime luminosity and low population density** tend to be more developed.
- Regions with **low nighttime luminosity and high population density** tend to be less developed.

By combining these signals, the model learns visual and demographic patterns correlated with human development.

---

## Methodology
- Built a **multimodal convolutional neural network (CNN)** that jointly processes satellite imagery and population data
- Trained the model to predict **subnational HDI scores** across diverse global regions
- Focused on scalability and reproducibility using globally available datasets

---

## Data Sources
- **Nighttime Satellite Imagery:** NASA Black Marble
- **Population Data:** NASA SEDAC Gridded Population of the World

Both datasets are globally consistent and publicly available, enabling HDI estimation in regions where traditional data collection is limited.

---

## Implementation
- Frameworks: **TensorFlow, Keras**
- Data processing and preprocessing:
  - Python
  - Pandas
  - NumPy
  - Pillow (PIL)

Custom pipelines were developed to align satellite imagery and population grids spatially and temporally before model training.

---

## Results
- **Mean Absolute Error (MAE):** **0.0945 HDI points**

The results demonstrate that satellite-derived features can serve as strong proxies for human development indicators at the subnational level.

---

## Key Takeaways
- Satellite imagery can meaningfully capture socioeconomic patterns
- Multimodal deep learning is effective for development-related prediction tasks
- This approach enables **low-cost, scalable HDI estimation** for data-scarce regions

---

## Citation
If you use or reference this work, please cite the associated research publication linked above.

