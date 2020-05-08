# Scientific-ML-Study-Discussion

## Apa itu Scientific Machine Learning?
Scientific machine learning adalah gabungan disiplin ilmu antara komputasi santifik
dan machine learning. Komputasi santifik biasanya merupakan pemodelan fenomena fisis
yang biasanya dimodelkan oleh persamaan differensial, yang dimana persamaan tersebut
telah menjelaskan bagaimana fenomena tersebut bekerja dari **asumsi hukum fisis dan faktor2 yang
ada didalamnya**. Dengan menyelesaikan model yang diasumsikan, kita dapat mengekstrapolasi
fenomena yang terjadi didalamnya dalam dimensi ruang-waktu, proses menyelesaikan model
biasanya membutuhkan **waktu yang lama**.

Dilain hal, machine learning, merupakan teknik pengambil kesimpulan (inference) yang
berasal dari **data-data** (data yang banyak) yang ada, **minim atau tanpa asumsi / informasi**
yang disediakan. Model akan dibentuk sendiri dari data-data yang ada, dan proses prediksi
model cenderung **sangat cepat**.

Namun, beberapa trend telah mulai menggabungkan kedua cabang ilmu tersebut untuk membentuk
model yang dapat dijelaskan namun dibentuk oleh data, dimana informasi atau asumsi yang diberikan
akan membentuk model yang umum dengan membutuhkan sedikit data tanpa overfitting, parameter
yang lebih sedikit, dan ekstrapolasi / prediksi jauh lebih cepat dan akurat.

Silahkan baca lebih lanjut mengenai [Sci-ML](https://www.stochasticlifestyle.com/the-essential-tools-of-scientific-machine-learning-scientific-ml/).

## Goals
- Analisis ML dalam inference menganalisis data-data fenomena fisis
  - bisakah ML mempelajari hukum fisika didalam data yang disediakan?
  - bisakah ML melakukan generalisasi model dan membentuk konstrain hukum fisikanya sendiri
- Membentuk model persamaan differensial yang tidak diketahui berbasis ML + asumsi fisis

## Anggota Diskusi:
- Muhammad Gaffar
- Faidzal Adilla

## Silabus
- Ordinary Differential Equation
  - dasar-dasar DifferentialEquations.jl
  - integrator problem, hands-on bouncing problem
  - analisis teknis hasil, hands-on oscillator harmonic
  - hamiltonian diffeq & automatic differentiation, hands-on kepler problem
  - chaotic system, hands-on double pendulum
- Partial Differential Equation
  - dasar-dasar PDE, hands-on heat equation
- Parameter Estimation / Bayes Inference
- Latent Space (?)
- Renormalization Group (?)
- Hamiltonian, Lagrangian NN (?)
