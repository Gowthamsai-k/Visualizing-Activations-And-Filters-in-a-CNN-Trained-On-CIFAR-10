# Visualizing-Activations-And-Filters-in-a-CNN-Trained-On-CIFAR-10

🧠 CIFAR-10 CNN with Filter & Activation Visualization

This project trains a Convolutional Neural Network (CNN) on the CIFAR-10 dataset and visualizes both the learned convolution filters and the feature map activations.
It’s a simple, educational project to help understand how CNNs process image data.


⚡ Features

✅ Train a simple CNN on CIFAR-10

✅ Visualize learned convolution filters

✅ Visualize feature map activations

✅ Modular code structure for easy extension

✅ Save trained models and figures

🔧 Installation

Clone this repo:

git clone https://github.com/your-username/cifar10-cnn-visualization.git
cd cifar10-cnn-visualization


Create a virtual environment (optional but recommended):

python -m venv venv
source venv/bin/activate   # Linux/Mac
venv\Scripts\activate      # Windows


Install dependencies:

pip install -r requirements.txt

▶️ Usage

Run training + visualization:

python src/main.py


Trains the CNN on CIFAR-10

Saves model & loss logs in outputs/

Displays filter and activation visualizations

📊 Example Outputs
Conv1 Filters

(First convolution layer after training)


Conv1 Activations

(Feature maps for a sample test image)


📚 Dataset

CIFAR-10 Dataset

60,000 32x32 color images

10 classes: airplane, car, bird, cat, deer, dog, frog, horse, ship, truck

Automatically downloaded with torchvision.datasets.CIFAR10

🏗️ Future Improvements

 Add more CNN layers / architectures

 Add training progress plots (loss/accuracy)

 Support GPU training with torch.cuda

 Export trained models (.pth)

🤝 Contributing

Pull requests are welcome! For major changes, please open an issue first to discuss.
