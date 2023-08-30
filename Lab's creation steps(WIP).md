# Các bước dùng để tạo ra một bài lab trong V-Cyber War's platform

## Bước 1
- Xác định mục tiêu của bài lab nhằm hướng đến nội dung gì, lỗ hổng gì bảo mật nào.
- Bài làm được làm trong một tình huống như thế nào (để xác định cho việc dựng môi trường của sandbox).
- Kết quả cuối cùng như thế nào để được coi là nắm được kiến thức.

## Bước 2
- Sau khi biết được mục tiêu của bài lab thì chúng ta sẽ tiến hành việc xác định cấu hình mạng trong sandbox.
	- Trước mắt phải chỉnh được file `topology.yml` để cấu hình mạng, xác định image và flavor cho các máy ảo trong môi trường và khả năng kết nối của người dùng có thể dùng máy nào.


## Extras
- Trong docs của KYPO thì cũng có đề cập đến việc 2 người dùng 1 sandbox là **KHẢ THI**. Để có thể làm được điều đó thì chúng ta cần phải cấu hình lại file topology sao cho có thêm một máy dành cho attacker.
- Cụ thể, giả sử xét trong một cuộc chơi là Attack & Defend, khi đó người truy cập vào sandbox một cách thông thường là Defender. Ngược lại, người thứ 2 sẽ là Attacker.