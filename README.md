# Chat Device V4

Ứng dụng chat và chia sẻ file theo cơ chế người dùng Android chủ động cấp quyền/chọn dữ liệu.

## Thành phần
- server: Node.js + Express + WebSocket + JWT
- admin-web: trang quản trị
- android-app: ứng dụng Android
- render.yaml: cấu hình deploy Render

## Local
cd server && npm install && ADMIN_USER=admin ADMIN_PASSWORD=change-me npm start

Khi chạy Internet dùng HTTPS/WSS. File upload hiện lưu filesystem để thử nghiệm; triển khai lâu dài nên dùng object storage.
