# Sales_Analysis

Tập dữ liệu được lấy từ kaggle: https://www.kaggle.com/datasets/vivek468/superstore-dataset-final.
Dưới đây là mô tả ngắn gọn về các cột trong dữ liệu:  
Row ID: Một số duy nhất đại diện cho từng dòng trong tập dữ liệu.  
Order ID: Mã đặt hàng duy nhất cho mỗi đơn hàng của khách hàng.  
Order Date: Ngày đặt hàng của sản phẩm.  
Ship Date: Ngày giao hàng của sản phẩm.  
Ship Mode: Phương thức giao hàng được xác định bởi khách hàng.  
Customer ID: Mã khách hàng duy nhất để xác định từng khách hàng.  
Customer Name: Tên của khách hàng.  
Segment: Phân khúc mà khách hàng thuộc về.  
Country: Quốc gia cư trú của khách hàng.  
City: Thành phố cư trú của khách hàng.  
State: Tiểu bang của khách hàng.  
Postal Code: Mã bưu chính của khách hàng.  
Region: Khu vực mà khách hàng thuộc về.  
Product ID: Mã duy nhất của sản phẩm.  
Category: Danh mục của sản phẩm được đặt hàng.  
Sub-Category: Danh mục con của sản phẩm được đặt hàng.  
Product Name: Tên của sản phẩm.  
Sales: Doanh số bán hàng của sản phẩm.  
Quantity: Số lượng của sản phẩm.  
Discount: Giảm giá được cung cấp.  
Profit: Lợi nhuận/Thua lỗ gánh chịu.  

### Data preprocessing:
Sau khi đã có dữ liệu ta sẽ tiến hành kiểm tra và làm sạch dữ liệu để đưa vào phân tích. Việc kiểm tra và làm sạch dữ liệu được thực hiện trong file ...

### Questions:
1. Danh mục sản phẩm nào có doanh số bán hàng cao nhất?
2. Có xu hướng thời gian nào liên quan đến doanh số của các doanh mục sản phẩm?
3. Có sự khác biệt về hiệu suất giữa các danh mục con trong từng danh mục sản phẩm không?
4. Có mối liên hệ nào giữa danh mục sản phẩm và phân khúc khách hàng?

### Data analysis
1. Danh mục sản phẩm nào có doanh số bán hàng cao nhất?

![image](https://github.com/Pien18801/Sales_Analysis/assets/92161666/3f9c32dd-5e51-4694-ab6e-4d7cd4185107)

Từ biểu đồ trên ta có thể thấy danh mục "technology" có doanh số cao nhất (36.4%). Điều này cho thấy rằng các sản phẩm công nghệ có ảnh hưởng lớn đến doanh số bán hàng. Cửa hàng nên tiếp tục tập trung vào việc phát triển, tiếp thị và cung cấp các sản phẩm công nghệ để duy trì và tăng cường doanh số bán hàng.
Tỷ lệ doanh số giữa danh mục "furniture" và "office supplies" khá gần nhau, lần lượt là 32.3% và 31.3%. Điều này cho thấy rằng mua sắm đối với nội thất và văn phòng là hai yếu tố có sự quan trọng tương đương đối với khách hàng. Cửa hàng có thể đề xuất các chiến lược kinh doanh tương ứng để cải thiện hiệu suất và tối ưu hóa lợi nhuận từ cả hai danh mục này.




