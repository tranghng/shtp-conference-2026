# Thư mục ảnh "Khoảnh khắc sự kiện"

**Chỉ cần tải ảnh mới vào thư mục này (jpg, jpeg, png, webp) là banner trên website tự cập nhật — không cần sửa code.**

- Ảnh được chia thành 4 thư mục con, **chạy lần lượt theo thứ tự thư mục**: `1-Sanh VIP` → `2-Trien lam` → `3-Toan the` → `4-Chuyen de`.
- Trong mỗi thư mục, ảnh chạy theo thứ tự tên file (số tăng dần). Nên đặt tên `01.jpg`, `02.jpg`, `03.jpg`...
- Ảnh để thẳng trong `images/events/` (không nằm trong thư mục con) sẽ chạy sau cùng.
- Muốn thêm nhóm mới: tạo thư mục mới với số thứ tự phía trước (ví dụ `5-Giao luu`).
- Nên dùng ảnh ngang, tỷ lệ gần 16:10, dung lượng mỗi ảnh dưới ~500 KB để trang tải nhanh.
- Gỡ ảnh: xoá file khỏi thư mục.

## Video recap (cột bên trái)
Mở file `config.json` trong thư mục này và dán link vào `"video"`:
- YouTube: `"video": "https://www.youtube.com/watch?v=XXXXXXXXXXX"`
- Facebook: `"video": "https://www.facebook.com/.../videos/..."`
- File mp4 tải lên cùng thư mục: `"video": "recap.mp4"` (và có thể thêm `"poster": "poster.jpg"`)

Để trống `"video": ""` thì hiện khung "Sắp được cập nhật".
