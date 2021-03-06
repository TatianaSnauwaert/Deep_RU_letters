## Deep_RU_letters

The goal of this project is to classify an image of a handwritten letter into one of 33 categories/letters of the Russian alphabet using deep learning technologies (computer vision).

**This project's repo includes the following files**:
- The project's final jupyter notebook (Deep_RU_letters_ CNN tutorial.ipynb);
- The final pretrained model (best_model.h5)

The source files for the project (images and their metadata) can be found in the [dataset](https://www.kaggle.com/tatianasnwrt/russian-handwritten-letters) I've created on Kaggle. It includes the following files:
- The folder with all images (all_letters_image)
- The information file about each image - cyrillic letter, its label, the filename of the image and the type of background (all_letters_info)

The project's notebook (Deep_RU_letters_ CNN tutorial.ipynb) can also be found on [Kaggle](https://www.kaggle.com/tatianasnwrt/deep-ru-letters-cnn-tutorial). It has four main parts:

1. Data preparation
2. Model creation and tuning
3. Model evaluation
4. Model prediction on test data

*References*:

- The dataset was prepared and uploaded by [Olga Belitskaya](https://www.kaggle.com/olgabelitskaya) including the total of 14190 images.

Letter Symbols => Letter Labels:

а=>1, б=>2, в=>3, г=>4, д=>5, е=>6, ё=>7, ж=>8, з=>9, и=>10, й=>11, к=>12, л=>13, м=>14, н=>15, о=>16, п=>17, р=>18, с=>19, т=>20, у=>21, ф=>22, х=>23, ц=>24, ч=>25, ш=>26, щ=>27, ъ=>28, ы=>29, ь=>30, э=>31, ю=>32, я=>33

- I have organized the original dataset to make it easier to understand for beginners. The updated version can be found on this [link](https://www.kaggle.com/tatianasnwrt/russian-handwritten-letters).

- Most of the explanations in the jupyter notebook are borrowed from the [Kaggle *Deep Learning* course](https://www.kaggle.com/learn/deep-learning) and this [kernel](https://www.kaggle.com/yassineghouzam/introduction-to-cnn-keras-0-997-top-6/output#Introduction-to-CNN-Keras---Acc-0.997-(top-8%)).
I will develope a Sequential Convolutional Neural Network for this project. I've chosen to build it with keras API (Tensorflow backend) which is very intuitive. Firstly, I will prepare the data (handwritten letters images) then I will focus on the CNN modeling and evaluation.

**The logbook of this project can be found [here](https://docs.google.com/spreadsheets/d/15L4IlWvsdMmVphFHvqlhz3lmE25VTatBQBejyFZUyK0/edit?usp=sharing).** It includes the following tabs:

- Time spent on the project
- Ideas to improve the model
- Logbook of different configurations I tested
- Lessons learnt from the project
