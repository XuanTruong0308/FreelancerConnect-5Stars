# Lab 6: UML Diagrams - FreelancerConnect 5Stars

## Tổng quan
Tài liệu này mô tả các sơ đồ UML cho hệ thống FreelancerConnect 5Stars.

## Use Case Diagram
- Đăng nhập/Đăng ký người dùng
- Đăng dự án
- Tìm kiếm và nộp proposal  
- Quản lý hợp đồng và thanh toán

## Class Diagram
```
User
- id: String
- name: String
- email: String
- role: UserRole

Project
- id: String
- title: String
- description: String
- budget: Double
- status: ProjectStatus

Proposal
- id: String
- projectId: String
- freelancerId: String
- price: Double
- description: String
```

## Sequence Diagram
Mô tả luồng xử lý cho các chức năng chính:
1. Quy trình đăng nhập
2. Quy trình đăng dự án
3. Quy trình nộp proposal
4. Quy trình thanh toán Escrow

## Activity Diagram
Mô tả các hoạt động trong hệ thống từ đầu đến cuối.

---
*Cập nhật: Lab 6 hoàn thiện với đầy đủ các sơ đồ UML*