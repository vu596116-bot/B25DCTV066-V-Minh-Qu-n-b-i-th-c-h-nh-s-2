# Bài Thực Hành 03 - Sổ Chi Tiêu Cá Nhân (ReactJS)

**Môn học:** Lập trình Web (LTW)  
**Mã lớp/học phần:** RIPT1306-20261-07  
**Giảng viên:** Ngô Văn Nhận  

---

## 👨‍🎓 Thông tin sinh viên
- **Họ và tên:** Vũ Minh Quân
- **Mã sinh viên:** B25DCTV066

---

## 📁 Cấu trúc thư mục dự án

```text
.
├── part-a-class/       # Phần A: Xây dựng ứng dụng bằng Class Component
│   ├── src/
│   │   ├── App.jsx     # Component quản lý state chính, form, lọc, tính tổng
│   │   └── Clock.jsx   # Component đồng hồ sử dụng lifecycle
│   ├── package.json
│   └── ...
├── part-b-hooks/       # Phần B: Xây dựng ứng dụng bằng Function Component + Hooks
│   ├── src/
│   │   ├── hooks/
│   │   │   ├── useFetch.js  # Custom hook tương tác MockAPI (get, add, delete, loading, error)
│   │   │   └── useClock.js  # Custom hook quản lý đồng hồ chạy theo giây
│   │   ├── App.jsx          # Component chính ứng dụng Hooks, useRef, useContext
│   │   └── ...
│   ├── package.json
│   └── ...
└── README.md           # Hướng dẫn chạy & Báo cáo so sánh Class vs Hooks
