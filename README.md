# 🧠 AML Project - Image Segmentation Web Application

[![Python](https://img.shields.io/badge/Python-3.8+-blue.svg)](https://www.python.org/downloads/)
[![Streamlit](https://img.shields.io/badge/Streamlit-1.0+-red.svg)](https://streamlit.io/)

> A powerful web application built with Streamlit for running image segmentation models developed in Python.

---

## 📖 Overview

This project is part of the **Advanced Topics in Machine Learning and Neural Networks** course. It provides an interactive web interface to deploy and run a pre-trained segmentation model, allowing users to easily upload images and visualize segmentation results in real-time.

### ✨ Key Features

- 🖼️ **Interactive Image Upload**: Easily upload images through a user-friendly interface
- 🎯 **Real-time Segmentation**: Process images with a trained segmentation model
- 📊 **Visualization Tools**: View original images alongside segmentation masks
- 🚀 **Fast Inference**: Optimized for quick predictions
- 💾 **Export Results**: Download segmented images and masks

---

## 🛠️ Technologies Used

| Technology | Purpose |
|------------|---------|
| **Python** | Core programming language |
| **Streamlit** | Web application framework |
| **PyTorch** | Deep learning framework |
| **OpenCV** | Image processing |
| **NumPy** | Numerical computations |

---

## 🚀 Getting Started

### Prerequisites

Make sure you have Python 3.8 or higher installed on your system.

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/davidesserra/AML_Project.git
   cd AML_Project
   ```

2. **Create a virtual environment** (recommended)
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   ```

3. **Install dependencies**
   ```bash
   pip install -r requirements.txt
   ```

### Running the Application

Launch the Streamlit app:
```bash
streamlit run app.py
```

The application will open in your default browser at `http://localhost:8501`

---

## 📁 Project Structure

```
AML_Project/
├── app.py              # Main Streamlit application
├── model/              # Segmentation model files
│   ├── model.py        # Model architecture
│   └── weights/        # Pre-trained weights
├── utils/              # Utility functions
│   ├── preprocessing.py
│   └── visualization.py
├── requirements.txt    # Python dependencies
└── README.md          # This file
```

---

## 🎮 How to Use

1. **Upload an Image**: Click on the upload button to select an image from your device
2. **Run Segmentation**: Click the "Segment" button to process the image
3. **View Results**: Explore the segmentation mask and overlay visualization
4. **Download**: Save the results to your device

---

## 🤝 Contributing

Contributions are welcome! Feel free to:

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

---

## 📜 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

## 👥 Authors

- **Davide Serra** - *Initial work* - [davidesserra](https://github.com/davidesserra)

---

## 🙏 Acknowledgments

- Advanced Topics in Machine Learning and Neural Networks course
- Streamlit team for the amazing framework
- Open-source community for various tools and libraries

---

<p align="center">
  Made with ❤️ for AML Course
</p>
