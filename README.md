# ML4CV---Assignment
This repository contains the assignment for the course of Machine Learning for Computer Vision at the University of Bologna
The notebook has been created using Kaggle. All the model training and evaluation have been done with the Kaggle GPU P100.
To ensure reproducibility please upload the notebook on Kaggle, connect to GPU P100 and run the notebook. Please, ensure that on your Kaggle notebook internet connection is enabled.
## Dataset and Data
Kaggle is fully cloud-based. Your local machine and the Kaggle server don’t share a file system, this implies that all the files need to be dinamically downloaded during the notebook execution, or manually added, this creates 2 consequences:
- The StreetHazards dataset has been directly downloaded from the Berkley university link in the first line of code, using wget.
- The model weights, the results directory containing all the evaluation results and the logs directory containing the logs run have been updated on the institutional One Drive, as required. But, One Drive only allows to share the link with those belonging to your institutional group (Unibo, in this case), and this blocks the download directly from Kaggle. To solve this inconvinient i have uploaded them inside my personal Google Drive. Link to the files:
  - the institutional OneDrive: https://liveunibo-my.sharepoint.com/:f:/g/personal/christian_dibuo_studio_unibo_it/EvnP2sxQoNRJqYqPF8YAg-UB37yXA_FhtvWtGmyauVuO8w?e=gTPSuf
  - my personal Google Drive: [https://drive.google.com/file/d/1zhLDGyPBT4HmJl6q6TRA0CsmFTMQ7Gzc/view?usp=sharing](https://drive.google.com/file/d/1zhLDGyPBT4HmJl6q6TRA0CsmFTMQ7Gzc/view?usp=sharing)
  
Uploding the files in my personal Google Drive allows me, using the gdown command in the first notebook's code cells, to create an automatic script, which is not influenced by the limitation of institutional One Drive. In this way the links are already inside the notebook, and nothing of the nootebook needs to be manually updated or modified. This makes the notebook completly reproducible.
