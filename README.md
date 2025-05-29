📱 Mobile Price Classification using Neural Networks

This project builds a binary classification model to predict mobile phone price range using machine learning and neural networks (Keras + TensorFlow).

 📊 Dataset
The dataset contains various features like battery power, RAM, camera, etc., and a `price_range` column as the target.

Source: Mobile_Price_Classification-220531-204702.csv

🧠 Model Architecture
- Input Layer: Based on number of features
- Dense Layer 1: 8 units, ReLU activation
- Dense Layer 2: 4 units, ReLU activation
- Output Layer: 1 unit, Sigmoid activation

🛠️ Technologies Used
- Python
- Pandas
- Keras (TensorFlow backend)
- Scikit-learn

📈 Training Details
- Loss function: Binary Crossentropy
- Optimizer: Adam
- Metrics: Accuracy
- Epochs: 100 (can be tuned)
- Batch size: 32 (can be tuned)

🗂️ Files Included
- `model.py`: The main code
- `Mobile_Price_Classification.csv`: Input dataset
- `weights.keras`: Trained model saved for later use
