# 🚀 Batch Normalization & Learning Rate Scheduler in PyTorch

<div align="center">

![Python](https://img.shields.io/badge/Python-3.x-blue?style=for-the-badge&logo=python)
![PyTorch](https://img.shields.io/badge/PyTorch-Deep%20Learning-red?style=for-the-badge&logo=pytorch)
![Jupyter Notebook](https://img.shields.io/badge/Jupyter-Notebook-orange?style=for-the-badge&logo=jupyter)
![Machine Learning](https://img.shields.io/badge/Machine%20Learning-Neural%20Networks-brightgreen?style=for-the-badge)

</div>

---

## 📌 Project Overview

This project demonstrates the use of **Batch Normalization** and **Learning Rate Scheduler** in a deep learning model using **PyTorch**.

The notebook explains how these two powerful techniques help improve neural network training by making the model more stable, faster, and efficient.

---

## 🧠 What This Notebook Covers

This notebook focuses on two important deep learning concepts:

### 🔹 Batch Normalization

Batch Normalization is used to normalize the inputs of each layer during training.  
It helps the model train faster and improves stability.

### 🔹 Learning Rate Scheduler

A Learning Rate Scheduler automatically adjusts the learning rate during training.  
It helps the model learn better by reducing the learning rate at the right time.

---

## ✨ Key Features

- Implementation using **PyTorch**
- Neural network model training
- Use of **Batch Normalization**
- Use of **Learning Rate Scheduler**
- Training loop implementation
- Loss calculation
- Backpropagation
- Optimizer usage
- Model performance improvement techniques

---

## 🛠️ Technologies Used

| Technology | Purpose |
|----------|---------|
| Python | Programming Language |
| PyTorch | Deep Learning Framework |
| NumPy | Numerical Operations |
| Jupyter Notebook | Code Execution and Documentation |
| Matplotlib | Visualization |

---

## 📂 Project Structure

    Batch_Normalization-and-LR-Scheduler/
    │
    ├── Batch_Normalization&LRScheduler.ipynb
    └── README.md

---

## ⚙️ Installation

Before running the notebook, install the required libraries:

    pip install torch torchvision numpy matplotlib

If you are using Jupyter Notebook:

    pip install notebook

---

## ▶️ How to Run

Follow these steps to run the project:

    git clone https://github.com/your-username/Batch_Normalization-and-LR-Scheduler.git

    cd Batch_Normalization-and-LR-Scheduler

    jupyter notebook

Then open:

    Batch_Normalization&LRScheduler.ipynb

---

## 🧪 Training Process

The notebook follows a standard deep learning workflow:

1. Import required libraries
2. Load and prepare the dataset
3. Define the neural network model
4. Apply Batch Normalization
5. Define loss function
6. Define optimizer
7. Apply Learning Rate Scheduler
8. Train the model
9. Track training loss
10. Evaluate model performance

---

## 📈 Why Batch Normalization?

Batch Normalization helps in:

- Faster training
- Better gradient flow
- Reduced internal covariate shift
- More stable neural network training
- Improved model generalization

---

## 📉 Why Learning Rate Scheduler?

Learning Rate Scheduler helps in:

- Adjusting learning rate automatically
- Improving convergence
- Avoiding overshooting the minimum loss
- Fine-tuning model training
- Achieving better performance

---

## 🔁 General Training Flow

    for epoch in range(num_epochs):
        model.train()

        for data, target in train_loader:
            optimizer.zero_grad()

            output = model(data)
            loss = criterion(output, target)

            loss.backward()
            optimizer.step()

        scheduler.step()

---

## 📊 Expected Outcome

After completing this notebook, you will understand:

- How Batch Normalization improves neural network training
- How Learning Rate Scheduler controls learning rate
- How to train a PyTorch model effectively
- How optimization techniques improve deep learning performance

---

## 📚 Concepts Learned

- Deep Learning
- Neural Networks
- PyTorch Model Training
- Batch Normalization
- Learning Rate Scheduling
- Loss Function
- Optimizer
- Backpropagation
- Training Loop

---

## 🎯 Use Cases

This project is useful for:

- Deep learning beginners
- PyTorch learners
- Machine learning students
- Neural network optimization practice
- Academic projects
- GitHub portfolio projects

---

## 🚀 Future Improvements

Possible improvements for this project:

- Add accuracy visualization
- Compare model with and without Batch Normalization
- Compare different Learning Rate Schedulers
- Add validation accuracy
- Add confusion matrix
- Use a larger dataset
- Save and load trained model

---

## 🧾 Requirements

    torch
    torchvision
    numpy
    matplotlib
    notebook

---

## 📌 Project Highlights

- Clean PyTorch implementation
- Beginner-friendly notebook
- Covers important optimization techniques
- Useful for understanding model training improvement
- Perfect for learning Batch Normalization and LR Scheduling

---

## 🙌 Conclusion

This notebook provides a practical understanding of how **Batch Normalization** and **Learning Rate Scheduler** improve deep learning model training.

Both techniques are widely used in modern neural networks to make training faster, smoother, and more effective.

---

## 👨‍💻 Author

**Kartik Shrikisan Jadhav**

---

## ⭐ Support

If you found this project helpful, consider giving it a ⭐ on GitHub.

---

<div align="center">

### 🚀 Keep Learning. Keep Building. Keep Improving.

</div>
