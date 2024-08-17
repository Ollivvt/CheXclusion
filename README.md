# CheXclusion
To examine the extent to which state-of-the-art deep learning classifiers trained to yield diagnostic labels from X-ray images are biased with respect to protected attributes, such as patient sex, age, race, and insurance type as a proxy for socioeconomic status. In particular, we examine the differences in true positive rate (TPR) across different subgroups per attributes. A high TPR disparity indicates that sick members of a protected subgroup would not be given correct diagnoses---e.g., true positives---at the same rate as the general population, even in an algorithm with high overall accuracy. 

## Dataset access:
All three MIMIC-CXR, CheXpert, and ChestX-ray14 datasets used for this work are public under data use agreements. 

- MIMIC-CXR dataset is available at: https://physionet.org/content/mimic-cxr/2.0.0/

- CheXpert dataset is available at: https://stanfordmlgroup.github.io/competitions/chexpert/

- ChestX-ray14 dataset is available at: https://www.nih.gov/news-events/news-releases/nih-clinical-center-provides-one-largest-publicly-available-chest-x-ray-datasets-scientific-community

Access to all three datasets requires user registration and the signing of a data use agreement. Only the MIMIC-CXR dataset requires the completion of an additional credentialing process. After following these procedures, the MIMIC-CXR data is available through PhysioNet (https://physionet.org/). The race/ethnicities and insurance type of the patients are not provided directly with the download of the MIMIC-CXR dataset. However, this data is available through merging the patient IDs in MIMIC-CXR with subject IDs in MIMIC-IV (https://physionet.org/content/mimiciv/0.4/) datasets, using the patient and admissions tables. Access to MIMIC-IV requires a similar procedure as MIMIC-CXR and the same credentialing process is applicable for both datasets. 
