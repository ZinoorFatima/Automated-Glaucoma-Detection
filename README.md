# Automated-Glaucoma-Detection
UNet models for Optic disk and Optic Cup Segmentation to calculate CDR and diagnose glaucoma

Dataset used : ORIGA Dataset

Aim : This project is intended to tackle the issues of the poor detection of glaucoma through the improvement of the automated glaucoma detection by the development of a dependable and precise segmentation algorithm for the optic disc and cup in the retinal images.

Methodology: The project includes creating deep learning models for optic disc and optic cup segmentation and then calculating the cdr ratio for the segmented parts and checking it against the allowed ratio to diagnose glaucoma. The images are taken from a dataset to train the model. Images are resized and some changes in brightness and hue are made for better learning of the model. Then the image is passed to two different deep learning models to segment the optic disc and optic cup.
