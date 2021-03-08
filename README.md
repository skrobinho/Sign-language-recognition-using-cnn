# Sign language recognition using CNN in Julia
This dataset is known as **[Sign Language MNIST](https://www.kaggle.com/datamunge/sign-language-mnist)** and comes from The American Sign Language letter database of hand gestures and  represents a multi-class problem with 24 classes of letters (excluding J and Z which require motion).

Each training and test case represents a label (0-25) as a one-to-one map for each alphabetic letter A-Z (and no cases for 9=J or 25=Z because of gesture motions). The training data (27,455 cases) and test data (7172 cases). CSV files contain header row of label and pixel1,pixel2….pixel784 which represent a single 28x28 pixel image with grayscale values between 0-255.

![American Sign Language letters](https://miro.medium.com/max/590/1*XrbqBLMR1W3N8mIQCPzPbw.png)