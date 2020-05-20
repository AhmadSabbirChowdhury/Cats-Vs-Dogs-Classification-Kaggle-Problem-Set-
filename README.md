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

## Final Validation Accuracy 
Epoch 1/20
100/100 [==============================] - 34s 341ms/step - loss: 0.6921 - acc: 0.5262 - val_loss: 0.6529 - val_acc: 0.5476
Epoch 2/20
100/100 [==============================] - 31s 307ms/step - loss: 0.6764 - acc: 0.5682 - val_loss: 0.6847 - val_acc: 0.6128
Epoch 3/20
100/100 [==============================] - 30s 303ms/step - loss: 0.6591 - acc: 0.6057 - val_loss: 0.5545 - val_acc: 0.6104
Epoch 4/20
100/100 [==============================] - 31s 309ms/step - loss: 0.6506 - acc: 0.6076 - val_loss: 0.6764 - val_acc: 0.6418
Epoch 5/20
100/100 [==============================] - 29s 294ms/step - loss: 0.6374 - acc: 0.6307 - val_loss: 0.5693 - val_acc: 0.6066
Epoch 6/20
100/100 [==============================] - 32s 321ms/step - loss: 0.6274 - acc: 0.6449 - val_loss: 0.4727 - val_acc: 0.6695
Epoch 7/20
100/100 [==============================] - 31s 308ms/step - loss: 0.5999 - acc: 0.6690 - val_loss: 0.5994 - val_acc: 0.6986
Epoch 8/20
100/100 [==============================] - 30s 303ms/step - loss: 0.5922 - acc: 0.6787 - val_loss: 0.4266 - val_acc: 0.6920
Epoch 9/20
100/100 [==============================] - 30s 300ms/step - loss: 0.5893 - acc: 0.6726 - val_loss: 0.4778 - val_acc: 0.6991
Epoch 10/20
100/100 [==============================] - 30s 302ms/step - loss: 0.5802 - acc: 0.6941 - val_loss: 0.5888 - val_acc: 0.6536
Epoch 11/20
100/100 [==============================] - 31s 308ms/step - loss: 0.5784 - acc: 0.7005 - val_loss: 0.6417 - val_acc: 0.6707
Epoch 12/20
100/100 [==============================] - 30s 303ms/step - loss: 0.5652 - acc: 0.7004 - val_loss: 0.5322 - val_acc: 0.7176
Epoch 13/20
100/100 [==============================] - 30s 303ms/step - loss: 0.5486 - acc: 0.7266 - val_loss: 0.3873 - val_acc: 0.7313
Epoch 14/20
100/100 [==============================] - 30s 295ms/step - loss: 0.5537 - acc: 0.7123 - val_loss: 0.4637 - val_acc: 0.7176
Epoch 15/20
100/100 [==============================] - 29s 294ms/step - loss: 0.5336 - acc: 0.7266 - val_loss: 0.4678 - val_acc: 0.7120
Epoch 16/20
100/100 [==============================] - 30s 299ms/step - loss: 0.5501 - acc: 0.7146 - val_loss: 0.3560 - val_acc: 0.7101
Epoch 17/20
100/100 [==============================] - 28s 285ms/step - loss: 0.5396 - acc: 0.7246 - val_loss: 0.3761 - val_acc: 0.7011
Epoch 18/20
100/100 [==============================] - 33s 326ms/step - loss: 0.5272 - acc: 0.7336 - val_loss: 0.4965 - val_acc: 0.7249
Epoch 19/20
100/100 [==============================] - 30s 301ms/step - loss: 0.5228 - acc: 0.7437 - val_loss: 0.4994 - val_acc: 0.7272
Epoch 20/20
100/100 [==============================] - 29s 295ms/step - loss: 0.5173 - acc: 0.7443 - val_loss: 0.5962 - val_acc: 0.7390
