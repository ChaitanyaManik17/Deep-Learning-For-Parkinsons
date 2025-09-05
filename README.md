🧠 Parkinson’s Disease Detection with Vision Transformer + Capsule Network and compare it with ANN

This project explores hybrid deep learning and feature engineering to detect Parkinson’s disease from medical images. It combines the power of Vision Transformers (ViT), Capsule Networks, and compare with classical Artificial Neural Network (ANN) . Our aim is to build a robust, interpretable, and accurate model that can aid in the early detection of Parkinson’s disease.

🚀 Key Features

* Vision Transformer + Capsule Network for advanced image-based feature extraction.
* Hybrid ANN classifier for feature-level classification.
* Visualizations for training progress (accuracy, loss curves).
* Comparative confusion matrices for both models.

Install dependencies:

pip install -r 
requirements.txt


▶️ How to Run

1. Train the Vision Transformer + Capsule Network

python main.py --model vit_capsnet


2. Train the ANN 

python main.py --model ann


3. Evaluate the Models

* Both models automatically save their best weights (`.h5` files).
* Validation accuracy and confusion matrices will be displayed after training.


📈 Results

  Vit + Capsule Network

  * Accuracy: \~97%
  * Stronger generalization on both classes

  ANN 

  * Accuracy: \~85%
  * Provides interpretability with handcrafted features

Confusion Matrices

 ✅ ViT + CapsNet → Balanced predictions with high accuracy
 ⚠️ ANN → Decent baseline but more misclassifications


🔮 Future Improvements

* Add Explainable AI methods (Grad-CAM, SHAP) for medical trust.
* Expand dataset with more diverse Parkinson’s samples.
* Optimize transformer hyperparameters.
* Deploy as a lightweight web/app diagnostic tool.


 📜 License

This project is licensed under the MIT License – feel free to use and adapt.

 🙌 Acknowledgments

* Dataset sources from Parkinson’s medical imaging research.
* TensorFlow/Keras, scikit-learn, and scikit-image contributors.
* Researchers exploring hybrid deep learning for neurodegenerative disease detection.
