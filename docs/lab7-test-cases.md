# Lab 7: Test Cases - FreelancerConnect 5Stars

## Tổng quan
Tài liệu test case chi tiết cho các chức năng của hệ thống FreelancerConnect 5Stars.

## Test Cases cho FR01 - Authentication

### TC-001: Đăng nhập thành công
- **Mô tả**: Người dùng đăng nhập với thông tin hợp lệ
- **Điều kiện tiên quyết**: Tài khoản đã được tạo
- **Bước thực hiện**:
  1. Nhập email hợp lệ
  2. Nhập mật khẩu đúng
  3. Click "Đăng nhập"
- **Kết quả mong đợi**: Đăng nhập thành công, chuyển đến trang chủ

### TC-002: Đăng ký tài khoản mới
- **Mô tả**: Người dùng tạo tài khoản mới
- **Bước thực hiện**:
  1. Nhập thông tin cá nhân
  2. Chọn role (Client/Freelancer)
  3. Xác nhận đăng ký
- **Kết quả mong đợi**: Tài khoản được tạo thành công

## Test Cases cho FR02 - Post Project

### TC-003: Đăng dự án thành công
- **Điều kiện tiên quyết**: Đã đăng nhập với role Client
- **Bước thực hiện**:
  1. Điền form dự án
  2. Thiết lập ngân sách
  3. Đăng dự án
- **Kết quả mong đợi**: Dự án được đăng thành công

## Test Cases cho FR03 - Search & Proposal

### TC-004: Tìm kiếm dự án
- **Điều kiện tiên quyết**: Đã đăng nhập với role Freelancer
- **Bước thực hiện**:
  1. Nhập từ khóa tìm kiếm
  2. Áp dụng bộ lọc
  3. Xem kết quả
- **Kết quả mong đợi**: Hiển thị danh sách dự án phù hợp

### TC-005: Nộp proposal
- **Bước thực hiện**:
  1. Chọn dự án
  2. Viết proposal
  3. Đặt giá
  4. Gửi proposal
- **Kết quả mong đợi**: Proposal được gửi thành công

## Test Cases cho FR04 - Contract & Payment

### TC-006: Tạo hợp đồng Escrow
- **Điều kiện tiên quyết**: Proposal được chấp nhận
- **Bước thực hiện**:
  1. Tạo hợp đồng
  2. Thiết lập điều khoản thanh toán
  3. Ký hợp đồng
- **Kết quả mong đợi**: Hợp đồng Escrow được tạo

### TC-007: Thanh toán qua Escrow
- **Bước thực hiện**:
  1. Client nạp tiền vào Escrow
  2. Freelancer hoàn thành công việc
  3. Client xác nhận và giải ngân
- **Kết quả mong đợi**: Thanh toán thành công

---
*Cập nhật: Lab 7 hoàn thiện với đầy đủ test cases chi tiết*