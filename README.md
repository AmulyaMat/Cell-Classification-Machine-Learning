# Developing AI model for cell status classification using Raman Spectrum Data

**Background:** Cell therapy has emerged as a widely explored solution in regenerative medicine to cure specific diseases without pharmaceuticals. The process involves transferring autologous or allogenic cellular material to a patient to treat diseases by restoring lost tissue functions and enhancing growth. Given the demanding requirements for cell therapy, monitoring the performance of cryopreservation through cell viability has become a priority. Convetional methods include LIVE/DEAD cell asasay, which is invasive and causes cell death. Eliminating these destructive effects, Raman spectroscopy has become popular in the biopharmaceutical industry for its real-time, in-situ, rapid detection of molecules' chemical and physical properties.

**Turning point:** Broadening the scope of Raman spectroscopy, **machine-learning-aided chemometrics** has remarkably demonstrated its capabilities in extracting critical information from the complex Raman spectra to provide a complete chemical interpretation of the samples. 

**Objective:** Considering the prospects of machine learning in this field, the project explores its capabilities in the 3 following purposes: 
1. Construct machine learning and deep learning models to classify different cells (hMSCs and osteocytes) based on acquired Raman Spectra data
2. Determine cell viability of Pyrogallol-coated hMSCs
3. Determine the minimal sample size (training data) required to achieve stable accuracy trend from the best model

**Models Implemented:**
1. Supervised Machine Learning: KNN, NB, SVM, RF, XGBoost
2. Deep Learning: CNN
3. Unsupervised Learning: One Class SVM

**Libraries/Tools Used:**
1. TensorFlow Keras: Deep Learning model development
2. PCA: Data dimensionality reduction
3. KMeans Clustering: Plotting cell clusters data and removing outliers
4. Confusion Matrix: Models' classification metric
5. GridSearchCV: Hyperparameter tuning
