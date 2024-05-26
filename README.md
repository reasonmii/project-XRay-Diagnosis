# X-ray Diagnosis with Deep Learning
Chest radiography is a commonly employed method for diagnosing respiratory ailments, such as COVID-19 and tuberculosis. Beyond providing an initial assessment of various respiratory conditions, chest X-rays are relatively inexpensive and widely accessible. Nonetheless, despite recent technological advancements, medical professionals must still interpret X-ray images to determine patients' health status. While such procedures may yield accurate diagnoses for experienced practitioners, it requires additional time and effort. Our team contends that machine learning algorithms, particularly those within the subfield of deep learning, offer a promising avenue for improving diagnostic accuracy in chest illnesses and for expediting such procedures.

Recent advancements in medical diagnosis have favored deep learning due to its potential to detect various diseases from medical images. Specifically, convolutional neural networks (CNNs) offer significant promise for this particular task since they can learn patterns and features in images that might prove difficult for human interpretation. Our project aims to predict various respiratory ailments, including COVID-19 and tuberculosis, using deep learning techniques on chest X-ray images. Finally, our team developed this web application where users can upload their chest X-ray images for analysis, expanding the reach of diagnostic capabilities beyond solely medical professionals.

Our team trained a deep learning model based on x-ray image datasets from Kaggle. Please refer to the below links for details. You may download the test datasets below.

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
