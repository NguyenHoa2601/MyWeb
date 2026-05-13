1. Mô tả chức năng và nhiệm vụ các trang

Hệ thống website được thiết kế với 04 trang cốt lõi, đảm bảo quy trình mua sắm khép kín:

Trang Chủ (trangchu.html): 

 Chức năng: Giới thiệu thương hiệu, hiển thị các banner khuyến mãi và các dòng sản phẩm RAM mới nhất (DDR5).

Nhiệm vụ: Thu hút người dùng và điều hướng nhanh đến các danh mục sản phẩm nổi bật.

Trang Danh Mục (danhmuc.html):

Chức năng: Hiển thị toàn bộ danh sách sản phẩm theo dạng lưới (Grid layout).

Nhiệm vụ: Cung cấp bộ lọc thông minh (Sidebar) để người dùng phân loại RAM theo thế hệ (DDR4, DDR5) hoặc thương hiệu.

Trang Chi Tiết Sản Phẩm (sanpham.html):

Chức năng: Hiển thị thông tin kỹ thuật chi tiết của một sản phẩm cụ thể.

Nhiệm vụ: Giúp người dùng kiểm tra các thông số như Bus, Latency, Voltage và hình ảnh thực tế trước khi quyết định mua.

Trang Giỏ Hàng (giohang.html):

Chức năng: Tổng hợp các sản phẩm người dùng đã chọn.

Nhiệm vụ: Cho phép chỉnh sửa số lượng, áp dụng mã giảm giá và tính toán tổng chi phí đơn hàng.

2. Bản vẽ thiết kế và Công cụ thực hiện
Hệ thống giao diện được phác thảo dựa trên phong cách Minimalist (Tối giản), tập trung vào tính chuyên nghiệp cho một cửa hàng linh kiện máy tính.

Bản vẽ thiết kế:


<img width="558" height="1024" alt="image" src="https://github.com/user-attachments/assets/672e1fdd-a56f-4b7c-9461-302c1c50003e" />


<img width="565" height="1024" alt="image" src="https://github.com/user-attachments/assets/02ca48ae-4c6a-467e-aa8a-b79968061788" />


<img width="404" height="1024" alt="image" src="https://github.com/user-attachments/assets/748ada1e-0f90-47e3-a0e2-dfef27c65038" />


<img width="1004" height="1024" alt="image" src="https://github.com/user-attachments/assets/0d90ec2e-10d0-48f3-a470-8dd7975b9eb9" />


Công cụ thiết kế: Figma và Mockup Editor.

Công cụ lập trình: Visual Studio Code (VS Code).

3. Dòng lệnh sử dụng AI sinh giao diện

Để tối ưu hóa cấu trúc mã nguồn và giao diện Responsive, dự án có sử dụng hỗ trợ từ trí tuệ nhân tạo.

Công cụ AI: Gemini (Google).

Dòng lệnh (Prompt):

"Hãy tạo giúp tôi một trang web bán linh kiện máy tính tên là 'RAM SPECIALIST'. Yêu cầu: Sử dụng HTML5 và CSS3 hiện đại. Giao diện có Header màu xanh đen, có Sidebar bên trái để lọc sản phẩm theo loại RAM (DDR4, DDR5), phần nội dung chính hiển thị các thẻ sản phẩm (Product Cards) dưới dạng lưới (Grid). Các thẻ sản phẩm phải có hiệu ứng hover nổi lên, hiển thị hình ảnh, tên RAM, giá tiền và có 2 nút: Mua ngay và Chi tiết. Hãy đảm bảo giao diện hiển thị tốt trên cả máy tính và điện thoại (Responsive)."

4. Liên kết GitHub Page

Người dùng có thể truy cập và trải nghiệm giao diện trực tiếp tại:

Link dự án: https://nguyenhoa2601.github.io/MyWeb/myweb/trangchu.html

5. Tổ chức tập tin trong Repository

MyWeb/myweb
     
     ├── HTML/
     │   ├── trangchu.html
     │   ├── danhmuc.html
     │   ├── sanpham.html
     │   └── giohang.html
     ├── CSS/
     │   └── style.css
     └── README.md
