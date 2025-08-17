# 🌿 Plant Disease Detection

A machine learning-powered web application that detects plant diseases from leaf images using deep learning models. Built with Streamlit and TensorFlow, this application can classify plant leaves as healthy or identify various disease conditions.

## 🚀 Features

- **Dual Model Ensemble**: Combines Xception and DenseNet121 models for improved accuracy
- **Real-time Prediction**: Instant disease detection from uploaded images
- **User-friendly Interface**: Clean Streamlit web interface
- **Image Processing**: Automatic image cleaning and preprocessing
- **Progress Tracking**: Visual progress indicators during prediction
- **Responsive Design**: Optimized for various screen sizes

## 🏗️ Architecture

The application uses an ensemble approach combining two pre-trained deep learning models:

- **Xception Model**: Efficient CNN architecture for image classification
- **DenseNet121 Model**: Dense connectivity pattern for feature reuse
- **Ensemble Method**: Average of both model predictions for final classification

## 📋 Requirements

- Python 3.7+
- TensorFlow 2.x
- Streamlit
- PIL (Pillow)
- NumPy

## 🛠️ Installation

1. **Clone the repository**
   ```bash
   git clone <your-repo-url>
   cd plant-disease-detection1-main
   ```

2. **Navigate to the project directory**
   ```bash
   cd Plant-Disease-Detection-main
   ```

3. **Install dependencies**
   ```bash
   pip install streamlit tensorflow pillow numpy
   ```

4. **Download the model weights**
   - Place `model.h5` file in the project directory
   - This file contains the pre-trained ensemble model weights

## 🚀 Usage

1. **Run the application**
   ```bash
   streamlit run app.py
   ```

2. **Open your browser**
   - Navigate to `http://localhost:8501`
   - The application will load automatically

3. **Upload an image**
   - Click "Choose a Image file"
   - Select a plant leaf image (PNG or JPG format)
   - Wait for the prediction to complete

4. **View results**
   - The application will display the uploaded image
   - Show prediction results with confidence scores
   - Indicate if the plant is healthy or diseased

## 📁 Project Structure

```
plant-disease-detection1-main/
├── Plant-Disease-Detection-main/
│   ├── app.py              # Main Streamlit application
│   └── model.h5            # Pre-trained model weights (not included)
├── README.md               # Project documentation
└── .git/                   # Git repository
```

## 🔧 Dependencies

- **Streamlit**: Web application framework
- **TensorFlow**: Deep learning framework
- **PIL (Pillow)**: Image processing
- **NumPy**: Numerical computing
- **utils**: Custom utility functions (referenced in code)

## 📸 Supported Image Formats

- PNG (.png)
- JPEG (.jpg)

## 🎯 Model Performance

The ensemble model is trained to classify plant leaves into 4 categories:
- Healthy plant
- Disease type 1
- Disease type 2  
- Disease type 3

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

- TensorFlow team for the deep learning framework
- Streamlit for the web application framework
- Pre-trained models from ImageNet

## 📞 Support

If you encounter any issues or have questions:
- Open an issue on GitHub
- Check the project documentation
- Review the code comments for implementation details

---

**Note**: Make sure to download the `model.h5` file containing the pre-trained weights before running the application. The model file is not included in this repository due to size constraints.
