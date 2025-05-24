# Glasses Detection - Image Classification

This project implements a binary image classification model using TensorFlow to detect whether a person is wearing glasses or not from images.

---

## Dataset

The dataset is too large to upload directly here (>465MB). You can download the dataset archive from Google Drive:

[Download dataset.rar](https://drive.google.com/file/d/1ePpwb8aWkMPpXTZQsAMRJZm2RclNkocD/view?usp=drive_link)

After downloading, extract the archive so that the folder structure looks like this:

```
dataset/
├── glasses/
│   ├── img1.jpg
│   ├── img2.jpg
│   └── ...
└── no_glasses/
    ├── img1.jpg
    ├── img2.jpg
    └── ...
```

---

## Project Structure

```
glasses_detection/
│
├── dataset/                 # Contains 'glasses' and 'no_glasses' image folders
│
├── glasses_detection.ipynb  # Jupyter Notebook with model training and testing code
│
└── requirements.txt         # Python dependencies
```

---

## How to Run

1. Clone the repository:
    ```
    git clone <your-repo-url>
    ```

2. Download and extract the dataset from the Google Drive link above.

3. Create a virtual environment and install dependencies:
    ```
    pip install -r requirements.txt
    ```

4. Open `glasses_detection.ipynb` in Jupyter Lab or Notebook.

5. Run the notebook cells step-by-step to train the model and test predictions.

---

## Requirements

- Python 3.x  
- TensorFlow  
- NumPy  
- Matplotlib  

(See `requirements.txt` for exact versions.)

---

## License

This project is open source and free to use.

---

Made with ❤️ by [Your Name or GitHub Handle]
