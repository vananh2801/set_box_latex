## Giới thiệu sơ lược về gói lệnh

### Nguyên nhân ra đời

- Đơn giản hoá bước tạo các khung nội dung mới theo mẫu có sẵn.
- Các khung được tạo tương thích tốt với gói lệnh `ex_test.sty` đã rất phổ biến hiện nay.
- Giải quyết được các vấn đề về lồng môi trường vào nhau, cũng như ẩn hiện môi trường được đóng khung.

### Một số lưu ý

- Gói lệnh nên đi kèm và khai báo phía sau hai gói `ex_test.sty` và `ntheorem.sty`.
- Chỉ nên cài đặt khung cho theorem hoặc environment mới hoặc đã áp dụng khung trước đó. Hạn chế áp dụng thêm các tác động khác ngoài gói này, có thể gây lỗi.

### Đôi lời muốn nói

- Gói lệnh hiện vẫn chưa phát triển câu lệnh để thầy cô tự tạo khung riêng như lệnh `\createbox` của gói lệnh `ex_test`.
