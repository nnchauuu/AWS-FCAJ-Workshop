---
title: "Worklog Tuần 6"
date: 2026-07-06
weight: 6
chapter: false
pre: " <b> 1.6. </b> "
---

### Mục tiêu tuần 6:

* Tìm hiểu Amazon Relational Database Service (Amazon RDS).
* Hiểu vai trò của RDS trong việc triển khai và quản lý cơ sở dữ liệu quan hệ trên AWS.
* Thực hành chuẩn bị môi trường mạng để kết nối EC2 với RDS.
* Tạo RDS Database Instance và kiểm tra kết nối từ ứng dụng.
* Tìm hiểu backup, restore và dọn dẹp tài nguyên sau khi thực hành.

### Các công việc cần triển khai trong tuần này:

| Thứ | Công việc | Ngày bắt đầu | Ngày hoàn thành | Nguồn tài liệu |
| --- | --- | --- | --- | --- |
| 2 | - Tìm hiểu tổng quan về Amazon RDS. <br> - Nghiên cứu vai trò của RDS trong việc quản lý cơ sở dữ liệu quan hệ trên AWS. <br> - Tìm hiểu các hệ quản trị cơ sở dữ liệu được RDS hỗ trợ như MySQL, PostgreSQL, MariaDB, Oracle và SQL Server. | 25/05/2026 | 25/05/2026 | <https://000005.awsstudygroup.com/vi/> |
| 3 | - Thực hành các bước chuẩn bị môi trường cho RDS. <br> - Tạo VPC, EC2 Security Group và RDS Security Group. <br> - Ghi chú cách Security Group kiểm soát kết nối giữa EC2 và RDS. | 26/05/2026 | 26/05/2026 | <https://000005.awsstudygroup.com/vi/> |
| 4 | - Tạo DB Subnet Group cho RDS. <br> - Thực hành tạo EC2 Instance để dùng làm máy chủ kết nối đến database. <br> - Kiểm tra cấu hình mạng, subnet và security group trước khi tạo database. | 27/05/2026 | 27/05/2026 | <https://000005.awsstudygroup.com/vi/> |
| 5 | - Thực hành tạo RDS Database Instance. <br> - Kiểm tra endpoint, username, password và thông tin kết nối database. <br> - Triển khai ứng dụng mẫu và kiểm tra kết nối từ EC2 đến RDS. | 28/05/2026 | 28/05/2026 | <https://000005.awsstudygroup.com/vi/> |
| 6 | - Tìm hiểu chức năng backup và restore trong Amazon RDS. <br> - Nghiên cứu DB Snapshot, sao lưu tự động và khôi phục database. <br> - Thực hiện dọn dẹp tài nguyên sau khi hoàn thành bài thực hành và ghi lại tài liệu các bước triển khai. | 29/05/2026 | 29/05/2026 | <https://000005.awsstudygroup.com/vi/> |

### Kết quả đạt được tuần 6:

* Hiểu được vai trò của Amazon RDS trong việc quản lý cơ sở dữ liệu quan hệ trên AWS.
* Nắm được các thành phần quan trọng khi triển khai RDS như DB Instance, DB Subnet Group, endpoint và Security Group.
* Biết cách chuẩn bị VPC, EC2 Security Group và RDS Security Group để kết nối ứng dụng với database.
* Thực hành tạo EC2 Instance và RDS Database Instance.
* Kiểm tra được kết nối từ ứng dụng hoặc EC2 đến RDS thông qua endpoint.
* Hiểu cơ bản về backup, restore, DB Snapshot và sao lưu tự động trong RDS.
* Ghi nhớ việc dọn dẹp tài nguyên sau khi thực hành để tránh phát sinh chi phí.