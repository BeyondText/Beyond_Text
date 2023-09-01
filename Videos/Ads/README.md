# Ads
## Content
This dataset contains videos separated with different sets of two tags - (non-)exciting ads and (not-)funny ads.
This dataset is a subset from https://people.cs.pitt.edu/~kovashka/ads/ by Hussain, Z., Zhang, M., Zhang, X., Ye, K., Thomas, C., Agha, Z., ... & Kovashka, A. (2017). Automatic understanding of image and video advertisements. In Proceedings of the IEEE conference on computer vision and pattern recognition (pp. 1705-1715).
The downloading codes are attached

To use this dataset, download the repository through the command line.

## How to Use in GCP
1. Upload the videos to GCS Cloud Storage at https://cloud.google.com/storage.
2. A summary.csv file is contained with this dataset along with a test.csv and train.csv. Modify these csv files with the approporiate Cloud Storage file paths.
3. Head to the GCP AutoML Video Classification at https://cloud.google.com/automl and create a new project.
4. Import the videos through the summary.csv file path in Cloud Storage.
5. Run the model with the associated tags.
