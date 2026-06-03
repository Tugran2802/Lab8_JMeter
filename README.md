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

<img width="1134" height="67" alt="image" src="https://github.com/user-attachments/assets/76da895b-488f-4e95-9a61-c366cdf60033" />


### Phân tích kết quả kiểm tra:

- Số lượng yêu cầu thành công: 
- Số lượng yêu cầu thất bại: 
- Thời gian phản hồi trung bình:
- Thời gian phản hồi trung vị: 
- Thời gian phản hồi percentil 90: 
- Chuyển tải: 
### Kết luận:


### Hình ảnh tổng quát


## Kiểm tra hiệu năng API

### Mục tiêu:

- Sử dụng jMeter để tạo một kịch bản kiểm tra mô phỏng người dùng truy cập API thời tiết 
- Chạy kịch bản kiểm tra và ghi lại kết quả.
- Phân tích kết quả kiểm tra, bao gồm thời gian phản hồi, số lượng yêu cầu thành công, số lượng yêu cầu thất bại, v.v.
- Dựa trên kết quả phân tích, đưa ra kết luận về hiệu năng của API.
### Kịch bản kiểm tra:

- Thread Group:
  - Số lượng thread: 100
  - Thời gian chạy: 60 giây
  - Ramp-up period: 10 giây
- HTTP Request:
  - URL: 
  - Method: GET
  - Content encoding: UTF-8
- Listeners:
  - View Results Tree
  - Aggregate Report
### Kết quả kiểm tra:



### Phân tích kết quả kiểm tra:

- Số lượng yêu cầu thành công: 
- Số lượng yêu cầu thất bại: 
- Thời gian phản hồi trung bình: 
