# Music Source Separation API

API tách nguồn âm thanh (vocals/drums/bass/other) dùng mô hình **DemucsLite** đã huấn luyện ở notebook `w5.ipynb`, đóng gói thành dịch vụ FastAPI.

Tạo folder checkpoints, thêm mô hình đã huấn luyện vào, đặt tên là best_model.pt

```bash
python -m venv venv
# Windows:
venv\Scripts\activate
uvicorn app.main:app --reload
