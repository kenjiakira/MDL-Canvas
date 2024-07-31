# Lệnh `id` - Tạo và Hiển Thị Căn Cước Công Dân

Lệnh `id` cho phép người dùng tạo hoặc xem thông tin căn cước công dân của họ. Lệnh này bao gồm các tính năng như tạo căn cước mới và hiển thị thông tin căn cước hiện có.

## Cấu hình

- **Tên lệnh:** `id`
- **Phiên bản:** 1.2.1
- **Quyền hạn:** 0 (Không yêu cầu quyền đặc biệt)
- **Tín dụng:** Hoàng Ngọc Từ
- **Danh mục lệnh:** Social
- **Cú pháp:** `.id [tên] | [ngày sinh] | [giới tính] | [địa chỉ]`
- **Thời gian chờ:** 10 giây

## Mô Tả

Lệnh `id` cho phép người dùng tạo một thẻ căn cước công dân với thông tin cá nhân, hoặc xem thông tin thẻ căn cước công dân hiện có của họ. Lệnh cũng cung cấp phản hồi nếu thông tin căn cước công dân đã tồn tại.

### Các Tùy Chọn

- **[tên]:** Tên đầy đủ của bạn.
- **[ngày sinh]:** Ngày sinh của bạn (định dạng dd/mm/yyyy).
- **[giới tính]:** Giới tính của bạn (Nam/Nữ).
- **[địa chỉ]:** Địa chỉ nơi bạn đang sống.

## Cách Sử Dụng

### Tạo Căn Cước Mới

Để tạo một căn cước công dân mới, hãy sử dụng cú pháp sau:


Lệnh này sẽ tạo một căn cước công dân mới với thông tin được cung cấp và gửi hình ảnh thẻ căn cước công dân của bạn.

### Xem Thông Tin Căn Cước

Nếu bạn đã có thông tin căn cước công dân, bạn có thể xem thông tin của mình bằng cách gọi lệnh mà không cần tham số bổ sung:


Lệnh này sẽ gửi thông tin căn cước công dân hiện có của bạn.

## Hướng Dẫn Hình Ảnh

Lệnh `id` cũng tạo ra một hình ảnh căn cước công dân. Hình ảnh này bao gồm các thông tin cá nhân và một ảnh đại diện được lấy từ Facebook. Hình ảnh được tạo và gửi dưới định dạng PNG.

### Tùy Chỉnh Hình Ảnh

- **Nền:** Hình ảnh nền có thể được thay đổi bằng cách cập nhật URL hoặc đường dẫn trong mã nguồn.
- **Ảnh Đại Diện:** Ảnh đại diện được lấy từ Facebook và có thể được cắt hình tròn bằng `jimp`.

## Cảnh Báo

- Đảm bảo rằng bạn đã có quyền truy cập cần thiết để lấy ảnh đại diện từ Facebook.
- Đảm bảo bạn đã cấu hình đường dẫn chính xác cho hình ảnh nền và các tệp liên quan.

## Liên Hệ

Nếu bạn gặp phải bất kỳ vấn đề nào hoặc cần hỗ trợ, hãy liên hệ với người phát triển hoặc kiểm tra các tài liệu hỗ trợ.

---

Chúc bạn sử dụng lệnh `id` thành công!
