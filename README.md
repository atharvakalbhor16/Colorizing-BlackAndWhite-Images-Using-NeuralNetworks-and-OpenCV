# 🎨 Colorizing Black and White Images using Neural Networks & OpenCV

This project focuses on **colorizing black-and-white (grayscale) images** using **deep learning models** and **OpenCV**. By leveraging pre-trained neural networks, the system automatically adds realistic color to B&W images — a task useful in restoration, media production, and visual enhancement.

---

## 📌 Project Objective

- Automatically colorize grayscale images using AI-based models.
- Utilize **OpenCV’s DNN module** with pre-trained deep learning models.
- Provide a simple input-output interface for image colorization.

---

## 🔧 How It Works

1. Load the pre-trained **colorization model** (typically a Caffe model trained on ImageNet or similar).
2. Convert input grayscale image into the appropriate format for inference.
3. Pass the image through the model to generate a colorized output.
4. Merge the luminance and predicted color channels to create a final result.

---

## 🛠️ Technologies Used

- Python
- OpenCV
- Deep Neural Networks (DNN module in OpenCV)
- Pre-trained Caffe models (`.prototxt` and `.caffemodel`)


## 🚀 Getting Started

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/Colorizing-BlackAndWhite-Images-Using-NeuralNetworks-and-OpenCV.git
   cd Colorizing-BlackAndWhite-Images-Using-NeuralNetworks-and-OpenCV
   ```

2. Install dependencies:
   ```bash
   pip install opencv-python numpy
   ```

3. Download the required pre-trained models:
   - `colorization_deploy_v2.prototxt`
   - `colorization_release_v2.caffemodel`
   - Points cluster file: `pts_in_hull.npy`

4. Run the script:
   ```bash
   python colorize.py --input input.jpg --output output.jpg
   ```

---


