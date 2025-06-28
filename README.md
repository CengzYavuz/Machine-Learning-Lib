# 📊 C++ Machine Learning Algorithms

**C++ Machine Learning Algorithms** is a collection of core machine learning algorithm implementations in C++, aimed at providing high-performance, educational reference code. This project is in its initial stages and will grow into a versatile library for classical ML techniques.

---

## 🛠 Project Summary

* **Project Title**: C++ Machine Learning Algorithms
* **Language**: C++ (C++17)
* **Status**: Early development / prototype
* **Purpose**: Educational implementations of ML algorithms with emphasis on clarity and performance

---

## 🚀 Planned Features

* **Regression Algorithms**

  * Linear Regression (Ordinary Least Squares)
  * Logistic Regression (Gradient Descent)

* **Classification Algorithms**

  * k-Nearest Neighbors (k-NN)
  * Support Vector Machine (SVM) - hard and soft margin

* **Clustering Algorithms**

  * K-Means Clustering
  * Hierarchical Agglomerative Clustering

* **Dimensionality Reduction**

  * Principal Component Analysis (PCA)

* **Data Handling Utilities**

  * CSV parser
  * Normalization and standardization functions

---

## 📦 Project Structure

```text
ml_cpp/
├── include/            # Public headers
│   ├── regression/     # Regression algorithms
│   ├── classification/ # Classification algorithms
│   ├── clustering/     # Clustering algorithms
│   └── utils/          # Utility functions (IO, math, preprocessing)
├── src/                # Implementation files
├── examples/           # Sample usage programs
└── tests/              # Unit tests (Google Test)
```

---

## 🛠 Build & Run

### Prerequisites

* C++17 compatible compiler (GCC/Clang/MSVC)
* CMake 3.10 or higher
* (Optional) Google Test for unit tests

### Build with CMake

```bash
mkdir build && cd build
cmake ..
make
```

### Run Examples

```bash
./examples/linear_regression_demo
```

### Run Tests

```bash
disable tests by default; to enable:
cmake -DENABLE_TESTS=ON ..
make
test
```

---

## 🔮 Roadmap & Future Improvements

* **Algorithm Enhancements**: Add regularization techniques (Ridge, Lasso) and advanced optimizers (Adam, RMSProp).
* **Performance Tuning**: SIMD vectorization and multi-threading support.
* **Model Persistence**: Serialization of trained models to disk.
* **Documentation**: Detailed API docs using Doxygen.
* **Package Management**: Publish as a CMake-compatible library or Conan package.

---

## 📧 Contact

**Your Name**
Email: [2022510158@ogr.deu.edu.tr](mailto:2022510158@ogr.deu.edu.tr)

Feel free to contribute via pull requests or open issues! :)
