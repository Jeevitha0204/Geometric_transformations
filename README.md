# Geometric_transformations
Python implementations of Euclidean, Similarity, Affine, and Projective (Homography) transformations with NumPy + Matplotlib visualization.
# Geometric Transformations in Python

This repository provides clean and well-documented Python implementations of fundamental **2D geometric transformations**:

- **Euclidean Transformations** (translation + rotation)
- **Similarity Transformations** (scaling + rotation + translation)
- **Affine Transformations** (rotation, scaling, shear, translation)
- **Projective Transformations (Homography)**

All transformations are implemented using **NumPy** and visualized with **Matplotlib**.

---

## 📂 Repository Structure
geometric-transformations/
│
├── transformations/
│ ├── affine_transform.py
│ ├── similarity_transform.py
│ ├── euclidean_transform.py
│ ├── projective_transform.py
│ └── init.py
│
├── examples/
│ ├── demo_affine.py
│ ├── demo_similarity.py
│ ├── demo_euclidean.py
│ └── demo_projective.py
│
├── requirements.txt
├── README.md
└
── LICENSE

---

## ⚡ Requirements

Install dependencies with:

```bash
pip install -r requirements.txt
🔍 Implemented Transformations
1. Euclidean Transformation

Translation

Rotation (about origin or arbitrary point)

Combined transformation (rotation + translation)

2. Similarity Transformation

Uniform scaling

Scaling + rotation

Scaling + rotation + translation

3. Affine Transformation

Rotation

Scaling (uniform / non-uniform)

Shear

Translation

4. Projective Transformation

Homography

Perspective warping
