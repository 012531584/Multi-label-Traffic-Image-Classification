Due to the large size of the dataset, it has been posted on the CLP web server. 
Please download the dataset from: https://coe-cmp.sjsu.edu/clp/static/datasets/traffic.tar.gz


Data Description:

The training dataset consists of 100,000 records and the test dataset also consists of 100,000 records. We provide you with the training class labels and the test labels are held out. We have included a small subset of the data in the traffic-small dataset which you may use to practice your codes locally. However, we recommend you use the HPC for the final computation on the traffic dataset. Note that the dataset file is very large (474 MB, expands to 1050 MB). Ensure you have enough space on your drive before expanding the file. Moreover, you will need to think carefully about how you will organize computations so you do not run out of RAM during training.

The dataset file contains two dataset directories: traffic, and traffic-small. In each directory, you will find train and test sub-directories with images numbered 1 to 100,000 (e.g., 000001.jpg) for the traffic dataset and 1 to 4209 for the traffic-small dataset. The train and test sets contain the same number of images. The image ID for the ith image corresponds to the label on the ith line of the train.labels file found in the main dataset directory. The traffic-small dataset contains a test.labels file, but the traffic dataset does not. Your task is to predict those labels for the images in the test set and create a test.txt file containing those labels, which you will submit to CLP. Note that CLP only accepts files with extensions .txt or .dat.
