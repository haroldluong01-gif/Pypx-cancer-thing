# Pypx-cancer-thing
Cancer cells look abnormal compared to healthy cells: they often have irregular shapes,  larger or misshapen nuclei, and tend to clump together instead of forming orderly layers. Under a microscope, they appear distorted and disorganized, reflecting their uncontrolled growth. This project is about detecting and killing cancer cells. 

75% of the images are in the train directory.

25% of the images are in the validation directory.

Both the train and validation directories contain the following
subdirectories:

benign/
malignant/
normal/

Normal cells are healthy and function as expected, whereas benign cells
form non-cancerous growths (tumors) that may appear abnormal but do not
invade surrounding tissue or spread to other parts of the body.


70-80% of the images are in the train directory.

20-30% of the images are in the validation directory.

Both of these directories contain the following subdirectories:
cancer/
normal/

The images for the benign and malignant cells came from the following
source:
https://data.mendeley.com/datasets/jxwvdwhpc2/1

The images for the normal cells came from the subsequent source:
https://zenodo.org/records/3632035

The images are located in the dataset_cancer_v1/classificacao_binaria path.

Notice how there are four different folders with an "X" at the end of their
names.

The "X" means time magnified.

40X is 40 times larger than the actual size.
100X is 100 times larger than the actual size.
200X is 200 times larger than the actual size.
400X is 400 times larger than the actual size.

At first, we can begin with the images located inside the
40X folder because the images in this folder will be less
noisy than the ones in 400X.

In machine learning, noise is irrelevant or a distracting
detail. In other words, it doesn't help the machine learning
model decide between "cancer" or "normal".

Inside 40X, there are two subfolders:
benign/
malignant/

Think of benign as a non-cancerous tumour.

Think of malignant as a cancerous tumour.

data_loader.ipynb is where the program verifies that the images are
rady and usable before the machine learning model is trained.


Think of malignant as a cancerous tumour.