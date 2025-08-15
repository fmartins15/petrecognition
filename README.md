# PETrecognition – Face Recognition with Photo-based Anti-Spoofing

**PETrecognition** is a computer vision project that integrates **image enhancement techniques**, **face recognition**, and a **photo-based anti-spoofing system** designed to detect and block fraudulent attempts using photos displayed on smartphones.

The final goal is to **deploy the entire solution on an embedded device** such as a Raspberry Pi, making it practical and professional for real-world applications.

---

## Repository Structure

- **preprocessamento_imagem.ipynb**  
  Image preprocessing and enhancement routines (e.g., filtering, histogram equalization, contrast improvement).

- **reconhecimento-facial.ipynb**  
  Face detection and recognition pipeline using **Keras**.

- **anti-spoofing-system.ipynb**  
  Anti-spoofing module specialized in detecting photo-based fraud attempts from smartphone screens, using **scikit-learn**.

---

## Technologies & Tools

- **Python**
- **OpenCV**
- **Keras**
- **scikit-learn**
- **Jupyter Notebook**

---

## How to Run

1. Clone the repository:  
   ```bash
   git clone https://github.com/fmartins15/petrecognition.git

2. Install dependencies:
   ```bash
    pip install opencv-python keras scikit-learn jupyter numpy

3. Run the notebooks in order:

    .Image preprocessing
    .Face recognition
    .Anti-spoofing

Project Goal

The ultimate aim of PETrecognition is to deploy the entire system onto embedded hardware such as a Raspberry Pi, ensuring it works efficiently in a professional, real-world environment.

Contributions & Contact

Contributions are welcome!
For questions or suggestions, contact:
📧 meierfelipe075@gmail.com