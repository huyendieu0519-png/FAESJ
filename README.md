# FAESJ

**FAESJ** là dự án Java Maven đa module, xử lý dữ liệu và đóng gói theo thuật toán bin-packing. Dự án được thiết kế để dễ mở rộng, dễ bảo trì, và phù hợp với teamwork chuyên nghiệp.

## 🧩 Cấu trúc module

- `core-engine`: xử lý dữ liệu, đọc ghi Excel, kết nối cơ sở dữ liệu
- `bin-packer`: API Spring Boot để đóng gói dữ liệu theo thuật toán bin-packing
- `app`: chứa KH575-FIAC.xlsx
- `config`: cấu hình hệ thống
- `reports`: xuất báo cáo kết quả
- `.mvn/`, `mvnw`, `mvnw.cmd`: Maven Wrapper giúp build dự án mà không cần cài Maven

## 🚀 Cách build dự án

```bash
./mvnw clean install
