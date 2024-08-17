# Maven-Pizza-Challenge

![images (7)](https://user-images.githubusercontent.com/108612390/193467417-26c85e60-7998-4b89-8015-120f30f6f86e.png)

## Giới thiệu
Dữ liệu từ Maven Plato Pizza bao gồm 4 tệp CSV đại diện cho một năm doanh thu từ một quán pizza giả tưởng, bao gồm ngày và giờ của mỗi đơn hàng cùng các loại pizza được phục vụ, với các chi tiết bổ sung về loại, kích cỡ, số lượng, giá cả và nguyên liệu.

## Phân tích được đề xuất
- Những ngày và giờ nào chúng tôi thường bận rộn nhất?
- Chúng tôi làm bao nhiêu chiếc pizza trong các khoảng thời gian cao điểm?
- Những loại pizza nào bán chạy nhất và tệ nhất?
- Giá trị đơn hàng trung bình của chúng tôi là bao nhiêu?

## Công cụ được sử dụng cho phân tích
- Microsoft Excel: Tôi đã sử dụng Ms Excel để xem các tập dữ liệu và hiểu rõ hơn về các tham số của dữ liệu. Tôi cũng đã thực hiện một số công việc làm sạch để làm cho tập dữ liệu dễ dàng làm việc và phân tích hơn.
- PostgreSQL: Đây là một công cụ tuyệt vời để truy xuất dữ liệu mà tôi đã sử dụng để thực hiện phân tích chi tiết với sự hỗ trợ của các toán tử và cú pháp SQL tổng quát để truy xuất dữ liệu cần thiết.
- Power BI: Công cụ trí tuệ doanh nghiệp của Microsoft rất hữu ích trong quá trình tạo hình ảnh hóa của tôi. Tôi đã nhập các tập dữ liệu vào Power BI và tạo một bảng điều khiển duy nhất rõ ràng và hấp dẫn về mặt thị giác.

## Dashboard trong Power BI
### Cover
![image](https://github.com/user-attachments/assets/9dbfbb69-39c5-4267-98df-cf6caa491baa)
### Order&Revenue
![image](https://github.com/user-attachments/assets/0afb4e5f-500c-43ca-b241-7ae223e70913)
### Weekday-Hour
![image](https://github.com/user-attachments/assets/78f83d25-c2d6-4dee-9ce0-2291a2623030)
### Name-Cate-Size
![image](https://github.com/user-attachments/assets/06a60402-3a00-4c3a-ac36-5bd4db0f5871)
### Ingredients
![image](https://github.com/user-attachments/assets/24f4df2e-1cfd-43ae-91ae-bc2d75e51937)
### Pizza Size
![image](https://github.com/user-attachments/assets/77855bc9-75ea-4c63-a893-ad796475864d)
### Pizza Size-Price
![image](https://github.com/user-attachments/assets/e5620291-478d-4204-be00-fe4ced88a9a4)
### Category
![image](https://github.com/user-attachments/assets/be79fe58-c4dc-4d97-8c88-4b97d7b369b7)

## Phân tích
![Screenshot (60)](https://user-images.githubusercontent.com/108612390/194349332-97fe168d-d622-4bba-a79b-f7d2af9541fe.png)
- Giờ bận rộn nhất dường như là từ 12 giờ trưa đến 2 giờ chiều.

![Screenshot (61)](https://user-images.githubusercontent.com/108612390/194350181-4701afb0-3551-4df5-bf21-f823b7e05dc8.png)
- Loại pizza bán chạy nhất là Thai Chicken Pizza, trong khi pizza bán ít nhất là Brie Carre Pizza.

![Screenshot (62)](https://user-images.githubusercontent.com/108612390/194350891-d8cc65a7-f30c-47d5-87a9-de4511b044e3.png)
- Plato Pizza ghi nhận số lượng đơn hàng và doanh thu nhiều nhất vào các ngày Chủ Nhật, tiếp theo là Thứ Hai, và số lượng đơn hàng ít nhất là vào các ngày Thứ Năm.

![Screenshot (63)](https://user-images.githubusercontent.com/108612390/194351514-c24aa062-0a4f-4b44-b62d-0974787e026a.png)
- Khách hàng ưa chuộng và mua nhiều pizza cỡ lớn hơn so với các kích cỡ khác. Trong khi đó, kích cỡ XXL (cực lớn) lại là kích cỡ ít được mua nhất.

![Screenshot (64)](https://user-images.githubusercontent.com/108612390/194352347-affe1bc2-c09e-4b51-9527-c0d433239ba6.png)
- Tháng 7 ghi nhận số lượng đơn hàng và doanh thu nhiều nhất, trong khi tháng 10 lại có doanh thu ít nhất. Plato Pizza chắc chắn cần cải thiện doanh thu trong mùa thu.

![Screenshot (65)](https://user-images.githubusercontent.com/108612390/194353332-d60c0ae1-dbe9-4f06-a061-f57764b1e954.png)
- Biểu đồ trên cho thấy cường độ bán hàng theo kích cỡ và loại pizza. Rõ ràng có bốn loại pizza tại Plato's Place và kích cỡ lớn trong loại Veggie dường như được khách hàng yêu thích nhất, trong khi kích cỡ XXL trong loại Classic là ít được khách hàng ưa chuộng nhất.

## Thông tin chi tiết
- Giá trung bình của một chiếc pizza là $16,4.
- Thai Chicken Pizza tạo ra doanh thu nhiều nhất với tổng số $43,434, trong khi Brie Carre Pizza tạo ra doanh thu ít nhất với $11,588.
- Kích cỡ L (lớn) có số lượng đơn hàng nhiều nhất với 18,956, trong khi kích cỡ XXL (cực lớn) có số lượng ít nhất với 28 đơn hàng.
- Tháng 7 ghi nhận số lượng bán hàng nhiều nhất với $72,557, tiếp theo là tháng 5, tháng 3, tháng 11... Trong tương lai, Plato Pizza sẽ cần nhiều nhân viên hơn để xử lý các đơn hàng giữa năm.
- Plato Pizza có doanh thu nhiều nhất vào các ngày Chủ Nhật, điều này là hợp lý vì gia đình và bạn bè thường tụ tập vào cuối tuần và các món ăn như pizza sẽ là không thể thiếu.
- Thời gian cao điểm tạo ra doanh thu nhiều nhất dường như là giữa trưa từ 12 giờ trưa đến 2 giờ chiều.
- Trong các khoảng thời gian cao điểm, thường là các ngày Chủ Nhật, Plato Pizza nhận được hơn 8,000 đơn hàng.
