# VLE Compass — Bản điện thoại

Bản web dành cho Safari trên iPhone và Chrome trên Android, có biểu tượng thêm vào màn hình chính. Không cần App Store, backend, tài khoản hoặc khóa API.

## Bật website một lần

Chủ kho mở:

https://github.com/sonnguyen31241025656-tech/xl/settings/pages

Trong **Build and deployment**:

1. **Source**: chọn **Deploy from a branch**.
2. **Branch**: chọn **main**.
3. Thư mục: chọn **/docs**.
4. Nhấn **Save** và chờ GitHub báo website đã được phát hành.

Địa chỉ sau khi phát hành:

https://sonnguyen31241025656-tech.github.io/xl/

Tài liệu này không xác nhận Pages đã được bật. Các tệp website đã được chuẩn bị; trạng thái xuất bản phụ thuộc cài đặt GitHub Pages của kho.

## Mở trên điện thoại

- **iPhone:** mở link bằng Safari → Chia sẻ → Thêm vào màn hình chính → Thêm. Bật “Mở dưới dạng ứng dụng web” nếu thiết bị có tùy chọn đó.
- **Android:** mở link bằng Chrome → menu ⋮ → Thêm vào màn hình chính hoặc Cài đặt ứng dụng.
- Hướng dẫn ngay trên website: `cai-dat.html`.

Mở khi có mạng ít nhất một lần và chờ tải xong để lưu bản demo cho lần dùng không có mạng. Bộ nhớ có thể bị trình duyệt hoặc người dùng xóa; đây không phải cam kết lưu trữ vĩnh viễn.

Trong ứng dụng: **Cá nhân → Demo Mode → Nạp bộ dữ liệu trình diễn** để thử vòng nhân viên → Buddy → Process Owner → HR.

## Đã kiểm tra

- Viewport 390×844 và 360×800, touch targets, font biểu mẫu 16px, điều hướng 5 tab.
- Manifest, icon 180/192/512px và bộ nhớ offline có phạm vi `/xl/`.
- Tải lại khi mất mạng; đọc tài liệu, thực hành COD, gửi check-in và giữ tiến độ.
- Không phát hiện lỗi JavaScript trong các luồng trên.

Kiểm tra dùng Chromium mô phỏng kích thước điện thoại. Chưa xác minh trên iPhone/Android thật hoặc trình duyệt Safari thật. Camera là tùy chọn; luồng “Thử quét QR mẫu” không cần camera.

Toàn bộ nội dung và số liệu là giả định phục vụ dự án học thuật. Dữ liệu được lưu riêng trên từng trình duyệt/thiết bị; điện thoại và máy tính không tự đồng bộ. Không có tin nhắn hoặc thông báo nào được gửi ra ngoài ứng dụng.
