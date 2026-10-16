# YÊU CẦU ĐẦU RA

## Phần 1: Báo cáo phân tích
 
 ## 1: Báo cáo phân tích
 
 - Input: Là văn bản viết bằng Markdown, gồm, tên biến, câu lệnh Terminal,...

 - Output: Là tài liệu được render trên StackEdit với tiêu đề rõ ràng, tên biến dạng inline code, các khối lệnh tách riêng, code Python được tô màu cú pháp, bảng dễ đọc và ô đánh dấu tiến độ

  ## 2: Source code

  MỘT FILE .MD CHỨA ĐẦY ĐỦ KHỐI CODE, BẲNG SO SÁNH VÀ MỘT TASK LIST KIỂM TRA TIẾN ĐỘ CÀI ĐẶT LÀ

## 1. Cấu hình môi trường & Biến hệ thống

Trước khi chạy ta cần cho Terminal chạy dòng lệnh này:

```bash
pip install RPi.GPIO adafruit-circuitpython-dht
```

## Khối code

```
Dây là code python
```

## Bảng so sánh

| Tiêu chí so sánh | Cảm biến loại cũ (DHT11) | Cảm biến loại mới (DHT22 / Capacitive) |
| :--- | :--- | :--- |
| **Độ chính xác** | Thấp  | Cao  |
| **Độ bền trong môi trường ẩm** | Kém  | Cao  |
| **Khoảng đo độ ẩm** | 20 - 80% | 0% - 100% |

## Task List

- [x] Lắp đặt phần cứng và kết nối nguồn điện an toàn
- [ ] Kiểm tra kết nối chân tín hiệu SENSOR_PIN trên bo mạch
- [ ] Chạy thử nghiệm script Python đọc giá trị cảm biến
- [ ] Kiểm tra cơ chế tự động ngắt/mở của rơ-le máy bơm
- [ ] Hoàn tất bàn giao hệ thống cho trang trại

  
