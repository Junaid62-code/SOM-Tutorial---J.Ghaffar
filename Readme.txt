Self-Organizing Maps (SOMs) for Dimensionality Reduction and Visualization

Overview

This project demonstrates the implementation and application of Self-Organizing Maps (SOMs) for dimensionality reduction and visualization of high-dimensional data. It explores how different neighborhood functions affect topology preservation and compares SOMs with t-SNE for dimensionality reduction.

Features

Implementation from Scratch: Includes a custom implementation of SOMs in Python.
Neighborhood Functions: Explores the impact of Gaussian, Mexican Hat, and Bubble neighborhood functions on SOM training and visualization.
Dataset Exploration: Applies SOMs to the Iris dataset and the Olivetti faces dataset to demonstrate their capabilities in dimensionality reduction and visualization.
Comparison with t-SNE: Compares SOMs with t-SNE, a popular dimensionality reduction technique, to highlight their strengths and weaknesses.
Topology Preservation: Demonstrates how SOMs preserve topological relationships in data using a synthetic 3D dataset.
Quality Metrics: Implements and compares topographic error and quantization error to assess the quality of different SOM models.
Parameter Tuning: Investigates the effect of learning rates, neighborhood radii, and map sizes on SOM performance.
Convergence Analysis: Examines the convergence behavior of SOM training using quantization error over iterations.
Weight Adaptation Visualization: Provides visualizations of weight adaptation during training to illustrate how the SOM learns.
Conclusion and Key Findings: Summarizes the key findings from the tutorial and their implications for using SOMs in practice.

 Requirements

- Python 3.x
- NumPy
- Matplotlib
- Pandas
- Scikit-learn
- Seaborn
- tqdm

Usage

1. Install Requirements: Install the necessary libraries using `pip install numpy matplotlib pandas scikit-learn seaborn tqdm`.
2. Execute the Script: Run the Python script in a suitable environment like Jupyter Notebook or Google Colab.
3. Explore and Modify: Experiment with different parameters and datasets to gain a deeper understanding of SOMs.

License

This project is licensed under the MIT License. See the `LICENSE` file for details.

Author

J.Ghaffar

Acknowledgments

- This project was inspired by the work of Teuvo Kohonen, the inventor of Self-Organizing Maps.
- The datasets used in this project are publicly available through scikit-learn.