# Dharshini
Image processing project in Python demonstrating geometric transformations.
# Geometric-Transformations-in-Computer-Vision

This repository contains simple Python + Matplotlib demos of **geometric transformations** used in image processing and computer vision.  
The implementations follow the definitions from *Computer Vision: Algorithms and Applications (Szeliski, 2010/2018 edition)*.

---

## 📌 Transformations Covered

### 1. Euclidean Transformations
- Operations: **Rotation + Translation**
- Preserves **shape and size** (rigid body motion).
- Represented by a rotation matrix + translation vector.
- Demo: A square rotated and shifted.

### 2. Similarity Transformations
- Operations: **Rotation + Translation + Uniform Scaling**
- Preserves **shape**, but not size.
- Special case of affine transform with scaling factor `k`.
- Demo: A square rotated, shifted, and uniformly scaled.

### 3. Affine Transformations
- Operations: **Rotation, Translation, Scaling (uniform/non-uniform), Shear**
- Preserves **parallel lines**, but not necessarily angles or lengths.
- Represented by a 2×3 affine matrix.
- Demo: A square warped into a rectangle or parallelogram.

### 4. Projective Transformations (Homography)
- Most general linear 2D warp.
- Operations: **Translation, Rotation, Scaling, Shear, Perspective warping**.
- Preserves **straight lines**, but parallel lines may meet (vanishing point).
- Represented by a 3×3 homography matrix in homogeneous coordinates.
- Demo: A square warped into a trapezoid (simulating perspective).

---

## 📂 Files

- `euclidean_transform.py` – Rotation + Translation
- `similarity_transform.py` – Rotation + Translation + Uniform Scaling
- `affine_transform.py` – General affine (non-uniform scaling, shear)
- `projective_transform.py` – Homography (perspective warping)

---
