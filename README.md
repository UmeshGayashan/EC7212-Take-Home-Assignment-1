# EC7212 - Computer Vision and Image Processing

# Take Home Assignment 1

### ✅ * Load the Image from Google Drive
  ![Intensity Level 4 (Grayscale)](./Assets/LoadImage.png)

---

## 📝 Tasks

### ✅ Task 01. Reduce Intensity Levels
Reduce the number of intensity levels in an image from 256 to a specified value (like 2, 4, 8, etc.) in integer powers of 2.

- Both grayscale and color images were used.
- Variable `levels` can be used for reduction.

#### ▶️ Outputs:
- **Grayscale**

  ![Intensity Level 4 (Grayscale)](./Assets/IntensityLevel4GrayScale.png)

- **RGB**

  ![Intensity Level 4 (RGB)](./Assets/IntensityLevel4RGB.png)

- **Intensity Level Collection (Grayscale)**

  ![Intensity Level Collection - Grayscale](./Assets/IntensityLevelColectionGrayScale.png)

- **Intensity Level Collection (RGB)**

  ![Intensity Level Collection - RGB](./Assets/IntensityLevelColectionRGB.png)

---

### ✅ Task 02. Spatial Averaging (3×3, 10×10, 20×20)

Apply average blurring to smooth the image using neighborhood sizes of 3×3, 10×10, and 20×20.

#### ▶️ Output:
![Task 2 - Average Blur](./Assets/Task2.png)

---

### ✅ 3. Rotate Image (45 degrees and 90 degrees)

Rotate the input image by:
- 90 degrees using OpenCV's rotation utility
- 45 degrees using affine transformation

#### ▶️ Output:
![Task 3 - Rotation](./Assets/Task3.png)

---

### ✅ 4. Block-wise Spatial Resolution Reduction

For each non-overlapping block (3×3, 5×5, 7×7):
- Replace all pixels in the block with their average value.

#### ▶️ Output:
![Task 4 - Block-wise Averaging](./Assets/Task4.png)

---

### 💻 Tools Used

- Google Colab
- Python 3
- OpenCV
- NumPy
- Matplotlib
