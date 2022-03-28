# DGM-Project
In this project, we propose a framework that detects OoD samples, by learning the likelihood values and the reconstruction loss values for the true dataset.
The model will be trained on one dataset and trained on both the same dataset as well as a completely new, never seen, dataset. The model will calculate the likelihood and the reconstruction loss, and will classify the given sample as in-distribution or out-of-distribution.

We use the following models:
NICE (HW1) - Taken from "paultsw" (https://github.com/paultsw/nice_pytorch) as it showed better training time then our own.
VAE (HW2) - Our code from the course.
SVM - Our code written for the project.
