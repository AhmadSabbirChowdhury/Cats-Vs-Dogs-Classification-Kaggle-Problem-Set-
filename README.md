# Cats-Vs-Dogs-Classification-Kaggle-Problem-Set-
Here I created a model that will classify between cats and dogs using the Kaggle Competition Dataset

# Kaggle Dataset
## Here I used Kaggle API to import the dataset into google collab. 
!kaggle competitions download -c dogs-vs-cats 

## Training and Validation Accuracy (with overfitting)
![Inaccurate Data](https://user-images.githubusercontent.com/45898995/82493935-9b8e6480-9b0a-11ea-952f-d5425fe17561.png)

## Training and Validation Loss (with overfitting)
![Inaccurate Data 2](https://user-images.githubusercontent.com/45898995/82494128-ea3bfe80-9b0a-11ea-9606-bcd4429af0fd.png)

## Training and Validation Accuracy (After fixing the overfitting)
![accurate data](https://user-images.githubusercontent.com/45898995/82494273-266f5f00-9b0b-11ea-8568-62483d0356f3.png)

## Training and Validation Loss (After fixing the overfitting)
![accurate data 2](https://user-images.githubusercontent.com/45898995/82494383-4b63d200-9b0b-11ea-81e3-997becef8f50.png)


Using ImageDataGenerator to read images from directories¶

Keras has a module with image-processing helper tools, located at keras.preprocessing.image. In particular, it contains the class ImageDataGenerator,which lets you quickly set up Python generators that can automatically turn image files on disk into batches of preprocessed tensors.
