caltech_101_training is the training dataset for content images (909 images)
style_img has 8 style images

I use the above for training

caltech_101_testing (not very important) has images not in caltech_101_training; use to test the model

I use the torchvision.datasets.ImageFolder function to load data from the dataset folders above
