# Inventory Analytics Project

## Mô tả
Dự án này tập trung vào xây dựng một kho dữ liệu (Data Warehouse) để phân tích dữ liệu về inventory. Sử dụng SQL Server Integration Services (SSIS) để xử lý dữ liệu từ tập dữ liệu gốc, SQL Server Analysis Services (SSAS) để xây dựng các cube phân tích, và Power BI để tạo các báo cáo và trực quan hóa.

## Hướng dẫn cài đặt
### Yêu cầu
- Visual Studio 2022
- SQL Server (bản mới nhất được khuyến nghị)
- Power BI Desktop

### Cài đặt
1. Clone dự án từ repository GitHub.
2. Mở Visual Studio 2022 và mở solution của dự án.
3. Thiết lập kết nối với cơ sở dữ liệu SQL Server và tập dữ liệu gốc.
4. Chạy các gói SSIS để xử lý dữ liệu và tạo các bảng dim và fact.
5. Xây dựng các cube phân tích trong SSAS.
6. Sử dụng Power BI để kết nối đến cube SSAS và tạo các báo cáo và trực quan hóa.

## Hướng dẫn sử dụng
1. Mở Power BI Desktop.
2. Kết nối đến cube SSAS đã xây dựng từ dự án.
3. Tạo các bảng điều khiển, biểu đồ, và báo cáo dựa trên dữ liệu từ cube.
4. Thực hiện phân tích và tùy chỉnh báo cáo theo nhu cầu của bạn.

## Tài liệu kỹ thuật
- File SSIS Package Files (.dtsx)
- File Backup SQL Server
- File SSAS (Analysis Services)
- Tệp Excel SSAS (ssas.xlsx)
- Tệp Power BI (ssas.pbix)
