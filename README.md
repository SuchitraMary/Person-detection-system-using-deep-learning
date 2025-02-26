Person Detection System using Deep Learning

This project is a Person Detection System that extracts image features using a Vision Transformer (ViT) and performs similarity search using FAISS. The system helps in clustering and retrieving similar individuals based on their appearance.

Features

Extracts deep features using ViT (Vision Transformer)

Stores and searches features efficiently using FAISS

Identifies dominant clothing colors for better retrieval

Supports image-based person search

Uses OpenCV for image processing

Project Structure

├── dataset/                          # Directory containing images
├── Deeplearning_Project.ipynb        # Jupyter Notebook with the complete pipeline
├── README.md                         # Project documentation
├─Person Detection System using Deep Learning

This project is a Person Detection System that extracts image features using a Vision Transformer (ViT) and performs similarity search using FAISS. The system helps in clustering and retrieving similar individuals based on their appearance.

Features

Extracts deep features using ViT (Vision Transformer)

Stores and searches features efficiently using FAISS

Identifies dominant clothing colors for better retrieval

Supports image-based person search

Uses OpenCV for image processing

Project Structure

├── dataset/                          # Directory containing images
├── Deeplearning_Project.ipynb        # Jupyter Notebook with the complete pipeline
├── README.md                         # Project documentation
├── requirements.txt                  # Required dependencies

Installation

Ensure you have Python 3.8+ installed. Then, install the required dependencies:

pip install -r requirements.txt

Or manually install the necessary packages:

pip install torch torchvision transformers faiss-cpu numpy matplotlib opencv-python webcolors seaborn 

Running the Project

Open Jupyter Notebook:

jupyter notebook

Open Deeplearning_Project.ipynb

Run all cells to execute the feature extraction, indexing, and retrieval pipeline.─ requirements.txt                  # Required dependencies

Installation

Ensure you have Python 3.8+ installed. Then, install the required dependencies:

pip install -r requirements.txt

Or manually install the necessary packages:

pip install torch torchvision transformers faiss-cpu numpy matplotlib opencv-python webcolors seaborn 

Running the Project

Open Jupyter Notebook:

jupyter notebook

Open Deeplearning_Project.ipynb

Run all cells to execute the feature extraction, indexing, and retrieval pipeline.
