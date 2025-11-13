<h2 align="center">
  <a href="https://dainam.edu.vn/vi/khoa-cong-nghe-thong-tin">
  🎓 KHOA CÔNG NGHỆ THÔNG TIN (ĐẠI HỌC ĐẠI NAM) 🎓
  </a>
</h2>

<div align="center">
  <p align="center">
    <img width="200" alt="dnu_logo" src="https://github.com/user-attachments/assets/2bcb1a6c-774c-4e7d-b14d-8c53dbb4067f" />
    <img width="180" alt="fitdnu_logo" src="https://github.com/user-attachments/assets/ec4815af-e477-480b-b9fa-c490b74772b8" />
    <img width="170" alt="aiotlab_logo" src="https://github.com/user-attachments/assets/41ef702b-3d6e-4ac4-beac-d8c9a874bca9" />
  </p>

  <p align="center">
    <a href="https://dainam.edu.vn">
      <img alt="DaiNam University"
           src="https://img.shields.io/badge/DaiNam_University-ff6b35?style=flat-square">
    </a>
    <a href="https://dainam.edu.vn/vi/khoa-cong-nghe-thong-tin">
      <img alt="Faculty of IT"
           src="https://img.shields.io/badge/Faculty_of_IT-0066cc?style=flat-square">
    </a>
    <a href="https://www.facebook.com/DNUAIoTLab">
      <img alt="AIoTLab"
           src="https://img.shields.io/badge/AIoTLab-28a745?style=flat-square&logo=facebook&logoColor=white">
    </a>
  </p>

  <p align="center">
    <a href="https://www.python.org/"><img alt="Python" src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white"></a>
    <a href="https://pytorch.org/"><img alt="PyTorch" src="https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white"></a>
    <a href="https://ultralytics.com/yolov8"><img alt="YOLOv8" src="https://img.shields.io/badge/YOLOv8-00FFFF?style=flat-square"></a>
    <a href="https://huggingface.co/Salesforce/blip2-flan-t5-xl"><img alt="BLIP-2" src="https://img.shields.io/badge/BLIP--2-FED141?style=flat-square&logo=huggingface&logoColor=black"></a>
    <a href="https://flask.palletsprojects.com/"><img alt="Flask" src="https://img.shields.io/badge/Flask-000000?style=flat-square&logo=flask&logoColor=white"></a>
    <a href="https://gradio.app/"><img alt="Gradio" src="https://img.shields.io/badge/Gradio-FF7F50?style=flat-square"></a>
    <a href="https://opencv.org/"><img alt="OpenCV" src="https://img.shields.io/badge/OpenCV-27338e?style=flat-square&logo=opencv&logoColor=white"></a>
    <img alt="DeepSort" src="https://img.shields.io/badge/DeepSort-5A5A5A?style=flat-square">
    <img alt="CUDA" src="https://img.shields.io/badge/CUDA-76B900?style=flat-square&logo=nvidia&logoColor=white">
    <img alt="VLM Integration" src="https://img.shields.io/badge/VLM_Integration-4C8EDA?style=flat-square">
  </p>

  <p align="center">
    <img alt="Made with Love" src="https://img.shields.io/badge/Made_with-❤️-ff69b4?style=flat-square">
    <img alt="Status: Demo ready" src="https://img.shields.io/badge/Status-Demo_ready-00c853?style=flat-square">
    <img alt="Language: Vietnamese" src="https://img.shields.io/badge/Language-Vietnamese-22b8cf?style=flat-square">
  </p>
</div>
---
# Student-Dropout-Rate-Prediction-System-Using-Learning-Data-Analysis

# 🎓 Hệ Thống Dự Báo Tỷ Lệ Bỏ Học Sinh Viên

Ứng dụng phân tích rủi ro nghỉ học sinh viên dựa trên dữ liệu học tập, sử dụng Gemini AI.

## ✨ Tính Năng Chính

- 🔍 **Phân tích đơn lẻ**: Đánh giá nhanh 1 sinh viên
- 📊 **Phân tích hàng loạt**: Upload Excel, xử lý nhiều sinh viên
- 📈 **Dashboard**: 4 biểu đồ thống kê trực quan
- 🎯 **Lọc & sắp xếp**: Dễ dàng quản lý kết quả
- 📥 **Xuất Excel**: Export kết quả phân tích

## 🚀 Cài Đặt

### Bước 1: Lấy API Key

1. Truy cập [Google AI Studio](https://aistudio.google.com/)
2. Đăng nhập → Click **"Get API Key"**
3. Copy API Key

### Bước 2: Cấu Hình

Mở file `index.html`, tìm dòng **217** và thay API Key:

```javascript
const API_KEY = "YOUR_API_KEY_HERE"; // 👈 Thay bằng API Key của bạn
```

### Bước 3: Chạy Ứng Dụng

**Cách 1: Mở trực tiếp**
```bash
# Mở file index.html bằng trình duyệt
```

**Cách 2: Live Server (Khuyến nghị)**
```bash
npm install -g live-server
live-server
```

**Cách 3: Python HTTP Server**
```bash
python -m http.server 8000
# Mở: http://localhost:8000
```

## 📖 Hướng Dẫn Sử Dụng

### Phân Tích Đơn Lẻ
1. Nhập: GPA, HP Nợ, Điểm RL, Xếp loại
2. Click **"Phân Tích Rủi Ro"**
3. Xem kết quả với màu sắc: 🔴 Cao | 🟡 TB | 🟢 Thấp

### Phân Tích Hàng Loạt
1. Chuẩn bị Excel với các cột: `Mã SV`, `Họ và tên`, `Lớp`, `TBCHT H4`, `HP Nợ`, `Điểm RL`, `Xếp loại`
2. Upload file → Click **"Phân Tích Tất Cả"**
3. Xem bảng kết quả, lọc theo rủi ro, xuất Excel

### Dashboard
- Tự động hiển thị sau khi phân tích hàng loạt
- 4 biểu đồ: Tỷ lệ rủi ro, Rủi ro/lớp, GPA vs Nợ, Điểm RL

## 🛠️ Công Nghệ

- Bootstrap 5.3.3
- Chart.js
- SheetJS (xlsx.js)
- Gemini API 1.5 Flash

## 📋 File Excel Mẫu

| Mã SV | Họ và tên | Lớp | TBCHT H4 | HP Nợ | Điểm RL | Xếp loại |
|-------|-----------|-----|----------|-------|---------|----------|
| SV001 | Nguyễn Văn A | CNTT01 | 2.5 | 3 | 75 | Khá |
| SV002 | Trần Thị B | CNTT02 | 3.2 | 0 | 85 | Giỏi |

## 🐛 Xử Lý Lỗi

**Lỗi API Key**: Kiểm tra lại API Key ở dòng 217

**CORS Error**: Chạy qua HTTP Server (không mở file trực tiếp)

**Rate Limit**: Đợi 1 phút (Free: 60 requests/phút)

## 📄 Giấy Phép

MIT License

## 👥 Tác Giả

**[Tên Sinh Viên]**  
Trường: [Tên Trường]  
Giảng viên HD: [Tên GV]

---

Made with ❤️ for Vietnamese Education
