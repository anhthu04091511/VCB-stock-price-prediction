# VCB-stock-price-prediction
Sử dụng các mô hình học máy và học sâu cho Dự đoán giá chứng khoán của ngân hàng VCB (Ngân hàng Thương mại Cổ phần ngoại thương Việt Nam - Vietcombank)
## 1. Thu thập dữ liệu
Lấy dữ liệu giá chứng khoán của Ngân hàng VCB từ 1/1/2015 - 24/3/2023 bằng thư viện selenium và BeautifulSoup.  
Dữ liệu được lấy từ trang web https://s.cafef.vn/Lich-su-giao-dich-NVL-1.chn  
## 2. Dự đoán giá chứng khoán
Trong phần này mình sử dụng giá chứng khoán của 14 ngày trước đó để dự đoán cho ngày tiếp theo (n_input = 14)  
Ở phần này mình sử dụng 2 tập đặc trưng khác nhau:  
- Tập đặc trưng ban đầu
- Sử dụng correlation để tìm ra tập đặc trưng tốt nhất cho bộ dữ liệu 
Trong phần dự đoán mình sử dụng các mô hình học máy và học sâu khác nhau:
- KNN
- DecisionTree
- LinearRegression
- RandomForest
- RNN
- LSTM
- BiLSTM
- RNN + CNN
- LSTM + CNN
- BiLSTM + CNN
## 3. Kết quả
### 3.1 Đối với tập đặc trưng ban đầu
- Biểu đồ thể hiện loss và mse  <image src='img/loss, mse.png'>
- Biểu đồ thể hiện giá trị thực và dự đoán  <image src='img/y_true, y_pred.png'>
- Biểu đồ thể hiện dự đoán giá cổ phiếu 14 ngày tiếp theo  <image src='img/predict_future.png'>  
- Bảng so sánh các model  <image src='img/compare.PNG'>  
### 3.2 Đối với tập đặc trưng sử dụng correlation  
- Biểu đồ thể hiện loss và mse  
<image src='img/loss, mse 2.png'>  
- Biểu đồ thể hiện giá trị thực và dự đoán  
<image src='img/y_true, y_pred 2.png'>  
- Biểu đồ thể hiện dự đoán giá cổ phiếu 14 ngày tiếp theo  
<image src='img/predict_future 2.png'>  
- Bảng so sánh các model  
<image src='img/compare 2.PNG'>  
