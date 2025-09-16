# Begulas IPA App

Dự án ứng dụng iOS/Android với cơ chế đăng nhập bằng **Key bản quyền**.  
Mỗi Key được ràng buộc với một thiết bị duy nhất và có hạn sử dụng.  

---

## 🎯 Mục tiêu
- Xây dựng ứng dụng Flutter (cross-platform).
- Backend sử dụng **Python + FastAPI**.
- Cơ sở dữ liệu: **SQL Server**.
- Cơ chế quản lý key:
  - Key chỉ dùng được cho 1 máy (ràng buộc device ID).
  - Key có thời hạn sử dụng.
  - Admin có panel riêng để quản lý key (thêm, xoá, gia hạn).

---

## 📂 Cấu trúc dự án
begulas-ipa-app/
│
├── app/ # Flutter App (frontend)
│ └── lib/ # Code chính của Flutter
│
├── backend/ # Backend FastAPI
│ ├── app.py # API chính
│ ├── requirements.txt
│ └── db/ # Models & truy vấn SQL
│
└── README.md
