📌 Facial Emotion Recognition using Deep CNN
🚀 A Deep Learning project to classify facial expressions using FER2013 and AffectNet datasets.
This model recognizes 7 emotions (Angry, Disgust, Fear, Happy, Neutral, Sad, Surprise) using a Deep Convolutional Neural Network (CNN).

🔹 Features
✔️ Deep CNN Model trained on FER2013 & AffectNet
✔️ Achieved 65.45% Accuracy on the test set
✔️ Uses PyTorch for training and inference
✔️ Confusion Matrix & Loss Curves for performance analysis
✔️ Supports Real-Time Inference (Webcam support)

📂 Dataset
This project uses two datasets:

🔹 FER2013
Contains 35,887 grayscale images (48×48) labeled with 7 emotions.
🔹 AffectNet
Contains 400,000 images collected from the internet.
"Contempt" emotion was removed to match FER2013 labels.
📊 Results
📌 Test Accuracy: 65.45%
📌 Best Performing Emotion: Happy (88% Precision, 83% Recall)
📌 Most Confused Emotions: Fear & Sad (often misclassified as Neutral)
