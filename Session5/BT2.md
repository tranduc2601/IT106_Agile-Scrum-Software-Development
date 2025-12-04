# Product Backlog Item (PBI)

**Title:** Thêm bộ lọc thống kê hoạt động theo ngày

**Business Requirement:**
Là trưởng phòng vận hành, tôi muốn có bộ lọc thống kê hoạt động theo ngày hoặc trong 24 giờ gần nhất để dễ dàng kiểm tra chi tiết hiệu suất làm việc của từng người dùng, thay vì chỉ xem báo cáo tổng hợp theo tuần.

## Acceptance Criteria

- [ ] Người dùng có thể chọn ngày cụ thể để xem thống kê hoạt động của từng thành viên.
- [ ] Người dùng có thể chọn khoảng thời gian 24 giờ gần nhất để xem thống kê.
- [ ] Khi chọn bộ lọc, hệ thống hiển thị chính xác dữ liệu theo ngày hoặc 24 giờ gần nhất, không gộp chung theo tuần.

### Given–When–Then
1. **Given** người dùng đang ở trang thống kê, **When** chọn một ngày bất kỳ, **Then** hệ thống hiển thị thống kê hoạt động đúng với ngày đó.
2. **Given** người dùng đang ở trang thống kê, **When** chọn bộ lọc 24 giờ gần nhất, **Then** hệ thống hiển thị thống kê hoạt động trong 24 giờ gần nhất.
3. **Given** người dùng đã áp dụng bộ lọc, **When** xem báo cáo, **Then** dữ liệu không bị gộp chung theo tuần mà hiển thị chi tiết theo ngày hoặc 24 giờ.
