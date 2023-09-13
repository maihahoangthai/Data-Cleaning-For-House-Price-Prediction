# Data Cleaning For House Price Prediction
## Giới thiệu về Dataset
dataset.csv: gồm 20.499 mẫu dữ liệu, với 23 trường thông tin được thu thập trong khoảng từ ngày 12 tháng 6 đến ngày 2 tháng 7 năm 2023 về các nhà bán ở tại TP.HCM trên website Batdongsan.com.vn như nhà riêng, nhà biệt thự, nhà mặt phố, shophouse, nhà phố thương mại.
## Giới thiệu về chương trình
Ví dụ về những công đoạn, công việc tối thiểu cần làm nhằm chuyển đổi Dataset thô sơ mới crawl về trở thành một Dataset gọn gàng, dễ làm việc và tính toán cho bài toán dự đoán giá nhà.


Lưu ý, chương trình vẫn còn nhiều hạn chế. Chẳng hạn như ở phần thêm cột "dự án/số hẻm đường", có thể loại bỏ hết các thông tin không cần thiết như số nhà, tên hẻm, tên dự án để chỉ giữ lại tên đường. Nghiên cứu sử dụng chiến thuật filling missing data khác cho 3 cột: Số tầng, Số phòng ngủ, Số toilet. Không có xử lý outlier nên nếu vẽ Heatmap sẽ thấy rất nhiều vấn đề: Diện tích có độ tương quan thấp với Mức giá, phân bố dữ liệu mang nhiều outlier, ... Có thể cân nhắc loại trừ outlier theo sự gom nhóm về "dự án/số hẻm đường".
