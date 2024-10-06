The FPS Increase ML project is a powerful tool for increasing video frame rates through deep learning-based frame interpolation, but it's important to note that **the model is still in development and not yet perfect**. While it can generate smoother playback, there are some limitations and areas for improvement that are being actively worked on.

### 🚀 Features:
- **Train Custom ML Models**: Tailor frame interpolation models to specific needs.
- **Frame Rate Enhancement**: Increase FPS without speeding up videos.
- **GPU Acceleration**: Leverage GPU for faster processing.
- **Colab Integration**: Seamlessly run in Google Colab with Google Drive support.
- **User-friendly Interface**: Easy command-line interactions for users.

### 🛠 Installation:
1. **Clone the repository**:
   ```bash
   git clone https://github.com/rigel08/fps-increase-ml.git
   cd fps-increase-ml
   ```
2. **Install dependencies**:
   ```bash
   pip install -r requirements.txt
   ```
3. **Optional - GPU Acceleration**: Set up CUDA for faster performance with PyTorch.

### 🖥 Usage:
- Open the **fps_increase_ml.ipynb** notebook in Google Colab.
- Set up the environment and mount your Google Drive.
- Choose to either:
  - Train a new model (option 1), or
  - Use an existing model (option 2).
- Upload a video, and the enhanced video will be saved to Google Drive.

### ⚠️ **Note: Model Limitations**
While the model successfully interpolates frames to increase FPS, **it's not yet fully optimized**. There may be inconsistencies, particularly with videos containing rapid scene changes or complex motion. The current version is limited to 720p resolution, and more improvements are planned in future updates.

### 🐛 Known Issues:
- Performance may degrade in scenes with rapid changes.
- Limited resolution support (720p) for now.

The project is under active development, and your feedback is crucial to help refine it!
