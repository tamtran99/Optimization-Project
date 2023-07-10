# Eton Optimization Project

## 1. Features

- Tìm đường đi tối ưu từ ***một kho*** đến các điểm cần giao cho một lần giao hàng.
- Data input:

    - Dữ liệu xe của các nhà vận tải ([Xem mô tả dữ liệu nhà vận tải](truck_description.md)).
    - Dữ liệu input danh sách SO cần vận chuyển ([Xem mô tả dữ liệu SO](SO_Data_Description.md)).

- Output:

    - Excel file ([Xem mô tả](output_description.md)).
    - HTML trực quan hóa đường đi.

## 2. Hướng dẫn sử dụng

- Yêu cầu ```python3.8```.

- Cài các gói thư viện trong file ```requirements.txt``` bằng câu lệnh:

<center> 

> ```pip install -r requirements.txt``` 

</center>

:warning: Khuyến khích quản lý qua môi trường ảo python (python virtual environment).

:warning: Nếu trên máy sử dụng cả python2 và python3 vui lòng sử dụng ```pip3``` thay cho ```pip```.

- Thực hiện tìm giải pháp cho một file csv SO:

<center> 

> ```python3 main.py --df_so_path duong_dan_file.csv``` 

</center>

Ví dụ:

<center> 

> ```python3 main.py --df_so_path input/sample.csv``` 

</center>

Sau khi chạy xong sẽ được kết quả trong mục ```output``` tương ứng với tên thực mục chứa kết quả của file là tên file csv không bao gồm ```".csv"```. Ví dụ: ```output/sample/``` là output tương ứng của file ```input/sample.csv```.
# Optimization-Project
