# 🧠 Age and Gender Recognition using Deep Learning

This project implements a deep learning model to predict a person's age and gender from facial images. It utilizes convolutional neural networks (CNNs) trained on labeled face datasets to provide accurate predictions for real-world applications.

## 📁 Project Structure

```

├── Age and Gender Recognition DL training program.ipynb  # Jupyter notebook with training and evaluation
├── model/                                                # Directory for saving trained models
├── data/                                                 # Directory or instructions for dataset
├── requirements.txt                                      # Python dependencies
├── README.md                                             # Project overview
└── ...
```


## 🚀 Features

- Age and gender prediction from facial images
- Pre-trained model available for quick inference
- Modular and clean codebase (training, evaluation, inference)

## 🧑‍💻 Tech Stack

- Python
- TensorFlow / Keras
- OpenCV
- NumPy, Matplotlib
- Jupyter Notebook ([NoMorningstar/age-gender-Recognition - GitHub](https://github.com/NoMorningstar/age-gender-Recognition?utm_source=chatgpt.com))

## 📦 Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/raj4thakur/Age_Gender_Recognition.git
   cd Age_Gender_Recognition
   ```


2. **Install the dependencies:**
   ```bash
   pip install -r requirements.txt
   ```


3. **(Optional)** Download pretrained models and place them in the `model/` directory.

## 📊 Dataset

This model was trained on the UTKFaces, which contains thousands of face images with age and gender labels. You can also experiment with other datasets.

## 🏁 Getting Started

To run inference on an image:
```bash
python src/infer.py --image_path path/to/image.jpg
```


To train your own model:
```bash
python src/train.py
```



## 🤝 Contributing

Contributions are welcome! Please open issues or pull requests for any enhancements or bug fixes.
