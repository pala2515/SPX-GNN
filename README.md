# SPX-GNN

SPX-GNN: An Explainable Graph Neural Network for Harnessing Long-Range Dependencies in Tuberculosis Classifications in Chest X-Ray Images

<img width="2711" height="4078" alt="diagnostics-15-03236-g001" src="https://github.com/user-attachments/assets/14621bf9-0497-4780-b738-4a550105f7e2" />


If you use this repository or find our work helpful in your research, please cite the following paper:

Pala, M. A., & Navdar, M. B. (2025). SPX-GNN: An Explainable Graph Neural Network for Harnessing Long-Range Dependencies in Tuberculosis Classifications in Chest X-Ray Images. Diagnostics, 15(24), 3236. 
https://doi.org/10.3390/diagnostics15243236


Abstract
Background/Objectives: Traditional medical image analysis methods often suffer from locality bias, limiting their ability to model long-range contextual relationships between spatially distributed anatomical structures. To overcome this challenge, this study proposes SPX-GNN (Superpixel Explainable Graph Neural Network). This novel method reformulates image analysis as a structural graph learning problem, capturing both local anomalies and global topological patterns in a holistic manner. Methods: The proposed framework decomposes images into semantically coherent superpixel regions, converting them into graph nodes that preserve topological relationships. Each node is enriched with a comprehensive feature vector encoding complementary diagnostic clues, including colour (CIELAB), texture (LBP and Haralick), shape (Hu moments), and spatial location. A Graph Neural Network is then employed to learn the relational dependencies between these enriched nodes. The method was rigorously evaluated using 5-fold stratified cross-validation on a public dataset comprising 4200 chest X-ray images. Results: SPX-GNN demonstrated exceptional performance in tuberculosis classification, achieving a mean accuracy of 99.82%, an F1-score of 99.45%, and a ROC-AUC of 100.00%. Furthermore, an integrated Explainable Artificial Intelligence module addresses the black box problem by generating semantic importance maps, which illuminate the decision mechanism and enhance clinical reliability. Conclusions: SPX-GNN offers a novel approach that successfully combines high diagnostic accuracy with methodological transparency. By providing a robust and interpretable workflow, this study presents a promising solution for medical imaging tasks where structural information is critical, paving the way for more reliable clinical decision support systems.
Keywords: graph neural networks; explainable AI; tuberculosis; deep learning; medical image

