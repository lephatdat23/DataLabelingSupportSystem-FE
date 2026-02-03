# Data Labeling Support System – Frontend

🎯 Frontend của hệ thống **Data Labeling Support System** – hỗ trợ gán nhãn dữ liệu (data labeling) cho các bài toán AI/ML.

Frontend được xây dựng bằng **React**, giao tiếp với Backend (Java / Spring Boot) thông qua REST API.

---

## 🚀 Công nghệ sử dụng

- ⚛️ React (Vite / CRA)
- 🟦 JavaScript / TypeScript
- 🎨 CSS / Tailwind / MUI (tuỳ project)
- 🔗 REST API

---

## 📂 Cấu trúc thư mục (tham khảo)

```text
src/
 ├── api/           # Gọi API backend
 ├── components/    # Component tái sử dụng
 ├── pages/         # Các trang chính
 ├── hooks/         # Custom hooks
 ├── services/      # Xử lý logic, request
 ├── App.jsx
 └── main.jsx
