## Deep_RU_letters

The goal of this notebook is to classify an image of a handwritten letter into one of 33 categories/letters of Russian alphabet using the deep learning technologies (computer vision).

References:

The dataset has been prepared and uploaded by Olga Belitskaya including the total of 14190 images.
Letter Symbols => Letter Labels:

а=>1, б=>2, в=>3, г=>4, д=>5, е=>6, ё=>7, ж=>8, з=>9, и=>10, й=>11, к=>12, л=>13, м=>14, н=>15, о=>16, п=>17, р=>18, с=>19, т=>20, у=>21, ф=>22, х=>23, ц=>24, ч=>25, ш=>26, щ=>27, ъ=>28, ы=>29, ь=>30, э=>31, ю=>32, я=>33

Most of the explanations are borrowed from the Kaggle "Deep Learning" course and this kernel.
I will develope a Sequential Convolutional Neural Network for this project. I've chosen to build it with keras API (Tensorflow backend) which is very intuitive. Firstly, I will prepare the data (handwritten letters images) then i will focus on the CNN modeling and evaluation.

This Notebook has four main parts:

Data preparation
Model creation and tuning
Model evaluation
Model prediction on test data

The logbook of this project can be found [here](https://docs.google.com/spreadsheets/d/15L4IlWvsdMmVphFHvqlhz3lmE25VTatBQBejyFZUyK0/edit?usp=sharing). It includes the following tabs:

Time spent on the project
Ideas to improve the model
Logbook of different configurations I tested
Lessons learnt from the project
