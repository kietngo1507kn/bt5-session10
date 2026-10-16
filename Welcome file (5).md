**Phần 1. Phân tích:** Xác định Input/Output và sơ đồ phối hợp phần cứng của hệ thống trang trại.
-   **Input (Đầu vào):**
    
    -   Dữ liệu từ các cảm biến IoT thực tế tại vườn lan: Cảm biến độ ẩm đất, cảm biến nhiệt độ và độ ẩm không khí , cảm biến cường độ ánh sáng.
        
    -   Lệnh thủ công hoặc cấu hình ngưỡng tự động từ người nông dân thông qua giao diện ứng dụng di động/web.
        
-   **Output (Đầu ra):**
    
    -   Tín hiệu điện điều khiển hệ thống rơ-le bật/tắt máy bơm nước, quạt thông gió hoặc lưới che nắng.
        
    -   Thông báo cảnh báo trạng thái gửi về điện thoại của chủ trang trại.
    **Phần 2. Triển khai:**
     File [README.md](http://README.md) hoàn chỉnh theo chuẩn kỹ sư phần mềm chuyên nghiệp
 
    # 🚀 Smart-Farm: Hệ Thống Tự Động Hóa Vườn Lan Thông Minh > *Giải pháp công nghệ IoT toàn diện giúp tối ưu hóa độ ẩm, nhiệt độ và quy trình chăm sóc hoa lan tự động hóa 24/7.* ---
    ## 1. Mô tả hệ thống Hệ thống **Smart-Farm** ứng dụng công nghệ vi điều khiển và cảm biến IoT nhằm giám sát liên tục các thông số môi trường vi khí hậu trong vườn lan. Hệ thống tự động phân tích dữ liệu đầu vào và kích hoạt thiết bị phần cứng (máy bơm, van điện từ) kịp thời, giúp cây lan phát triển trong điều kiện tối ưu nhất mà không cần tốn nhiều công sức giám sát thủ công. ---
     ## 2. Hướng dẫn cài đặt nhanh Thực hiện các lệnh sau trên terminal để cấu hình và khởi chạy môi trường hệ thống trên vi điều khiển:
      ```bash # Cập nhật danh sách gói hệ thống và cài đặt thư viện phụ thuộc IoT sudo apt-get update && sudo apt-get install -y python3-pip git git clone [https://github.com/ptit-tech/smart-farm-lan.git](https://github.com/ptit-tech/smart-farm-lan.git) cd smart-farm-lan 
      # Cài đặt các gói thư viện điều khiển phần cứng cần thiết pip install -r requirements.txt 
      # Khởi chạy dịch vụ giám sát cảm biến nền python3 main.py --mode=production
      **Phần 3. Kiểm thử:** Giả định RAM bị đầy dữ liệu nhật ký, hãy cập nhật mục "Lưu ý" trong README cách xử lý an toàn.
   -   [x] **Giám sát thời gian thực:** Theo dõi sát sao nhiệt độ, độ ẩm không khí và độ ẩm đất mọi lúc mọi nơi.
    
-   [x] **Tưới nước thông minh tự động:** Kích hoạt hệ thống phun sương/tưới gốc dựa trên ngưỡng cấu hình sẵn.
    
-   [ ] **Điều khiển từ xa qua cloud:** Bật/tắt thủ công thiết bị qua ứng dụng di động (Đang phát triển phiên bản V2).
    
-   [x] **Nhật ký dữ liệu an toàn:** Lưu trữ lịch sử hoạt động vào bộ nhớ đệm cục bộ để phục vụ phân tích.   
