# Dự báo cổ phiếu VCB bằng ARIMA
Thu thập, xử lý dữ liệu cổ phiếu VCB từ Yahoo Finance và áp dụng mô hình ARIMA để dự báo giá

## Thông số sau huấn luyện

<div align="center">

<img width="752" height="562" alt="rs1" src="https://github.com/user-attachments/assets/bc21cdc4-8408-4ca8-80b2-a4230d701ac3" />
<br>
<small>Hình 1: Biểu đồ diagnostics sau khi huấn luyện</small>

<br><br>

<img width="807" height="482" alt="rs2" src="https://github.com/user-attachments/assets/1a730381-5224-4dc4-818b-052506c89ba6" />
<br>
<small>Hình 2: Bảng chi tiết thống kê</small>
</div>
Prob(Q) = 0.92 > 0.05 => phần dư gần như ngẫu nhiên, cho thấy mô hình ARIMA đã bắt được hầu hết các mẫu tự tương quan trong dữ liệu. Prob(JB) = 0.00 < 0.05 => phần dư không tuân theo phân phối chuẩn; mô hình có thể không hoàn toàn thỏa mãn giả định chuẩn, nhưng điều này ít ảnh hưởng đến khả năng dự báo.

## Kết quả (60 ngày)

<div align="center">

<img width="1266" height="647" alt="rs3" src="https://github.com/user-attachments/assets/77fcfa48-844d-4efd-945d-3483670e1378" />
<br>
<small>Hình 3: Dự báo 60 ngày</small>

</div>

