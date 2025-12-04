# Sprint Review – Tính năng: Đăng nhập hệ thống (Login)

## (A) Mục tiêu của buổi Sprint Review
- Xác nhận tính năng đăng nhập hoạt động đúng với các trường hợp thực tế.
- Lấy phản hồi từ người dùng và stakeholders về giao diện, trải nghiệm đăng nhập.
- Ghi nhận các đề xuất cải tiến hoặc phát hiện lỗi để ưu tiên cho Sprint tiếp theo.

## (B) Nội dung mở đầu cuộc họp
**Product Owner:**
"Chào mọi người, mục tiêu của Sprint này là hoàn thiện và kiểm thử tính năng đăng nhập hệ thống. Đây là bước đầu tiên và quan trọng để người dùng truy cập các chức năng khác, nên chúng tôi muốn đảm bảo trải nghiệm đăng nhập thật mượt mà và an toàn."

**Scrum Master:**
"Cảm ơn PO. Xin nhắc lại, buổi Sprint Review hôm nay kéo dài 30 phút, mọi người tập trung vào việc quan sát demo, đặt câu hỏi và phản hồi. Hãy chia sẻ ý kiến một cách cởi mở để giúp sản phẩm tốt hơn."

**Dev Lead:**
"Em sẽ demo tính năng đăng nhập với các trường hợp: đăng nhập thành công, nhập sai mật khẩu, và tài khoản bị khóa. Mời mọi người theo dõi."

## (C) Các bước demo tính năng
1. Dev mở giao diện trang đăng nhập trên trình duyệt.
2. Sử dụng tài khoản mẫu hợp lệ, nhập email và mật khẩu đúng, nhấn Đăng nhập. Hệ thống chuyển sang dashboard và hiển thị tên người dùng.
3. Đăng xuất, sau đó nhập lại email đúng nhưng mật khẩu sai. Hệ thống báo lỗi "Sai mật khẩu, vui lòng thử lại".
4. Thử đăng nhập bằng tài khoản đã bị khóa. Hệ thống hiển thị thông báo "Tài khoản đã bị khóa, liên hệ quản trị viên".
5. Dev trình bày các biện pháp bảo mật như ẩn mật khẩu, giới hạn số lần đăng nhập sai.
6. Dev cho stakeholders xem log hệ thống ghi nhận các lần đăng nhập thất bại.
7. Kết quả mong đợi: Stakeholders thấy hệ thống phản hồi đúng với từng trường hợp, giao diện rõ ràng, thông báo dễ hiểu, và không có lỗi phát sinh.
