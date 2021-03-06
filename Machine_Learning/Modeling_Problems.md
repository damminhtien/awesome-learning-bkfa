# Modeling Problems
Theo cuốn AI for Humans vol 1, tác giả Jeff Heaton phân loại các vấn đề ra thành bốn nhóm chính, ở mức độ cao nhất:
* Phân loại dữ liệu (Data classification)
* Phân tích hồi quy (Regression analysis)
* Phân cụm (Clustering)
* Chuỗi thời gian (Time Series)

Đôi khi trong một vài trường hợp bạn có thể gặp một vấn đề là tổng hợp của một vài vấn đề trên, nhưng bốn loại trên là cốt lõi.

## Phân loại dữ liệu - Data Classification
* Classification thường là bài toán học máy có giám sát (Supervised learning)
* Phân loại dữ liệu (Classification) đúng như cái tên của nó đó là phân loại dữ liệu đầu vào thành các lớp tương ứng có trong bộ nhãn có sẵn, hay nói cách khác, chúng ta đi gắn nhãn cho dữ liệu mới dựa trên những dữ liệu cũ đã được gán nhãn
* Mục đích của bài toán classification là tối ưu xác suất để dữ liệu A có thuộc phân lớp B hay không

## Phân tích hồi quy (Regression Analysis)
* Dữ liệu gán nhãn không phải là các nhóm mà là một giá trị cụ thể
* Thường là đi tìm một hàm số f fit với dữ liệu đầu vào, khi ta có một dữ liệu mới thay vào f sẽ cho kết quả cần tìm

## Phân cụm (Clustering)
* Bài toán phân nhóm toàn bộ dữ liệu X thành các nhóm nhỏ dựa trên sự liên quan giữa các dữ liệu trong mỗi nhóm. Ví dụ: phân nhóm khách hàng dựa trên hành vi mua hàng, phân nhóm vùng ảnh có độ tương quan
* Bài toán phân cụm khá giống so với bài toán classification  chỉ khác không có nhãn cụ thể cho các nhóm dữ liệu
* Đối với bài toán phân loại thì người lập trình thường tự định nghĩa số cụm

## Chuỗi thời gian (Time Series)
