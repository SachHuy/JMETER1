1. Tổng Quan
Chương trình kiểm thử được thực hiện bằng JMeter nhằm đánh giá hiệu suất và tính ổn định của hệ thống. Trong báo cáo này, chúng tôi sẽ trình bày về môi trường kiểm thử, các kịch bản kiểm thử, kết quả chính và các phát hiện quan trọng.

2. Môi Trường Kiểm Thử
Công cụ kiểm thử: Apache JMeter 5.4.1
Mục Tiêu Kiểm Thử: Đánh giá hiệu suất của ứng dụng web trong điều kiện tải nặng.

3. Các Kịch Bản Kiểm Thử
Kịch Bản 1: Tải Trang Chính

Mô tả: Mô phỏng hành vi của người dùng truy cập trang chính của ứng dụng.
Thực Hiện: Tạo yêu cầu HTTP GET đến trang chính.
Số Lượng Người Dùng: 100
Kết Quả: Đánh giá thời gian phản hồi trung bình và tỷ lệ lỗi.
Kịch Bản 2: Đăng Nhập

Mô tả: Mô phỏng hành vi của người dùng đăng nhập vào hệ thống.
Thực Hiện: Gửi yêu cầu HTTP POST với thông tin đăng nhập.
Số Lượng Người Dùng: 50
Kết Quả: Đánh giá thời gian đăng nhập thành công và tỷ lệ thất bại.
4. Kết Quả Kiểm Thử
Kịch Bản 1: Tải Trang Chính
Thời Gian Phản Hồi Trung Bình: 850ms
Tỷ Lệ Lỗi: 0%
Kịch Bản 2: Đăng Nhập
Thời Gian Đăng Nhập Thành Công Trung Bình: 1200ms
Tỷ Lệ Đăng Nhập Thất Bại: 2%
5. Phát Hiện và Ghi Chú
Thời gian phản hồi trung bình và tỷ lệ lỗi trong kịch bản tải trang chính đều trong ngưỡng chấp nhận được.
Tuy nhiên, tỷ lệ đăng nhập thất bại trong kịch bản đăng nhập vượt quá mức chấp nhận, cần kiểm tra và tối ưu hóa quá trình đăng nhập.
6. Kết Luận
Kiểm thử bằng JMeter đã cung cấp cái nhìn tổng quan về hiệu suất và tính ổn định của ứng dụng web. Kết quả này có thể được sử dụng để cải thiện hiệu suất và trải nghiệm người dùng của hệ thống.

