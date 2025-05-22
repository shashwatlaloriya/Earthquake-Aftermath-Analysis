# Automated Building Damage Assessment Using LiDAR Scans
Developed a robust pipeline to align pre- and post-disaster 3D point clouds for automated structural damage
assessment. 
<br>
Using ensemble learning methods (e.g., SVM, XGBoost) to classify severity levels of structural damage based on
extracted geometric features.

# Abstract and Motivation
Rapid and accurate building damage assessment following natural disasters is
critical for effective emergency response and recovery planning. This study presents an
automated methodology that leverages LiDAR point cloud data and ensemble machine
learning to detect and classify collapsed structures in disaster-affected areas. 
<br>
<img src="https://github.com/user-attachments/assets/211e79a1-9d9e-4eb8-b1f6-83f6e7ff634a" alt="Alt Text" width="400" height="200">

The proposed framework processes pre- and post-disaster digital surface models to extract seven key
structural features, including mean height difference, standard deviation, spatial correlation,
and footprint area. Building footprints are identified through height thresholding and
connected component analysis, and an ensemble classifier-integrating Random Forest,
Support Vector Machine, Logistic Regression, and XGBoost algorithms-is trained to
distinguish between collapsed and non-collapsed buildings. 
<br>
<img src="https://github.com/user-attachments/assets/a9bc98b7-bde3-44b6-b062-2d3de3263464" alt="Alt Text" width="800" height="400">

The system incorporates memory-efficient batch processing, enabling scalable analysis of large urban areas.
Experimental results demonstrate that the approach achieves high classification accuracy
and significantly reduces assessment time compared to traditional field surveys. 
<br>
<br>
<img src="https://github.com/user-attachments/assets/94832e53-0024-4f08-9ffc-2991369e8b7c" alt="Alt Text" width="800" height="400">

Visualization tools, such as color-coded damage maps and feature distribution plots, support rapid
interpretation and decision-making for emergency managers. The methodology offers a
robust and efficient solution for post-disaster building damage assessment, with potential for
integration into operational disaster response workflows and extension to various disaster
scenarios.
<br>
<br>
By integrating efficient digital surface model generation, robust feature engineering, and ensemble machine
learning classification, the system provides rapid, scalable, and objective identification of
collapsed structures across large urban areas.
While the approach is limited by the availability of
pre-disaster LiDAR data and a primary focus on vertical structural changes, the results confirm
that automated analysis can substantially reduce assessment time and improve the safety and
effectiveness of disaster response operations.
