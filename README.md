I. Tổng Quan Dự Án
RAM SPECIALIST là một website chuyên biệt cung cấp các giải pháp bộ nhớ trong (RAM) cho máy tính. Dự án tập trung vào trải nghiệm mua sắm tối giản, hiệu quả và tối ưu hóa quy trình tra cứu thông số kỹ thuật cho người dùng.

Công cụ thực hiện: Visual Studio Code (VS Code).

Ngôn ngữ sử dụng: HTML5, CSS3.

II. Mô Tả Chi Tiết Các Trang Chức Năng
1. Trang Chủ (trangchu.html)
Chức năng: Điểm chạm đầu tiên, giới thiệu thương hiệu và các sản phẩm nổi bật, dòng RAM mới nhất (DDR5).

Nhiệm vụ: Điều hướng người dùng đến các danh mục sản phẩm và cung cấp cái nhìn tổng quan về chương trình khuyến mãi.

Thiết kế: 

<img width="558" height="1024" alt="image" src="https://github.com/user-attachments/assets/672e1fdd-a56f-4b7c-9461-302c1c50003e" />


Công cụ thiết kế: Figma/Mockup tools.

2. Trang Danh Mục (danhmuc.html)
Chức năng: Hiển thị danh sách sản phẩm dưới dạng lưới (Grid).

Nhiệm vụ: Tích hợp bộ lọc (Sidebar) giúp khách hàng phân loại nhanh theo thế hệ RAM (DDR4, DDR5) và thương hiệu.

Thiết kế: 

<img width="565" height="1024" alt="image" src="https://github.com/user-attachments/assets/02ca48ae-4c6a-467e-aa8a-b79968061788" />


Công cụ thiết kế: Figma/Mockup tools.

3. Trang Chi Tiết Sản Phẩm (sanpham.html)
Chức năng: Cung cấp thông tin chuyên sâu.

Nhiệm vụ: Hiển thị bảng thông số kỹ thuật (Bus, Timing, Voltage), hình ảnh chi tiết và mô tả sản phẩm để hỗ trợ quyết định mua hàng.

Thiết kế: 

<img width="404" height="1024" alt="image" src="https://github.com/user-attachments/assets/748ada1e-0f90-47e3-a0e2-dfef27c65038" />


Công cụ thiết kế: Figma/Mockup tools.

4. Trang Giỏ Hàng (giohang.html)
Chức năng: Quản lý lựa chọn mua sắm.

Nhiệm vụ: Hiển thị danh sách sản phẩm đã chọn, tính toán tổng tiền, áp dụng mã giảm giá và dẫn dắt người dùng đến bước thanh toán.

Thiết kế: 

<img width="1004" height="1024" alt="image" src="https://github.com/user-attachments/assets/0d90ec2e-10d0-48f3-a470-8dd7975b9eb9" />


Công cụ thiết kế: Figma/Mockup tools.

III. Ứng Dụng Trí Tuệ Nhân Tạo (AI)

Công cụ AI sử dụng: Gemini (Google).

Dòng lệnh (Prompt) sử dụng để sinh giao diện:

"Hãy tạo giúp tôi một trang web bán linh kiện máy tính tên là 'RAM SPECIALIST'. Yêu cầu: Sử dụng HTML5 và CSS3 hiện đại. Giao diện có Header màu xanh đen, có Sidebar bên trái để lọc sản phẩm theo loại RAM (DDR4, DDR5), phần nội dung chính hiển thị các thẻ sản phẩm (Product Cards) dưới dạng lưới (Grid). Các thẻ sản phẩm phải có hiệu ứng hover nổi lên, hiển thị hình ảnh, tên RAM, giá tiền và có 2 nút: Mua ngay và Chi tiết. Hãy đảm bảo giao diện hiển thị tốt trên cả máy tính và điện thoại (Responsive)."

IV. Liên Kết Trực Tuyến (GitHub Pages)

https://nguyenhoa2601.github.io/MyWeb/myweb/trangchu.html

V. Cấu Trúc Thư Mục Dự Án

MyWeb/myweb
     
      ├── HTML/
      │   ├── trangchu.html
      │   ├── danhmuc.html
      │   ├── sanpham.html
      │   └── giohang.html
      ├── CSS/
      │   └── style.css
      └── README.md

