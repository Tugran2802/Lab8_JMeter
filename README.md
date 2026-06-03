# Lab8 JMeter
## Kiểm tra hiệu năng trang web
### Mục tiêu:

- Sử dụng jMeter để tạo một kịch bản kiểm tra mô phỏng người dùng truy cập trang web https://www.tinkercad.com
- Chạy kịch bản kiểm tra và ghi lại kết quả.
- Phân tích kết quả kiểm tra, bao gồm thời gian phản hồi, số lượng yêu cầu thành công, số lượng yêu cầu thất bại, v.v.
- Dựa trên kết quả phân tích, đưa ra kết luận về hiệu năng của trang web.
### Kịch bản kiểm tra:

- Thread Group:
  - Số lượng thread: 100
  - Thời gian chạy: 60 giây
  - Ramp-up period: 10 giây
- HTTP Request:
  - URL: https://www.tinkercad.com
  - Method: GET
  - Content encoding: UTF-8
- Listeners:
  - View Results Tree
  - Aggregate Report
### Kết quả kiểm tra:

<img width="1131" height="66" alt="image" src="https://github.com/user-attachments/assets/34e11c13-e0a5-4621-b765-4522d2ad6a8b" />


### Phân tích kết quả kiểm tra:

- Số lượng yêu cầu thành công: 38,471 yêu cầu (Tính từ lượng thành công ~5.12%).
- Số lượng yêu cầu thất bại: 712,917 yêu cầu (Ứng với tỉ lệ lỗi 94.88%).
- Thời gian phản hồi trung bình: 14 ms
- Thời gian phản hồi trung vị: 10 ms
- Thời gian phản hồi percentil 90: 17 ms
- Chuyển tải: 748.8 yêu cầu/giây
### Kết luận:

- Kịch bản giả lập tải quá lớn khiến hệ thống kích hoạt cơ chế bảo mật (Anti-DDoS/Tường lửa), lập tức chặn và từ chối 94.88% số lượng yêu cầu gửi đến. Hệ thống phản hồi lỗi ngay vòng ngoài nên thời gian phản hồi rất ngắn (17 ms). Kết quả kiểm thử đánh giá: Không đạt do lỗi bảo mật chặn tải, chưa phản ánh được năng lực xử lý thực tế của server.



