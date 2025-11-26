# 📊 Excel Reader App

Ứng dụng web đọc và xử lý file Excel được xây dựng bằng Streamlit.

## ✨ Tính năng

- 📁 **Upload và đọc file Excel** (.xlsx, .xls)
- 📊 **Xem dữ liệu** từ nhiều sheet khác nhau
- 🔍 **Tìm kiếm và lọc** dữ liệu trong file
- 📈 **Xem thống kê mô tả** của dữ liệu
- 💾 **Xuất dữ liệu** ra CSV hoặc Excel
- ℹ️ **Thông tin chi tiết** về các cột và dữ liệu

## 🚀 Cài đặt

### Yêu cầu hệ thống

- Python 3.8 trở lên

### Các bước cài đặt

1. **Clone repository hoặc tải xuống project**

2. **Cài đặt các thư viện cần thiết:**
   ```bash
   pip install -r requirements.txt
   ```

## 📖 Cách sử dụng

1. **Chạy ứng dụng:**
   ```bash
   streamlit run app.py
   ```

2. **Sử dụng ứng dụng:**
   - Upload file Excel qua sidebar bên trái
   - Chọn sheet muốn xem từ dropdown
   - Khám phá dữ liệu với các tùy chọn hiển thị
   - Tìm kiếm và lọc dữ liệu
   - Xem thống kê mô tả
   - Tải xuống dữ liệu đã xử lý

## 📋 Định dạng file hỗ trợ

- ✅ `.xlsx` (Excel 2007+)
- ✅ `.xls` (Excel 97-2003)

## 📦 Dependencies

- `streamlit` - Framework để xây dựng ứng dụng web
- `pandas` - Xử lý và phân tích dữ liệu
- `openpyxl` - Đọc và ghi file Excel (.xlsx)

## 🛠️ Cấu trúc project

```
Rexcel_V00-main/
├── app.py              # File chính của ứng dụng
├── demo_data.xlsx      # File dữ liệu mẫu
├── requirements.txt    # Danh sách các thư viện cần thiết
└── README.md          # File hướng dẫn này
```

## 📝 Ghi chú

- Ứng dụng hỗ trợ hiển thị tối đa 100 dòng mặc định (có thể tắt để xem toàn bộ)
- Dữ liệu xuất ra CSV sử dụng encoding UTF-8 với BOM để hỗ trợ tiếng Việt
- Tất cả các sheet trong file Excel đều có thể được xem và xử lý

## 👨‍💻 Tác giả

Made with ❤️ by Streamlit

