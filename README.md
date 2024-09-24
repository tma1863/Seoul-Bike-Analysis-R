# Seoul-Bike-Analysis
![](https://www.korea.net/upload/content/editImage/20180404_bike_article_01.jpg)

[Nguồn ảnh: korea.net](https://www.korea.net/NewsFocus/Society/view?articleId=156692)

Hiện nay, dịch vụ cho thuê xe đạp được giới thiệu ở nhiều thành phố đô thị lớn nhằm nâng cao sự thoải mái
khi di chuyển. Điều quan trọng là phải cung cấp xe đạp cho thuê và công chúng có thể tiếp cận vào đúng
thời điểm vì nó giúp giảm thời gian chờ đợi. Cuối cùng, việc cung cấp cho thành phố nguồn cung cấp xe đạp
cho thuê ổn định trở thành mối quan tâm lớn. Phần quan trọng là dự đoán số lượng xe đạp cần thiết mỗi giờ
để cung cấp xe đạp cho thuê ổn định.

## ABOUT DATASET
Dữ liệu SeoulBikeData.csv chứa thông tin về số lượng xe đạp được thuê mỗi giờ trong ngày tại thành phố Seoul trong giai đoạn 01/12/2017 tới 30/11/2018 với các biến được quan sát:

* Date : year-month-day
* Rented Bike count - Count of bikes rented at each hour
* Hour - Hour of the day
* Temperature-Temperature in Celsius
* Humidity - %
* Windspeed - m/s
* Visibility - 10m
* Dew point temperature - Celsius
* Solar radiation - MJ/m2
* Rainfall - mm
* Snowfall - cm
* Seasons - Winter, Spring, Summer, Autumn
* Holiday - Holiday/No holiday
* Functional Day - NoFunc(Non Functional Hours), Fun(Functional hours)

## Các phương pháp xử lý dữ liệu được sử dụng:
* Tiền xử lý và khai phá dữ liệu
* Kiểm định giả thuyết thống kê
* Xây dựng mô hình hồi quy
