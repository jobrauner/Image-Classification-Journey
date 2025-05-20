# Data Folder - Machine Learning Project

Welcome to the data folder for our machine learning project. This directory contains links to the datasets we have utilized throughout our research and development process. Given the substantial size of the image data, we have provided download links to both Google Drive and Kaggle for your convenience.

Below, you will find details about each dataset, including its purpose and where it has been used within the project.

## Datasets

### 1. Google Drive Link

- **Purpose:** These links contain the datasets provided by the company and the dataset retrieved from the company one after manual labelling.
- **Download Link:**
  - [Google Drive - Company Dataset](https://drive.google.com/drive/folders/1wuA87IKUZv5iAswmPLKIB3wvWAh2WjvP?usp=share_link)
  - [Google Drive - Labelled images](https://drive.google.com/drive/folders/1dvcofV59yLtktT6fI6gaFdPmhDWQ_-dt?usp=share_link)
- **Usage Dataset "Data":** 
  - Used in the initial data exploration phase to understand data distribution and characteristics.
  - Labelled manually to then train our models.
- **Usage Dataset "Labelled images":**
  - Used to train, validate and test our models


### 2. Kaggle Link

- **Purpose:** This link provides access to a smaller version of the RVL-CDIP dataset collected by Adam W. Harley, Alex Ufkes, and Konstantinos G. Derpanis. You can find details [here](https://adamharley.com/rvl-cdip/)
- **Download Link:** [Kaggle - RVL-CDIP small](https://www.kaggle.com/datasets/uditamin/rvl-cdip-small)
- **Usage:**
  - Data Augmentation: To ensure validity and robustness of our models, we have decided to perform classification on unseen images loaded from the web.
  - We firslty collected all the 16 classes provided by the dataset; later, we choosed the 4 classes of interest (E-mail, Resume, Handwritten Documents, and Resumé) to which we added a fifth one called "other" by selecting randomized images from the remaining 12 classes which were not the focus in our project.

## Instructions for Download

1. **Google Drive:**
   - Click on the provided link.
   - Select the files or folders you wish to download.
   - Click the download button.

2. **Kaggle:**
   - Click on the provided link.
   - Sign in to your Kaggle account.
   - Click on "Download" and obtain the dataset. Be careful: this datasets consists on 16 different classes (roughly between 2900/3000 images each), chose the ones of interests.


## Additional Information

In case of any problem with the data loading, please reach out our team. Below you can find our emails:

- [Joshua Brauner (group referent)](mailto:joshua.brauner@studenti.luiss.it)
- [Elisa Dobici](mailto:elisa.dobicil@studenti.luiss.it)
- [Paoloemilio Grande](mailto:paoloemilio.grande@studenti.luiss.it)
