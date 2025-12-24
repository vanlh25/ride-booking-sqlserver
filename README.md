# HeQTCSDL
# QuanLyDatXe-SQLServer 🚖

**Final Project: Database Management System – Ride Booking Desktop App **  

Ứng dụng **QuanLyDatXe-ADO** là hệ thống **đặt xe online dạng desktop**, được xây dựng với C#
Người dùng có thể đặt xe, quản lý chuyến đi, xuất báo cáo, tất cả thao tác dữ liệu được thực hiện trực tiếp trên cơ sở dữ liệu SQLServer.

---

## 🔹 Features / Tính năng chính

### 1️⃣ User Management
- Đăng ký tài khoản mới và đăng nhập.  
- Kiểm tra tính hợp lệ dữ liệu: email, password, username.  
- Phân quyền Admin / User (Admin quản lý toàn bộ chuyến đi).  

### 2️⃣ Ride Booking
- Chọn điểm đi, điểm đến, loại xe, thời gian đặt.  
- Tính toán **ước lượng chi phí** dựa trên loại xe và quãng đường.  
- Lưu dữ liệu trực tiếp vào cơ sở dữ liệu qua **ADO.NET**.  

### 3️⃣ Ride Management
- Hiển thị danh sách tất cả chuyến đi trong **DataGrid / Table**.  
- Lọc theo trạng thái: Đang chờ, Đang di chuyển, Hoàn tất.  
- Admin có thể **cập nhật trạng thái chuyến đi**.  

### 4️⃣ Reporting / Export
- Xuất dữ liệu thành **CSV hoặc Excel**.  
- Thống kê số chuyến đi theo ngày, tháng.  
- Thống kê doanh thu tổng (nếu có chi phí).  

### 5️⃣ User Interface
- Giao diện **WinForms / WPF** trực quan, dễ thao tác.  
- Menu, button, table, form nhập liệu đầy đủ.  
- Icon và màu sắc phân biệt các chức năng.  

---

## 🔹 Technologies / Công nghệ sử dụng
- **Ngôn ngữ:** C#  
- **Framework:** Windows Forms
- **Database:** SQL Server 
- **IDE:** Visual Studio 2022  
- **OS:** Windows 10 trở lên  

---
```bash
git clone https://github.com/vanlh25/QuanLyDatXe-ADO.git
