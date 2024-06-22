# Description 
This project aims to develop a robust machine learning model capable of predicting the age and gender of individuals from images. Leveraging deep learning techniques, such as convolutional neural networks (CNNs), the model learns to analyze facial features and extract relevant information for accurate age and gender classification. By training on diverse datasets containing labeled facial images, the model can generalize well to unseen data and provide insights into demographic characteristics from visual data.

# To Run
- ```
  pip3 install -r requirements.txt
  ```
- Check [the tutorial](https://www.thepythoncode.com/article/gender-and-age-detection-using-opencv-python) for more information on how to set this up.
- After you download the models weights and architectures, you can perform age & gender detection on any image:
    ```
    python age_and_gender_detection.py images/kids.jpg
    ```
- You can also use your camera, via the
  ```
  python age_and_gender_detection_live.py
  ```
