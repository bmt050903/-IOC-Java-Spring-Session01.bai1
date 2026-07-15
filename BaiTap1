[Bài tập] Phân tích mô hình Client - Server cho ứng dụng Quản lý sản phẩm
Giả sử người dung muốn xem danh sách sản phẩm:
1.	Client: Trình duyệt sẽ gửi Request như thế nào? (URL dự kiến, HTTP Method là GET hay POST?).
-	Người dùng mở trình duyệt và truy cập địa chỉ: http://localhost:8080/products
-	Trình duyệt sẽ gửi một HTTP Request đến Server với: 
+ URL: /products 
+ HTTP Method: GET
2.	Server: Ứng dụng Spring Boot sẽ làm gì khi nhận yêu cầu? (Xử lý logic, gọi dữ liệu ở đâu?).
-	Khi nhận được yêu cầu GET /products, Server sẽ:
+ Tiếp nhận Request thông qua Controller.
+ Controller gọi Service để xử lý nghiệp vụ.
+ Service gọi Repository để lấy danh sách sản phẩm.
+ Sau khi lấy được dữ liệu, Server chuẩn bị Response để gửi về Client.
3.	Database: Đóng vai trò gì trong yêu cầu này? (Tạm thời giả lập bằng bộ nhớ RAM).
-	Database có nhiệm vụ lưu trữ danh sách sản phẩm và cung cấp dữ liệu khi Server yêu cầu.

4.	Response: Server trả về định dạng gì cho Client? (HTML hay JSON?).
-	Định dạng Response là JSON
-	Client nhận dữ liệu và hiển thị danh sách sản phẩm cho người dùng.

