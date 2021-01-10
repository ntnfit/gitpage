EDA LÀ : Phân tích dữ liệu khám phá là một tiếp cận: tóm
tắt các đặc điểm chính của dữ liệu. Từ đó:
- Hiểu dữ liệu,
- Lấy ngữ cảnh liên quan đến dữ liệu
- Hiểu các biến và quan hệ giữa các biến
- Hình thành các giải thuyết có thể hữu ích cho việc xây dựng các mô hình dự
báo
Trong bài này học việc thực hiện EDA sử dụng trực quan dữ liệu, với thư viện
seaborn
- Phân tích trực quan các biến định lượng dùng histogram
- Phân tích trực quan các biến phân loại dùng count plot
- Phân tích trực quan sự tương quan giữa các biến định lượng dùng scatter plot,
joint plot, box plot và các complex conditional plot
Trực quan hiệu quả các biến và sự tương quan giữa chúng, các nhà khoa học dữ liệu
và phân tích dữ liệu nhanh chóng hiểu xu hướng, các ngoại lệ và mẫu (pattern) của dữ
liệu. Sự hiếu biết này được sử dụng để kể một câu chuyện, định hướng cho việc ra
quyết định hay tạo các mô hình dự báo
các bước để phân tích EDA:
+ chuẩn bị dữ liệu
+ xử lý dữ liệu: dữ liệu miss, dữ liệu trùng, dữ liệu bị sai.
+ import các thư viện của python: seaborn, numpy, panda, matplyplot...
+ trực quan dữ liệu thống quan các công cụ vẽ biểu đồ của python:
	- phân tích biến định lượng thường dùng histogram
	- phân tích biến phân loại: countplot, bar, column,..
	- Phân tích tương quan giữa các biến định lượng
	  *dùng Scatter plot thường được dùng để trực quan sự tương quan giữa 2 biến định
	lượng
	- Phân tích tương quan giữa biến định lượng và biến phân loại
	  *dùng box plot thường được dùng trong việc trực quan sự tương quan giữa biến định
		lượng và biến phân loại.
	-Complex conditional plots được dùng để trực quan sự tương quan có điều kiện
+ đọc biểu đồ và đưa ra nhận xét.
+ từ các dữ liệu xây dựng và định hướng ra các dự báo.
