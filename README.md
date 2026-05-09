Physics-Informed Meta-Learning for Few-Shot Landslide Forecasting

This project presents a Physics-Informed Meta-Learning (PIML) framework for cross-region landslide prediction in India using few-shot learning and geospatial deep learning techniques.

The framework integrates:

Physics-informed constraints
Model-Agnostic Meta-Learning (MAML)
Spatio-temporal learning
Terrain and rainfall-based feature engineering

The system rapidly adapts to unseen landslide-prone regions using limited labeled samples.

Key Features
Cross-region landslide prediction
Few-shot adaptation for unseen regions
Physics-guided loss functions
DEM-based terrain feature extraction
Temporal rainfall sequence modeling
Comparative evaluation against LSTM, GRU, Fine-Tuning, and MAML baselines
Study Regions
Kerala (Source Region)
Kodagu, Karnataka
Himachal Pradesh
Technologies Used
Python
PyTorch
GeoPandas
Rasterio
NumPy
Scikit-learn
Google Colab

Results
Achieved superior few-shot adaptation performance
Reduced prediction RMSE compared to conventional deep learning baselines
Improved cross-region generalization under data-scarce conditions

Repository Structure
src/        -> Source notebooks and implementation
results/    -> Experimental outputs and visualizations
docs/       -> Research report and documentation
data/       -> Sample datasets
Research Contribution

This work combines physics-informed learning with meta-learning for geospatial disaster forecasting, enabling rapid deployment in new regions with minimal labeled data.

Author
Gaurav Kumar
