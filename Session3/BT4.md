# Ước lượng User Story bằng Planning Poker

**User Story:**
"Là người dùng, tôi muốn đăng nhập vào ứng dụng ngân hàng trực tuyến để có thể truy cập tài khoản và thực hiện các giao dịch."

**Điểm Story ước lượng (Planning Poker):**
- Thành viên 1: 8 điểm
- Thành viên 2: 13 điểm
- Thành viên 3: 8 điểm
- Thành viên 4: 13 điểm
- Thành viên 5: 8 điểm

**Thảo luận và đồng thuận:**
Sau khi mở bài, các thành viên có sự khác biệt giữa 8 và 13 điểm. 

**Lý do thành viên chọn 13 điểm:**
- Ứng dụng ngân hàng trực tuyến yêu cầu mức độ bảo mật cao với nhiều lớp xác thực (mật khẩu, OTP, sinh trắc học).
- Cần tích hợp với hệ thống xác thực đa yếu tố (MFA/2FA).
- Xử lý các trường hợp bảo mật: giới hạn số lần đăng nhập sai, khóa tài khoản tạm thời, phát hiện đăng nhập bất thường.
- Quản lý phiên đăng nhập an toàn, mã hóa dữ liệu, và tuân thủ các tiêu chuẩn bảo mật ngân hàng.

**Lý do thành viên chọn 8 điểm:**
- Cho rằng có thể tái sử dụng các thư viện xác thực có sẵn.
- Chức năng đăng nhập cơ bản đã quen thuộc với nhóm phát triển.

Sau khi thảo luận chi tiết về các yêu cầu bảo mật nghiêm ngặt trong lĩnh vực ngân hàng, nhóm đồng thuận rằng tính năng này đòi hỏi nhiều nỗ lực hơn do phải đảm bảo các tiêu chuẩn bảo mật cao và xử lý nhiều trường hợp đặc biệt.

**Kết quả ước lượng cuối cùng:**
- 13 điểm Story (mức độ khó rất cao)

**Ghi chú:**
Độ phức tạp cao do yêu cầu bảo mật nghiêm ngặt, tích hợp xác thực đa yếu tố, xử lý nhiều trường hợp ngoại lệ và tuân thủ các quy định về bảo mật ngân hàng.
