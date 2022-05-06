# Haiti Earthquake 2010 Analytical Project

In 2010, disaster struck Haiti. A dangerous earthquake killed an estimated 100,000-300,000 people. 

As part of the rescue effort, a team from the Rochester Institute of Technology were flying an aircraft to collect high resolution geo-referenced imagery. It was known that the people whose homes had been destroyed by the earthquake were creating temporary shelters using blue tarps, and these blue tarps would be good indicators of where the displaced persons were – if only they could be located in time, out of the thousands of images that would be collected every day. The problem was that there was no way for aid workers to search the thousands of images in time to find the tarps and communicate the locations back to the rescue workers on the ground in time. The solution would be provided by data-mining algorithms, which could search the images far faster and more thoroughly (and accurately?) then humanly possible. The goal was to find an algorithm that could effectively search the images in order to locate displaced persons and communicate those locations rescue workers so they could help those who needed it in time.

Using some of these images, a training and holdout set were created and is contained in this repository. One such image is shown below:

![img_1](https://user-images.githubusercontent.com/66688601/167225138-6d0a9c70-c15d-41ef-9e8a-2a215b6326fb.jpg)

## In this repository...

I have the the training/testing data and a Rmarkdown and pdf of my final report. This was a final school project in a graduate-level UVA data mining course.

In my report, I train and test several machine learning algorithms in a classification problem to predict blue tarps in images. The report includes the testing of these methods: Logistic Regression, Ridge Regression, KNN, Linear Discriminant Analysis, Quadratic Discriminant Anaylsis, Random Forests, and various flavors of Support Vector Machines (linear, quadratic, and radial kernels). I generated a PDF from my Rmarkdown containing my code and a narrative with figures as I walk through my thought process of this project step-by-step.

