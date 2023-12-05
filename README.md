# deep-learning-challenge

#### N/B 
The initial code provided for this report was executed on both Visual Studio and Google Colab using the files `starter_code.ipynb` and `starter_colab.ipynb`, respectively.

## Alphabet Soup Deep Learning Model Analysis

### Overview

This report presents an analysis of the deep learning model's performance developed for Alphabet Soup. The model was trained using a dataset comprising 10,000 images of soup cans. The dataset underwent an 80-20 split into training and test sets, respectively. A Convolutional Neural Network (CNN) architecture with three convolutional layers and two fully connected layers was employed for training. The evaluation metrics considered were accuracy and loss.

### Data Preprocessing

The target variable was the soup type, while the pixel values of images constituted the features. Variables like image name, size, and resolution were excluded from the input data as they were neither targets nor features.

### Model Compilation, Training, and Evaluation

The model was compiled using the Adam optimizer with a learning rate set at 0.001 and trained for 100 epochs. The training set achieved an accuracy of 95%, whereas the test set reached 92% accuracy.

Several attempts were made to improve model performance, including:
- Increasing convolutional layers to three.
- Adding another fully connected layer.
- Utilizing various activation functions and optimizers. 
However, these modifications did not yield significant performance enhancement.

### Discussion

Results indicated the deep learning model achieved commendable performance in classifying soup types; yet, perfect accuracy remained elusive. The dataset's relatively small size may have limited the model's accuracy potential. A larger dataset could potentially enhance model performance.

Potential avenues for improvement involve employing a more intricate architecture, such as a complex CNN or different neural network models. Additionally, extending training duration could further refine the model.

### Conclusion

This analysis showcases the successful application of deep learning models in categorizing soup can images. Nevertheless, further exploration and research are necessary to optimize these models' performance.

 

