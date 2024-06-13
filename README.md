1.Mục tiêu:

-Sử dụng jMeter để tạo một kịch bản kiểm tra mô phỏng người dùng truy cập trang web https://phenikaa-uni.edu.vn/vi.

-Chạy kịch bản kiểm tra và ghi lại kết quả.

-Phân tích kết quả kiểm tra, bao gồm thời gian phản hồi, số lượng yêu cầu thành công, số lượng yêu cầu thất bại, v.v.

-Dựa trên kết quả phân tích, đưa ra kết luận về hiệu năng của trang web.

2.Kịch bản kiểm tra:

-Thread Group:

Số lượng thread: 1000

Thời gian chạy: 23 giây

Ramp-up period: 10 giây

-HTTP Request:

URL: https://phenikaa-uni.edu.vn/vi

Method: GET

Content encoding: UTF-8

-Listeners:

View Results Tree

Aggregate Report

3.Kết quả kiểm tra:

![image](https://github.com/hungkun23/Jmeter/assets/164150837/db555b78-19a2-4eed-96b1-a4685f82b82a)

4.Phân tích kết quả kiểm tra:

-Số lượng yêu cầu thành công: 97,1%

-Số lượng yêu cầu thất bại: 2,9%

-Thời gian phản hồi trung bình: 14,64 ms

-Thời gian phản hồi trung vị: 15,03 ms

-Thời gian phản hồi percentil 90: 70 ms

-Chuyển tải: 16 yêu cầu/giây

5.Kết luận:

Trang web https://phenikaa-uni.edu.vn/vi có hiệu năng tốt. Số lượng yêu cầu thành công cao (97,1%), số lượng yêu cầu thất bại rất thấp (0,29%). Thời gian phản hồi trung bình, trung vị và percentil 90 đều ở mức thấp (dưới 100 ms). Chuyển tải của trang web cũng khá cao (16 yêu cầu/giây).

6.Hình ảnh tổng quát

![image](https://github.com/hungkun23/Jmeter/assets/164150837/a2a23d00-3c8b-489f-8cdc-0532e6a258c0)
