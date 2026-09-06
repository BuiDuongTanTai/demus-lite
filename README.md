# Music Source Separation API

API tách nguồn âm thanh (vocals/drums/bass/other) dùng mô hình **DemucsLite** đã huấn luyện ở notebook `w5.ipynb`, đóng gói thành dịch vụ FastAPI.

## 1. Cài đặt

```bash
python -m venv venv
# Windows:
venv\Scripts\activate
# Linux/macOS:
source venv/bin/activate
pip install -r requirements.txt


checkpoints/best_model.pt
