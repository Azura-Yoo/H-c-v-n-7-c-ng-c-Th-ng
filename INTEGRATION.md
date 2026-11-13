# Tích hợp không gian Học Văn 6 vào Văn học số

## Tệp đã chuẩn bị
- `grade6/index.html`: giao diện và chức năng không gian Học Văn 6, được tách từ nền tảng Học Văn 7 và điều chỉnh cho khối 6.
- `grade6/stem-features.js`: các chức năng STEM được dùng bởi giao diện Văn 6.

## Đích tích hợp
Không gian Văn 6 phải được mở bên trong Worker của trang mẹ tại đường dẫn `/hoc-van-6`, cùng cấu trúc điều hướng và xác thực chung của Văn học số. Không thay thế trang mẹ, không sửa nội dung hay dữ liệu Văn 7.

## Trạng thái
Các tệp Văn 6 đã được đưa vào repository này trên nhánh `integrate-grade6`. Phần còn lại là ghép nội dung `grade6/index.html` vào route `/hoc-van-6` của Worker trang mẹ hiện hành và triển khai Worker đó. Không triển khai bản thay thế trang mẹ khi chưa có nguyên vẹn mã Worker đang chạy, vì Worker hiện tại còn có trang chủ và cổng giáo viên (/giao-vien).
