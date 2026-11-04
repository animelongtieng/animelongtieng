# AnimeLồngTiếng – Source project

- `index.html`: trang chủ, tìm kiếm, lọc anime và danh sách phim.
- `watch.html`: trang xem phim riêng, mở theo dạng `watch.html?id=1`.
- `style.css`: giao diện responsive dùng chung.
- `data.js`: dữ liệu anime mẫu và hàm tiện ích.
- `app.js`: chức năng trang chủ.
- `watch.js`: trình phát, chọn tập, URL video và anime liên quan.
- `assets/`: thư mục đặt poster/logo.

## Chạy thử
Giải nén ZIP, mở thư mục bằng VS Code và chạy `index.html` bằng Live Server. Chọn một anime trên trang chủ để chuyển sang trang xem riêng.

## Lưu ý
Đây là frontend demo, chưa có API, máy chủ hoặc database trung tâm. Dữ liệu và URL video lưu bằng localStorage trên trình duyệt hiện tại. Video không đi kèm dự án; chỉ sử dụng nguồn bạn có quyền sử dụng. HLS có thể cần thư viện phát riêng. Phiên bản này không có tài khoản người xem hoặc trang quản trị.
