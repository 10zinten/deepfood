# DeepFood
This project is submitted to AI Saturday, Kattankulathur. </br>This project uses ResNet-50 to classify image of common Indian food. With limitation of access to GPU and no exiting accumulated dataset of India food over the internet. It implements transfer learning by fine tuning the last 10 layer of the ResNet-50. As an application of this indian food image classification model, it has simple Django web application interface to generate ingredients of the predicted food image by the fine-tuned ResNet-50 model.
![result](https://i.postimg.cc/prDxYSCm/final-prediction.png)

# Model summary:
|                                 |                                |
|---------------------------------|-------------------------------:|
| # classes                       | 7                              |
| # image from each class used    | 200 (due to limited RAM space) | 
| Training Accuracy               | 96.79 %                        |
| Test Accuracy                   | 91.43 %                        |

![plot](https://i.postimg.cc/SR6RXNt5/plot.png)

![Home page](https://i.postiimg.cc/8k2KW5xX/home.png)
![ingredients page](https://i.postimg.cc/HxJz8DzC/dosa.png)

## Training step:


# Prediction result
![prediction](https://gdurl.com/0Jxj)
