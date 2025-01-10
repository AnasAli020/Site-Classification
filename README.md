# Jordanian Site Image Classification
This project focuses on building a robust image classification system for famous Jordanian landmarks. The goal is to classify images of various locations using state-of-the-art deep learning models. The models implemented in this project include InceptionV3, VGG16, VGG19, and ResNet101.

📍 Locations
The project classifies images into the following categories of iconic Jordanian landmarks:

Petra Treasury
The world-famous archaeological wonder and UNESCO World Heritage Site.
Petra Siq
The narrow gorge leading to the Treasury with stunning rock formations.
Wadi Rum
A vast desert landscape with dramatic sandstone mountains and red sand dunes, also known as the "Valley of the Moon."
Ajloun Castle
A 12th-century Islamic castle with historical and architectural significance.
Roman Amphitheater
A well-preserved ancient theater located in the heart of Amman.
Umm Qais
A Greco-Roman site known for its ancient ruins and breathtaking views of the Golan Heights and the Sea of Galilee.

🧠 Models Used
The following pre-trained convolutional neural network (CNN) architectures were fine-tuned for this classification task:

InceptionV3
Known for its efficiency in handling complex datasets with lower computational cost.
VGG16
A classic deep learning architecture, simple and effective for transfer learning tasks.
VGG19
A deeper version of VGG16, ideal for extracting fine-grained features.
ResNet101
A deep residual network capable of addressing vanishing gradient issues, ideal for complex image data.
📊 Dataset and Preprocessing
Dataset: The dataset consists of high-quality images of the listed locations, collected from various sources. Images were labeled manually to ensure accuracy.
Preprocessing: Each image was resized to the required input dimensions of the models. Data augmentation techniques such as rotation, flipping, and color adjustments were applied to increase the diversity of the training data.
🚀 Model Performance
Metrics: Accuracy, precision, recall, and F1-score were used to evaluate the performance of each model.
Results:
InceptionV3: Achieved the best balance of accuracy and computational efficiency.
VGG16 and VGG19: Excelled in extracting detailed features but required higher training time.
ResNet101: Performed well on complex datasets with deep feature representation.
