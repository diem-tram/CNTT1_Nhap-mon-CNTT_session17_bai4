# CNTT1_nhapmonCNTT_session17_bai4
Bài 4 : Quản lý Môi trường Trình duyệt cho Lập trình viên
Bảng so sánh đánh giá 
Tiêu chí 	Chế độ ẩn danh 	Hồ sơ riêng biệt
Hồ sơ cách ly 	Tạm thời: sẽ bị xóa ngay khi đóng toàn bộ cửa sổ ẩn danh	Tuyệt đối: hoàn toàn độc lập
Lưu giữ trạng thái	Không lưu giữ: lịch sử duyệt web	Lưu giữ lâu dài và đồng bộ 
Hiệu suất	Kém	Cao
Ưu điểm 	Nhanh chóng: không cần thiết lập ban đầu. phù hợp để test nhanh giao diện	Duy trì môi trường làm việc lâu dài. Cách ly hoàn toàn môi trường cá  nhân- công việc- test
Nhược điểm	Mất hết dữ liệu, phải lặp lại thao tác mỗi ngày	Tốn mộ ít dụng lượng ổ cứng ban đầu để lâu cấu hình riêng cho từng profile
Mô hình 3 profile chuẩn Dev
1 Profile : giải trí tin tức, tài khoản xã hội, banking cá nhân 
2 Work : làm việc hằng ngày, trao đổi công việc, đọc tài liệu kỹ thuật, quản lý task 
3 Sandbox : dùng chuyên biệt để test các role khác nhau trên hệ thống LMS 
Giải pháp tối ưu hơn ẩn danh 
-	Không mất bookmark: lưu cố định tài liệu kỹ thuật, API, jira ticket; tắt máy khởi động lại vẫn giữ nguyên 
-	Tiết kiệm thời gian: không cần nhập lại password, xác nhận mỗi ngày 
-	Hỗ trợ devtools tối đa: cài sẵn mỗi trường extension debug cho từng môi trường mà không bị ngắt kết nối 
-	Trách nhầm lẫn dữ liệu: cách ly hoàn toàn tài khoản Dev thật và tài khoản Test, không lo lỡ tay thao tác sai data trên môi trường chạy thật
