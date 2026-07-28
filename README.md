# Phân Tích Dữ Liệu Bán Hàng Pizza (Pizza Sales Data Analysis)

## Tổng Quan Project
Project này phân tích dữ liệu bán hàng pizza bằng **SQL** và **Excel** nhằm xác định xu hướng bán hàng, hành vi khách hàng và hiệu suất sản phẩm. Mục tiêu là tạo ra các insight kinh doanh cụ thể và xây dựng một dashboard tương tác phục vụ việc ra quyết định.

---

## Công Cụ Sử Dụng
- SQL
- Microsoft Excel
- Pivot Tables
- Pivot Charts
- Data Cleaning (làm sạch dữ liệu)
- Dashboard Visualization

---

## Câu Hỏi Phân Tích Chính
- Khung giờ nào có lượng đơn hàng cao nhất?
- Danh mục pizza nào tạo ra doanh thu cao nhất?
- Sản phẩm nào bán chạy nhất và bán chậm nhất?
- Doanh số bán hàng thay đổi như thế nào theo ngày và theo tháng?

---

## Các Chỉ Số KPI Chính
- Tổng doanh thu (Total Revenue)
- Tổng số đơn hàng (Total Orders)
- Giá trị đơn hàng trung bình (Average Order Value)
- Tổng số pizza đã bán (Total Pizzas Sold)
- Số pizza trung bình mỗi đơn hàng (Average Pizzas per Order)

---

## Tính Năng Dashboard
- Xu hướng bán hàng theo ngày và theo giờ
- Phân tích doanh thu
- Hiệu suất theo danh mục và kích cỡ pizza
- Trực quan hóa sản phẩm bán chạy nhất
- Pivot Chart tương tác

---
## Phát Hiện Chính (Key Findings)
- Danh mục Classic ghi nhận số lượng đơn hàng và tổng số pizza bán ra cao nhất trong tất cả các danh mục. → Gợi ý: nên ưu tiên đảm bảo nguồn nguyên liệu ổn định cho nhóm Classic vì đây là danh mục chủ lực, đồng thời cân nhắc mở rộng thêm biến thể trong dòng sản phẩm này.
- Pizza cỡ Large (Lớn) đóng góp doanh thu cao nhất trong tất cả các kích cỡ. → Gợi ý: có thể đẩy mạnh chương trình khuyến khích khách hàng nâng cấp lên size Large (upsize) tại các điểm bán hoặc trên kênh đặt hàng online.
- Nhu cầu khách hàng đạt đỉnh trong khung giờ 12h–13h và 16h–20h, đặc biệt vào tối thứ Sáu và thứ Bảy. → Gợi ý: nên bố trí thêm nhân sự và tối ưu quy trình bếp trong các khung giờ cao điểm này để giảm thời gian chờ và tăng trải nghiệm khách hàng.
- Classic Deluxe Pizza là sản phẩm bán chạy nhất với 2.453 pizza được bán ra. → Gợi ý: có thể dùng sản phẩm này làm "món chủ lực" trong các chiến dịch marketing hoặc combo khuyến mãi.
- Brie Carre Pizza ghi nhận hiệu suất thấp nhất, cả về số lượng đơn hàng lẫn doanh thu. → Gợi ý: cần xem xét lại menu — có thể cải tiến công thức, điều chỉnh giá, hoặc loại bỏ sản phẩm này để tối ưu chi phí vận hành.

---
## Các File Đính Kèm
- `pizza_sales.sql` → Câu lệnh SQL dùng để phân tích dữ liệu
- `dashboard.xlsx` → Dashboard Excel và các Pivot Table
- `dashboard.png` → Ảnh preview dashboard

---
## Kết Quả Project
Project này cung cấp các insight dựa trên dữ liệu về hành vi mua hàng của khách hàng, xu hướng bán hàng và hiệu suất sản phẩm thông qua phân tích SQL kết hợp với dashboard Excel tương tác, giúp hỗ trợ việc ra quyết định kinh doanh dựa trên dữ liệu.

