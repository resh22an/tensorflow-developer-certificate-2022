
## Image Classification

- This repo contains preparation material for [TensorFlow Developer Certification](https://www.tensorflow.org/certificate) (Content as in Coursera's [DeepLearning.AI TensorFlow Developer](https://coursera.org/professional-certificates/tensorflow-in-practice) course)
- ```tf.keras.utils.image_dataset_from_directory```is used instead of the deprecated ```preprocessing.image.ImageDataGenerator``` in the below projects
- Tensorboard is used to visualize model's loss and accuracy metrics during hyperparameter tuning
- Image corruption is checked in DogsVsCats, RockPaperScissors datasets using JPEG's JFIF header check and libraries (```PIL.Image```, ```cv2```, ```wand```)

### Binary image classification :

- [Dogs or Cats](https://github.com/resh22an/tensorflow-developer-certificate-2022/blob/39407fd306e7b5ccc59ed611fe886112d6b70890/computer-vision-main/binary-image-classification/DogsVsCats.ipynb) - Classify images as Cats or Dogs
- [Transfer Learning - Dogs or Cats](https://github.com/resh22an/tensorflow-developer-certificate-2022/blob/9be6eba4c60e9695c2f3dac479c5e65cb2289315/computer-vision-main/binary-image-classification/DogsCats_TransferLearning.ipynb) - Using InceptionV3
- [Horses or Humans](https://github.com/resh22an/tensorflow-developer-certificate-2022/blob/9be6eba4c60e9695c2f3dac479c5e65cb2289315/computer-vision-main/binary-image-classification/HorsesHumans.ipynb) - Classify images as Horses or Humans
- [Happy or Sad](https://github.com/resh22an/tensorflow-developer-certificate-2022/blob/9be6eba4c60e9695c2f3dac479c5e65cb2289315/computer-vision-main/binary-image-classification/HappySad.ipynb) - Classify the emoji-like faces as Happy or Sad
    

### Multi class image classification :

- [Rock Paper Scissors](https://github.com/resh22an/tensorflow-developer-certificate-2022/blob/9be6eba4c60e9695c2f3dac479c5e65cb2289315/computer-vision-main/multiclass-image-classification/RockPaperScissors.ipynb) - Recognize if the hand image is in rock or paper or scissors pose
- [Sign language MNIST](https://github.com/resh22an/tensorflow-developer-certificate-2022/blob/9be6eba4c60e9695c2f3dac479c5e65cb2289315/computer-vision-main/multiclass-image-classification/SignLanguageMNIST.ipynb) - Classify each image as the letter it represents
- [Fashion MNIST](https://github.com/resh22an/tensorflow-developer-certificate-2022/blob/9be6eba4c60e9695c2f3dac479c5e65cb2289315/computer-vision-main/multiclass-image-classification/FashionMNIST.ipynb) - Recognize different items of clothing, trained from a dataset containing 10 different types
