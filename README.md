# Fashion MNIST Classification — Artificial Neural Network (PyTorch)

This project implements a clean and efficient **Artificial Neural Network (ANN)** using **PyTorch** to classify images from the **Fashion-MNIST dataset**.  
The model achieves **92.80% accuracy** with dropout regularization and the Adam optimizer.

---

##  Tech Stack
- Python  
- PyTorch  
- Torchvision  
- NumPy  
- Matplotlib  

---

##  Model Architecture
model = nn.Sequential(
nn.Flatten(),
nn.Linear(784, 256), nn.ReLU(),
nn.Dropout(0.2),
nn.Linear(256, 128), nn.ReLU(),
nn.Linear(128, 10),
nn.LogSoftmax(dim=1)
)


---

##  Key Features
- End-to-end ANN model training  
- Achieved **92.8% test accuracy**  
- Clean training loop with Adam optimizer  
- Loss & accuracy visualization  
- Misclassified image analysis  
- Easy-to-understand PyTorch implementation  

---

##  Project Structure

 Artificial-Neural-Network
 ann_fashion_mnist_pytorch.ipynb 
 # Main notebook
 README.md 
 
 # Documentation


---

##  How to Run
git clone https://github.com/Arbaz-hai/Artificial-Neural-Network

cd Artificial-Neural-Network
pip install torch torchvision matplotlib numpy
jupyter notebook


Open the notebook:
ann_fashion_mnist_pytorch.ipynb


---

##  Dataset
Fashion-MNIST: 60,000 training + 10,000 testing images  
Classes include: T-shirt, trouser, pullover, dress, coat, sandal, shirt, sneaker, bag, ankle boot.

Automatically downloaded via:
torchvision.datasets.FashionMNIST()


---

##  Future Enhancements
- Migrate ANN → **CNN** for higher accuracy  
- Add early stopping & learning rate scheduler  
- Deploy using FastAPI or Flask  

---

##  Author
**Arbaz**  
GitHub: https://github.com/Arbaz-hai  
LinkedIn: https://www.linkedin.com/in/arbaz-sheikh-712408339  

---

 If this project helped you, please consider giving it a **star**!
