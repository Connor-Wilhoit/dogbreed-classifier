# dogbreed-classifier
Cute Little "Dog Breed Classifier" - Deep Learning Project - FastAI Library Implementation

This is essentially an extension/customization of the first notebook, second lesson in fastai's first course on Deep-Learning For Coders.
link: https://github.com/fastai/course-v3/blob/master/nbs/dl1/lesson2-download.ipynb

The folder labeled 'dogpics_downloads' contains text files for downloading the images from Google.
If you want to use your own images, you can use the 'get_images.js' file.
-to see how to use said javascript file, see the fastai notebook, or figure it out.

The 'dogbreeds.txt' file just contains a brief list of all dogbreeds used in this program, and is just one of the first markdown cells in the notebook.

If you actually create a Neural Network using this notebook, and train for an hour or two, you should have a pretty descent classifying-model, where
you can have it predict the dogbreed on a given image (use an image the model has never seen before!).
-I got it to a little over %90 accuracy on my best run, with very minimal training.

Future work: (a) create a webapp that implements a fully training network, w/a webpage frontend that allows users to simply upload an
                 image of a given dog, and get back the model's best guess as to which breed it it.
             (b) extend the functionality to include all major dog breeds.
