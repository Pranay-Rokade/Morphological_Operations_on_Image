# Morphological Operations on Image

This project demonstrates basic **morphological operations** used in image processing using **OpenCV** and **NumPy**. These operations are commonly used to preprocess binary images, especially for tasks such as noise removal, hole filling, object separation, and edge detection.

## 📌 Aim

To perform and visualize the following morphological operations on a grayscale image:
1. Thresholding
2. Dilation
3. Erosion
4. Opening
5. Closing
6. Morphological Gradient

---

## 🛠️ Tools & Libraries Used

- Python
- OpenCV (`cv2`)
- NumPy
- Matplotlib

---

## 🖼️ Input

- A grayscale image file (`leg.jpg`)

> Ensure the image is present in the same directory as the script or update the `image_path` accordingly.

---

## 🔍 Morphological Operations Explained

| Operation | Description |
|----------|-------------|
| **Thresholding** | Converts grayscale image to binary using a fixed threshold value. |
| **Dilation** | Expands the white regions (foreground). Useful to connect disjoint objects. |
| **Erosion** | Shrinks the white regions. Useful for removing small white noises. |
| **Opening** | Erosion followed by dilation. Removes small objects from the foreground. |
| **Closing** | Dilation followed by erosion. Fills small holes in the foreground. |
| **Gradient** | Difference between dilation and erosion. Highlights the edges. |

---
