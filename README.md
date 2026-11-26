# Bản đồ khái niệm 3D – Kiểm toán CNTT cấp độ 1

Trang web tương tác giúp học viên lớp **Kiểm toán Công nghệ thông tin cấp độ 1** nhìn thấy các khái niệm quan trọng của 3 chuyên đề và mối liên hệ giữa chúng trong không gian 3D.

- **Chuyên đề 1** – Tổng quan về kiểm toán CNTT (khái niệm, kiểm soát CNTT, rủi ro & trọng yếu, quy trình 4 giai đoạn)
- **Chuyên đề 2** – Kiểm toán hệ thống CNTT (quản trị, phát triển – mua sắm, vận hành, thuê khoán, BCP/DRP, an toàn thông tin, kiểm soát ứng dụng)
- **Chuyên đề 3** – Tiếp cận, chuẩn hóa, phân tích và truy vấn dữ liệu (chuẩn mực KTNN, CAATs, dữ liệu)

## Cách dùng

| Thao tác | Kết quả |
|---|---|
| Kéo chuột / vuốt | Xoay bản đồ |
| Cuộn / chụm 2 ngón | Phóng to, thu nhỏ |
| Bấm vào một nút | Xem giải thích, vị trí trong tài liệu và các liên hệ đi ra / đi vào |
| **Lộ trình học** (◀ ▶ hoặc phím ← →) | Đi lần lượt 36 khái niệm theo thứ tự nên học |
| Tìm kiếm | Gõ không dấu cũng được (vd: `rui ro`, `caats`) |
| Bật/tắt nhóm | Ẩn bớt nhóm để tập trung vào một phần |
| 📋 Danh sách khái niệm | Bảng tổng hợp 75 khái niệm để ôn tập |

Có thể gửi đường dẫn tới thẳng một khái niệm bằng cách thêm `#mã`, ví dụ `…/#rr` (Rủi ro CNTT), `…/#caats`, `…/#ksc`.

## Cấu trúc

- `index.html` – giao diện và đồ thị 3D (thư viện [3d-force-graph](https://github.com/vasturiano/3d-force-graph), tải qua CDN)
- `data.js` – danh sách khái niệm (`NODES`), mối liên hệ (`LINKS`) và lộ trình học (`PATH`). Sửa file này để bổ sung hoặc chỉnh nội dung.

Nội dung được tóm tắt từ tài liệu học tập Kiểm toán CNTT cấp độ 1; khi có khác biệt, tài liệu gốc là căn cứ.
