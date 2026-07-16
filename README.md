<img width="539" height="385" alt="RECNET" src="https://github.com/user-attachments/assets/9a701b79-614a-4ceb-9448-2e0d461a7725" />
Intelligent larval zebrafish phenotype recognition via attention mechanism for high-throughput screening

Background: Larval zebrafish phenotypes serve as critical research indicators in fields such as ecotoxicology and 
safety assessment since phenotypic defects are closely related to alterations of underlying pathway. However, 
identifying these defects is time-consuming and requires specialized knowledge.
Method: We proposed a deep network model called RECNet, which combines attention mechanisms and residual 
structures. In terms of data processing, we applied the mixup data augmentation technique and accumulated a 
collection of 6805 larval zebrafish phenotype images, mostly generated from our laboratory. Our proposed model 
was deployed to execute two distinct tasks, including a four-classification of zebrafish phenotypes and a seven- 
classification involving mixed labels for abnormalities.
Results: In the four-class classification task, the RECNet model achieved an accuracy of 0.949, with a mean area 
under the curve of 0.986 and an F1-score of 0.966. Through interpretable research, attention mechanisms enable 
the model to focus more accurately on regions of interest. In the mixed-label seven-classification task for 
anomalies, our model achieved an accuracy of 0.913 and a mean average precision value of 0.847 by employing 
the weighted loss function (DFBLoss). Furthermore, in a new test dataset, the RECNet model achieved accuracy 
rates of 0.924 and 0.876 for the two tasks, respectively. Our RECNet model was trained by orders of magnitude 
larger dataset than previous studies and also showed better accuracy rates.
Conclusions: Our method holds promise for diverse applications within zebrafish laboratories and fields such as 
toxicology, providing indispensable support to scientific research.
