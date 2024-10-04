
### ** K-means Clustering Project**

#### Project Overview:
This project applies **K-means clustering** to neutron interaction data as part of ongoing research to improve neutron detection systems, including the **Next Generation Neutron Detector (NGND)**. The goal is to uncover patterns in the interaction data without prior labels, helping to inform the design of detector arrays and improve resolution.

#### Files:
- `Demo_Kmean_py.ipynb`: Implements the K-means clustering algorithm using **Scikit-learn**. It includes steps for clustering neutron interaction events and visualizing the clusters.

#### How to Run:
1. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
   where `requirements.txt` contains:
   ```
   scikit-learn
   pandas
   numpy
   matplotlib
   seaborn
   ```
2. Launch the notebook:
   ```bash
   jupyter notebook Demo_Kmean_py.ipynb
   ```
3. Follow the notebook steps to load the neutron interaction dataset, apply K-means clustering, and visualize the clusters.

#### Key Features:
- Application of K-means clustering to uncover hidden patterns in neutron interaction data.
- Visualization of clusters using **Matplotlib** and **Seaborn**.
- Analysis of clustering results and their implications for detector array design.

#### Contributors:
- **Raven Mott**: Developed and implemented the K-means clustering model, contributing to the analysis of neutron data and visualization of clustering results. Worked on integrating the findings into the **NGND** project to enhance neutron detection resolution.
-**Thomas Redpath**:PI
-**Facility for Rare Isotope Beams (FRIB)**
