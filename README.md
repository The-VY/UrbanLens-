
UrbanLens 🌆

# 🚗 Smart City Vehicle Number Plate Detection

## Summary
This project is all about building a smart system for detecting vehicle number plates using the TensorFlow Object Detection API. 🛠️ Initially developed during the Smart India Hackathon, the goal was to create a camera system that could help manage traffic, track vehicles, and catch those who break the rules. 🚦

## Tech Stack
- 👨‍💻 Programming Language:** Python
- 📚 Libraries: TensorFlow, OpenCV, NumPy, Pandas, Jupyter Notebooks
- 🛠️ Tools: TensorFlow Object Detection API, Virtual Environments, TensorBoard
- 💻 Platform: Linux, Windows

## Introduction
During the Smart India Hackathon, my team and I set out to create something ambitious—a smart camera system that could read vehicle number plates and help manage city traffic. 🚘 The idea was to assist city management in identifying and tracking vehicles, especially those not following the rules. While we didn’t win the hackathon, the journey was incredibly rewarding. It gave me a deep dive into the world of object detection and machine learning. 🌟

## How to Run This Project

### Step 1: Set Up Your Virtual Environment 🧑‍💻
Create and activate a virtual environment to keep things neat and tidy:

```bash
python -m venv tfod
source tfod/bin/activate # Linux
.\tfod\Scripts\activate # Windows 
```

### Step 2: Install Dependencies 🔧
Upgrade pip and install the necessary packages:

```bash
python -m pip install --upgrade pip
pip install ipykernel
python -m ipykernel install --user --name=tfodj
```

### Step 3: Collect Some Images 📸
Use the provided notebook to gather images for training:
[1. Image Collection.ipynb]

### Step 4: Organize Your Images 🗂️
Manually split your collected images into `train` and `test` folders:
```
\TFODCourse\Tensorflow\workspace\images\train
\TFODCourse\Tensorflow\workspace\images\test
```

### Step 5: Train Your Model 🤖
Open the [2. Training and Detection.ipynb] notebook to start training. 
Pro tip: You can also train the model in a separate terminal to see live loss metrics, which is pretty cool! 😎

### Step 6: Evaluate Like a Pro 🎯
Once your model is trained, use TensorBoard to evaluate its performance:

```bash
cd Tensorlfow/workspace/models/my_ssd_mobnet/eval
tensorboard --logdir=.
```
Fire up your browser and check out metrics like mAP (mean Average Precision) and Recall. 🚀

---

Even though we didn’t bag the top spot at the hackathon, this project was an amazing learning experience. It deepened my understanding of object detection, and I’m excited to see where these skills take me next! 💪