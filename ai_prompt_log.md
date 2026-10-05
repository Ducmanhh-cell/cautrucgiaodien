# AI Prompt Log - MetricsHub UI Refactoring

### Prompt 1: Phân tích nguyên nhân lỗi (Step 1)
- **Prompt:** "Khi tôi cần một bố cục mà một phần tử con (Child) phải chiếm chính xác 2 hàng và 2 cột (span 2 rows, 2 columns) đan xen với các phần tử nhỏ khác, tôi nên chọn CSS Grid hay Flexbox? Tại sao Flexbox lại chật vật với yêu cầu này?"
- **Mục đích:** Hiểu rõ giới hạn 1D của Flexbox và sức mạnh 2D của CSS Grid để giải quyết "Div Soup" ở Bento Dashboard.

### Prompt 2: Tìm giải pháp Bootstrap vs CSS thuần (Step 2)
- **Prompt:** "Trong Bootstrap 5, sự khác biệt giữa lớp col-sm-4 và col-md-4 là gì? Tại sao tôi nên dùng Bootstrap thay vì tự viết CSS Grid cho một phần tử đơn giản như 3 cột Bảng giá?"
- **Mục đích:** Hiểu cách hoạt động của điểm ngắt (breakpoint) và lợi ích tốc độ triển khai (Rapid Prototyping) của Bootstrap Grid 12 cột.

### Prompt 3: Cú pháp Bento Box (Step 3)
- **Prompt:** "Hãy cho tôi xem một cú pháp CSS Grid đơn giản (sử dụng grid-template-columns và span) để tạo một layout dạng Bento Box: có 1 hình vuông lớn bên trái chiếm 2x2, và các hình vuông nhỏ khác bên phải."
- **Mục đích:** Lấy ví dụ cú pháp `grid-column: span 2` và `grid-row: span 2` tối ưu hóa DOM.

### Prompt 4: Responsive Navbar (Step 4)
- **Prompt:** "Làm thế nào để sử dụng thuộc tính flex-wrap: wrap trong Flexbox kết hợp với gap để Navbar tự động co giãn linh hoạt khi đổi ngôn ngữ tiếng Đức mà không vỡ giao diện?"
- **Mục đích:** Hoàn thiện responsive và khoảng cách động cho Navbar.
