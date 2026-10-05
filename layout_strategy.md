# Strategy Report: CSS Grid vs Flexbox

CSS Grid được thiết kế cho **bố cục 2 chiều (2D)** - quản lý cả hàng và cột đồng thời. Do đó, Grid phù hợp làm khung xương tổng thể (Dashboard, Bento Box, Layout trang), nơi các phần tử cần vị trí chính xác và khả năng chiếm nhiều hàng/cột (`span`).

Ngược lại, Flexbox tối ưu cho **bố cục 1 chiều (1D)** (theo hàng hoặc cột riêng lẻ). Flexbox dựa trên dung lượng nội dung (Content-driven), tự động co giãn và căn chỉnh linh hoạt. Vì vậy, Flexbox lý tưởng cho các thành phần chi tiết (Component) như Navbar, Toolbar, hoặc căn chỉnh phần tử bên trong một Widget/Card.
