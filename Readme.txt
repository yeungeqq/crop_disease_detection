Instructions for Running the Jupyter Notebook

To execute the models in this notebook, please follow the steps below in sequence:

Custom CNN Model
1. Set up the environment and preprocess the data
Run Blocks 1 and 2 to configure the environment and perform data preprocessing.

2. Perform cross-validation
Run Block 3 to conduct stratified k-fold cross-validation for the custom CNN model.

3. Train the custom CNN model
Run Block 4 to build, train, and evaluate the custom CNN model.

--------------------------------------------------------------------------------------------------------------------------------

SVM and Random Forest Models (using ResNet50 feature extraction)
1. Set up the environment and imports
Run Block 5 (optionally rerun Block 1) to import necessary libraries and configure the environment for feature-based models.

2. Extract features using ResNet50
Run Block 6 to resize and batch the images, and then extract image features using the pre-trained ResNet50 model.

3. Cross-validate the SVM model
Run Block 7 to perform stratified k-fold cross-validation for SVM model.

4. Train and evaluate the SVM model
Run Block 8 to train the SVM classifier on the extracted features and evaluate its performance.

5. Cross-validate the RF model
Run Block 9 to perform stratified k-fold cross-validation for RF model.

6. Train and evaluate the Random Forest model
Run block 10 to train the RF classifier on the extracted features and evaluate its performance.