
# Đề tài 3: Website Quảng bá Sản phẩm (WordPress)

**Môn học:** Triển khai và Quản trị Hệ thống Phần mềm
**Mã SV:** dtc245180074

## Kiến trúc hệ thống

Hệ thống được đóng gói hoàn toàn bằng Docker Compose bao gồm:

- **Web Server:** WordPress + Nginx (Reverse Proxy & HTTPS)
- **Database:** MySQL 8.0 + phpMyAdmin
- **Monitoring:** Prometheus + Grafana + cAdvisor + Nginx Exporter
- **Logging:** Loki + Promtail

## Hướng dẫn khởi chạy

1. Đảm bảo Docker Desktop đã được bật.
2. Chạy lệnh: `docker compose up -d`
3. Địa chỉ truy cập các dịch vụ:
   - WordPress Website: https://localhost
   - phpMyAdmin: https://localhost/phpmyadmin/
   - Grafana Dashboard: http://localhost:3000 (User/Pass: admin/admin)
