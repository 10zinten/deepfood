# DeepFood
This project is submitted to AI Saturday, Kattankulathur. </br>This project uses ResNet-50 to classify image of common Indian food. With limitation of access to GPU and no exiting accumulated dataset of India food over the internet. It implements transfer learning by fine tuning the last 10 layer of the ResNet-50. As an application of this indian food image classification model, it has simple Django web application interface to generate ingredients of the predicted food image by the fine-tuned ResNet-50 model.
![result](https://i.postimg.cc/prDxYSCm/final-prediction.png)

# Model summary:
With the help of transfer learning,  model achieved good accuracy on only 200 images from each class.

|                                 |                                |
|---------------------------------|-------------------------------:|
| # classes                       | 7                              |
| # image from each class used    | 200 (due to limited RAM space) | 
| Training Accuracy               | 96.79 %                        |
| Test Accuracy                   | 91.43 %                        |

![plot](https://i.postimg.cc/SR6RXNt5/plot.png)

# Demo
![Home page](https://preview.ibb.co/nruho0/home.png)
![ingredients page](https://preview.ibb.co/gZEAaf/dosa.png)

## Run Wep app:
```
$ pip install -r requirement.txt
$ cd foodImageClassifier
$ python manage.py runserver
```

# Training the model:
training porcess and evaluating model done in [this notebook](https://github.com/10zinten/deepfood/blob/master/FIC%20fine-tuned%20on%20ResNet-50%20with%20keras.ipynb). Download the dataset from [here](https://www.floydhub.com/tenzinknrb/datasets/indian-food-images)
