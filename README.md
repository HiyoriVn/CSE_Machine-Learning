# CSE_Machine-Learning

Các notebook bài tập Machine Learning được sắp xếp theo chủ đề. Mở notebook bằng Jupyter Notebook/Lab hoặc Google Colab và chạy các cell theo thứ tự.

## Cấu trúc

- `01_perceptron/`
  - `perceptron_learning_algorithm.ipynb`: thuật toán Perceptron và minh họa cập nhật.
  - `bai_tap_gd_perceptron.ipynb`: bài tập Gradient Descent và Perceptron (3.26–3.30).
- `02_gradient_descent/`
  - `gradient_descent.ipynb`: Gradient Descent cho hàm một biến.
  - `gradient_descent_v2.ipynb`: Gradient Descent cho hồi quy tuyến tính.
- `03_underfit_overfit/`
  - `btvn_underfit_overfit.ipynb`: underfitting/overfitting, hồi quy đa thức và cross-validation.
- `04_id3/`
  - `iterative_dichotomiser_3.ipynb`: cài đặt ID3, chạy độc lập trên ba bộ dữ liệu.
  - `data/weather.csv`, `data/buys_computer.csv`, `data/credit_risk.csv`: dữ liệu minh họa ID3.

## Môi trường và cách chạy

Cài Python cùng Jupyter và các thư viện dùng trong notebook:

```bash
python -m pip install jupyter numpy pandas matplotlib scikit-learn pillow
jupyter lab
```

Mở notebook cần chạy từ Jupyter. Notebook ID3 tự tìm thư mục `data/` khi chạy từ `04_id3` hoặc thư mục gốc repo. Notebook underfit/overfit có cell cuối yêu cầu nhập một giá trị giờ ôn tập.

