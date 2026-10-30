# BÁO CÁO BÀI TẬP / ĐỒ ÁN

## THÔNG TIN SINH VIÊN
- **Họ và tên:** Nguyễn Minh Đức
- **Mã số sinh viên:** 24810320326
- **Lớp:** D19QTANM1
- **Tên môn học:** Lập trình C# / Windows Forms
- **Tên bài tập:** BÀI TẬP 5.4: HỆ THỐNG QUẢN LÝ TIỆN ÍCH DỊCH VỤ & KHÁCH SẠN
(HOTEL MANAGEMENT SYSTEM)

---

## KẾT QUẢ THỰC HÀNH

- Giao diện chính
<img width="1289" height="794" alt="Screenshot 2026-10-30 090524" src="https://github.com/user-attachments/assets/85c2a25a-dcb4-4868-9a46-d8d7e76c5058" />

- Xác nhận thông tin khách hàng chưa có trong hệ thống - khách hàng mới
<img width="1284" height="788" alt="Screenshot 2026-10-30 090804" src="https://github.com/user-attachments/assets/02452f88-57d8-493b-a7fc-049cab725f30" />

- Xác nhận thông tin đặt phòng thành công
<img width="1283" height="792" alt="Screenshot 2026-10-30 090846" src="https://github.com/user-attachments/assets/e6d7dc36-e210-4789-8529-cc041aafc0a3" />

- Xem số tiền tạm tính (tiền phòng + dịch vụ đã sử dụng)
<img width="1284" height="797" alt="Screenshot 2026-10-30 090904" src="https://github.com/user-attachments/assets/3256630f-6240-47aa-aa53-29b657a93b7f" />

- Xác nhận thanh toán thành công + trạng thái phòng chuyển sang dọn dẹp
<img width="1283" height="791" alt="Screenshot 2026-10-30 090915" src="https://github.com/user-attachments/assets/9da27beb-e676-497e-8f3c-7eefe565f6c8" />

- Giao diện chọn các loại phòng khác nhau
<img width="1284" height="786" alt="Screenshot 2026-10-30 090943" src="https://github.com/user-attachments/assets/d39352dd-97e9-44b1-baed-f7a3448dc77a" />

## HƯỚNG DẪN CÀI ĐẶT VÀ CHẠY DỰ ÁN:
1. **Khởi tạo CSDL**:
   - Mở file `Database.sql` có sẵn trong thư mục dự án bằng SQL Server Management Studio (SSMS) hoặc Visual Studio.
   - Chạy toàn bộ script (Execute) để tự động tạo CSDL `HotelDB` cùng các bảng và dữ liệu mẫu.

2. **Cấu hình chuỗi kết nối**:
   - Mở file `DatabaseHelper.cs`.
   - Kiểm tra và đổi lại `Data Source` cho khớp với tên SQL Server trên máy chấm (Mặc định đang để kết nối tới `(localdb)\MSSQLLocalDB`).

3. **Chạy chương trình**:
   - Nhấn **F5** (hoặc nút Start) trên Visual Studio để chạy hệ thống.
