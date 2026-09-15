### **Bài 2: Hệ thống y tế của bạn xảy ra các tình huống sau. Hãy xác định mã lỗi HTTP nào là phù hợp nhất:**
    TH1: Người dùng gửi yêu cầu đặt lịch khám nhưng bỏ trống tên bệnh nhân.
        HTTP Status: 400 Bad Request
    TH2: Tìm kiếm hồ sơ bệnh án với ID là 999 nhưng trong Database không tồn tại.
        HTTP Status: 404 Not Found
    TH3: Hệ thống đang chạy thì Database MySQL bị sập, không thể truy vấn dữ liệu.
        HTTP Status: 500 Internal Sever Error
    TH4: Người dùng nhập tuổi bệnh nhân là -5 (Dữ liệu không hợp lệ về mặt logic).
        HTTP Status: 400 Bad Request