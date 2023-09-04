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

## Downloading LFS MP4 Files from This Repository
This guide provides steps on how to download MP4 files stored with Git Large File Storage (LFS) from this GitHub repository.

## Prerequisites
Git installed on your local machine. If not, install it from here.
Git LFS installed on your local machine. If not, install it from here.
## Steps
Step 1: Clone the Repository
To clone the repository and download the LFS files, execute the following command in your terminal or command prompt:
bash
git lfs clone https://github.com/BeyondText/Beyond_Text/tree/master/Videos/Ads.git

Step 2: Navigate to the Ads Folder:
Once the repository is cloned, navigate to the interested folder.

Step 3: Pull LFS Files:
If for some reason the LFS files have not been downloaded, navigate to the cloned repository directory in your terminal and run:
git lfs pull
