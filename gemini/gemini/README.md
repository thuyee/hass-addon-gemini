## Gemini Web API Add-on cho Home Assistant

### 🔧 Cài đặt
1. Tạo thư mục `/config/gemini-web-api/`
2. Tạo file `my_cookie.txt` bên trong đó
3. Dán cookie từ Gemini Web vào file này

### 🍪 Lấy cookie
- Truy cập [gemini.google.com](https://gemini.google.com) bằng trình duyệt ẩn danh
- Đăng nhập → chat một đoạn → mở Developer Tools (F12)
- Tab Network → chọn request → copy toàn bộ cookie
- Mở `cookie.html` → dán cookie → bấm Trích xuất → copy kết quả vào `my_cookie.txt`

### 🚀 Khởi động Add-on
- Vào Add-on Store → Repositories → thêm link repo GitHub
- Cài Gemini Web API từ Add-on Store
- Truy cập API tại `http://homeassistant.local:5002/v1`
