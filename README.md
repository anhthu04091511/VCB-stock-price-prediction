# VCB-stock-price-prediction
Sử dụng các mô hình học máy và học sâu cho Dự đoán giá chứng khoán của ngân hàng VCB (Ngân hàng Thương mại Cổ phần ngoại thương Việt Nam - Vietcombank)
## Thu thập dữ liệu
Lấy dữ liệu giá chứng khoán của Ngân hàng VCB từ 1/1/2015 - 24/3/2023 bằng thư viện selenium và BeautifulSoup.  
Dữ liệu được lấy từ trang web https://s.cafef.vn/Lich-su-giao-dich-NVL-1.chn  
## Dự đoán giá chứng khoán
Trong phần này mình sử dụng giá chứng khoán của 14 ngày trước đó để dự đoán cho ngày tiếp theo (n_input = 14)  
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
