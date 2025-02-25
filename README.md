# Machine Learning for Brain Tumor Detection

## Overview

Machine learning has been a revolutionary tool in the modern age, in many different ways. The medical field is no exception. For example, light microscopy systems have been greatly enhanced through machine learning techniques. This has allowed scientists to observe biological processes in real-time with low-cost microscopy equipment (Hunter, 2019). 

Brain tumors are a significant health issue around the world. There are multiple types of brain tumors, determined by the type of cells that make up the tumor. Moreover, there are two classifications of all tumors: benign and malignant. Malignant brain tumors are cancerous brain tumors, which have a rather low 5-year survival rate of 35.7% after diagnosis. In the United States, brain tumors have quite a low occurrence rate of 1% (Srakocic, 2023). Despite the rarity of brain tumor formation, it is critical to diagnose malignant brain tumors at an early stage, which increases the chances of survival after diagnosis. 

One of the most common modes of diagnosing brain tumors is the MRI scan. Not all MRI equipment is created equal; that is, low-cost MRI equipment typically returns lower-resolution MRI scans than expensive MRI equipment. In the United States, healthcare costs are higher than ever. Funding expensive MRI equipment increases these costs. An objective of this project is to alleviate healthcare costs by enhancing low-resolution MRI scans using edge detection.

Furthermore, there are machine learning models currently in development that aid health professionals in tumor detection. It works by finding patterns in images that can easily be missed with the human eye. The issue that lies within these models is the difficulty in maximizing both their sensitivity and specificity (Srakocic, 2023) because of there is an imbalance of data for each group. This project aims to enhance the diagnosis of brain tumors by alleviating human error, maximizing both sensitivity and specificity of the model itself, and decreasing the cost of MRI equipment.

## Project Files

1. Data Set

   A set of MRI brain scan images were downloaded from the Kaggle website, and can be downloaded using the following link: https://www.kaggle.com/dsv/1183165. The images are also included in the Data folder. 

   This dataset has a rather extensive directory. Inside of the main folder are two subfolders: Testing and Training. Testing and Training each have the following subfolders: glioma_tumor, meningioma_tumor,          pituitary_tumor, and no_tumor. Each of the four subfolders contain hundreds of MRI brain scan images of differing size. Using the title of each of the four subfolders, I created the labels for each image. In      total, there are 3264 MRI brain scan images in the dataset.

   The MRI brain scan images used for this project contain brain tumors of three common types: glioma, meningioma, and pituitary. Gliomas are formed by the overgrowth of glial cells that surround the nerves and      aid in nerve function. Meningiomas are oftentimes benign (non-cancerous) tumors that form on the meninges. They are the membranes that surround the brain and spinal chord (Srakocic, 2023). Pituitary tumors,       as the name suggests, form on the pituitary gland. There are a total of 926 images in the glioma class, 937 in the meningioma class, 901 in the pituitary class, and 500 in the no tumor class.
   
2. Code

   - MRI_Scan_Project_Code.ipynb contains all of the code used throughout this project. It also includes discussion of results and models throughout.


## How to Run the Project

1. Dependencies

   Using the following code, install the following Python libraries (if not done so already): pip install numpy glob2 pillow matplotlib scikit-learn scikit-image scipy opencv-python torch

2. Notebook Execution

   Using your favorite IDE, run the MRI_Scan_Project_Code.ipynb Python notebook. Also read through the analysis throughout the notebook.

## References

Hunter, P. (2019). The advent of ai and deep learning in diagnostics and imaging: Machine learning systems have potential to improve diagnostics in healthcare and imaging systems in research. EMBO Reports, 20(7):e48559.

Srakocic, S. (2023). How common are brain tumors? Medically Reviewed By: Susan W. Lee, DO; Copy Edited By: Maggie Hellwig.
