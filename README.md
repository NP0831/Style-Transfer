# Style-Transfer

**StyleTransfer** is a web application that allows users to apply artistic styles from one or more images onto a single content image. The application also segments and combines stylized outputs into a final merged image for seamless viewing.

---

## 🔍 Overview

StyleTransfer enables users to:

- Upload a content image and multiple style images.
- Apply neural style transfer to generate stylized versions of the content image.
- Automatically segment and combine outputs based on the number of styles.
- Interact with the system through a user-friendly Gradio interface.

---

## 🖼️ Description

This web application provides the following features:

- **Content and Style Uploads**: Users can upload one content image and up to `n` style images.
- **Multiple Stylizations**: Each style image is individually applied to the same content image.
- **Combined Output**: The stylized outputs are merged into a single image using segmentation for visual comparison.
- **Real-Time Inference**: The application uses GPU acceleration (if available) for faster results.
- **Interactive Web Interface**: Users can interactively upload images and view/download results.

---

## 🌟 Benefits of StyleTransfer

- 🎭 **Multi-style Support**: Apply multiple style images to a single content image in one go.
- ✨ **Automatic Segmentation**: Stylized results are merged into a single composite image with seamless transitions.
- ⚡ **Fast and Lightweight**: Built with PyTorch and optimized with GPU support.
- 🌐 **Web-Based Access**: No local setup needed beyond dependencies — just launch and go.
- 🧠 **Deep Learning Powered**: Uses a pretrained VGG-19 model for feature extraction and Gram matrix-based style matching.

---

## 🧰 Tech Stack

- **Frontend**: Gradio (Python-based UI)
- **Backend**: PyTorch
- **Model**: Pretrained VGG-19
- **Image Processing**: Pillow, Matplotlib

---

## 📚 Necessary Libraries

Make sure the following libraries are installed before running the code:

```bash
pip install torch torchvision matplotlib gradio pillow numpy

