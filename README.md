# GTSRB-German-Traffic-Sign-Recognition

In this project, I used Python and TensorFlow to classify traffic signs.

Dataset used: German Traffic Sign Dataset. This dataset has more than 50,000 images of 43 classes.

I was able to reach a more than +95% validation accuracy, and a +95% testing accuracy.

I utilized deep neural networks and convolutional neural networks to classify traffic signs. I trained and validated a model so it can classify traffic sign images using the German Traffic Sign Dataset. After the model was trained, I tested out the model on images of German traffic signs I found on the web. The rubric contains "Stand Out Suggestions" for enhancing the project beyond the minimum requirements, of which I believe I accomplished by augmenting the training data and challenging my classifier with "toxic" difficult to read road signs.

The goal of this project was to build a Convolutional Neural Network (CNN) in TensorFlow and Python.

## Dependencies

This are the main packages used:

- [Numpy](https://numpy.org/)
- [Tensorflow](https://www.tensorflow.org/api_docs/python/tf/math/tan)
- [Python 3.5 or above](https://www.python.org/)

Full details on the requirements.txt file.


## Installation

To install the required dependencies, you can use pip:

```bash
pip install -r requirements.txt
```

## Usage
To use the project, follow these steps:

git clone https://github.com/yourusername/GTSRB-German-Traffic-Sign-Recognition.git

Navigate to the project directory:

cd GTSRB-German-Traffic-Sign-Recognition

Run the application:
python predict_traffic_signs.py

## Model Training
If you want to train the model with your own data:

Replace the existing dataset with your data in the data directory.
Modify the data preprocessing and model training scripts as needed.

Run the training script:
python train_model.py

## Contributing
Contributions to this project are welcome! If you have any suggestions, enhancements, or bug fixes, feel free to open an issue or submit a pull request.

## License
This project is licensed under the MIT License - see the LICENSE file for details.





## Conclusion

The project was highly effective during experimentation, resulting in a robust traffic sign classifier app. However, it occasionally encountered challenges with random sample images from the internet.

Furthermore, for a self-driving car to locate traffic signs in public, it must first identify their locations. Speeding signs, for example, may require an OCR (object recognition) mechanism to scan the image with sliding windows to locate candidate signs. Such a detection mechanism is beyond the scope of this project.


