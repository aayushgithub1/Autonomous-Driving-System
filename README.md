# Autonomous-Driving-System
/* Dataset Details */
- **Dataset**: German Traffic Sign Benchmark (GTSB)
  - Contains over 30,000 labeled images.
  - Split into approximately:
    - **20,000 images** for training.
    - **10,000 images** for testing.

/* Libraries Used */
- **Scikit-Learn**: Utilized for image processing and prediction tasks.

/* Classification Models */
- **Random Forest Classifier (RFC)**:
  - Initial Accuracy: **75%**
  - After Grid Search: **80%**
- **Multi-Layer Perceptron (MLP)**:
  - Accuracy: **78%**

/* Preprocessing Techniques */
- Conversion to **gray scale**.
- Addition of **noise** for robustness.
- Increasing **screen brightness**.
- **Image resizing** using OpenCV.
