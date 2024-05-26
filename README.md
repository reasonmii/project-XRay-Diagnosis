# X-ray Diagnosis with Deep Learning
- Developed a full-stack web app for predicting respiratory illnesses from user-uploaded chest X-rays, using an EfficientNet-based classifier with 98% accuracy.
- Enhanced model interpretability with Grad-CAM, highlighting the areas that influenced the model's predictions.

### Transfer Learning with EfficientNetB0 (CNN) from TensorFlow Keras
- Used accuracy as a metric, with a 10% validation set
- Batch size of 32
- GlobalAveragePooling2D
- Dropout with a rate of 0.5
- 4 Dense layers with a softmax activation function
- Adam optimizer

### Grad-CAM from TensorFlow
- Calculated how changes in each pixel of the last convolutional layer's output affect the class score
- Applied a ReLU activation to the heatmap to keep only positive values
- Used the heatmap for visualization

### Skills
- Python, JavaScript, HTML/CSS, Bootstrap, Flask, Docker, Heroku (deploying web app), AWS Lightsail
- Python libraries : TensorFlow (keras), sklearn, cv2, pandas, numpy, matplotlib, seaborn
