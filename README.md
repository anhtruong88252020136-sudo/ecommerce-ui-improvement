# E-commerce UI Improvement

## . Cấu trúc thư mục
```text
bach-hoa-xanh/
├── index.html
├── gio-hang.html
├── css/
│   ├── style.css
│   └── gio-hang.css
├── images/
│   └── product-demo.jpg
├── README.md
└── AI_USAGE.md
```
## 1. Giới thiệu dự án
Cải tiến giao diện thương mại điện tử siêu thị trực tuyến **Bách Hóa XANH** bằng HTML5 và CSS3, bài làm tập trung tối ưu trải nghiệm duyệt danh mục sản phẩm qua thanh điều hướng cố định (sticky tabs), khu vực gợi ý thực phẩm hằng ngày ("Hôm nay ăn gì?") và giao diện giỏ hàng thân thiện trên nhiều kích thước màn hình.


## 2. Website tham khảo
- **Tên website:** Bách Hóa XANH
- **URL:** https://www.bachhoaxanh.com/
- **Khu vực đã khảo sát:** Thanh điều hướng danh mục sản phẩm (Header & Sticky Tabs), khối gợi ý thực phẩm theo bữa ăn ("Hôm nay ăn gì?"), danh sách thẻ sản phẩm và giao diện giỏ hàng.

## 3. Chức năng
- Hiển thị danh sách sản phẩm phân chia trực quan theo từng nhóm ngành hàng.
- Hiển thị đầy đủ hình ảnh, tên sản phẩm, quy cách và giá bán.
- Thanh điều hướng danh mục cố định giúp chuyển đổi nhanh giữa các nhóm sản phẩm khi cuộn trang.
- Bố cục hỗ trợ nhiều kích thước màn hình (Responsive trên điện thoại, máy tính bảng và máy tính để bàn).

## 4. Công nghệ
- HTML5
- CSS3

## 5. Cách chạy
1. Tải hoặc clone repository về máy tính.
2. Mở file `index.html` trực tiếp bằng trình duyệt web (Chrome, Edge, Firefox) hoặc chạy qua tiện ích **Live Server** trong VS Code.
3. Có thể truy cập trực tiếp phiên bản triển khai trên **GitHub Pages**.

## 6. Cải tiến đã thực hiện
- **Vấn đề ban đầu:** Giao diện gốc có mật độ thông tin dày đặc, thanh danh mục dễ bị khuất khi cuộn trang trên màn hình nhỏ và thông tin điều kiện giao hàng trong giỏ hàng còn phân tán.
- **Thay đổi đã thực hiện:** Thiết kế lại bố cục theo hướng gọn gàng (Mobile-first), cố định thanh điều hướng danh mục (`sticky tabs`) để thao tác nhanh bằng một tay, làm nổi bật khu vực gợi ý *"Hôm nay ăn gì?"* và tổ chức lại trang giỏ hàng (`gio-hang.html`) giúp người dùng dễ theo dõi giá trị đơn hàng và khung giờ giao.

## 7. Hỗ trợ từ AI
- **Phần AI hỗ trợ:** Phân tích bố cục giao diện tham khảo, gợi ý cấu trúc HTML5 chuẩn ngữ nghĩa (Semantic HTML), đề xuất kỹ thuật dàn trang CSS Flexbox/Grid Responsive và hỗ trợ xử lý lỗi đường dẫn khi triển khai lên GitHub Pages.
- **Phần tôi đã kiểm tra, điều chỉnh hoặc bổ sung:** Trực tiếp kiểm thử giao diện trên nhiều độ phân giải màn hình bằng Chrome DevTools, tinh chỉnh màu sắc nhận diện, khoảng cách thẻ sản phẩm, chuẩn hóa cấu trúc thư mục viết thường (`css/`, `images/`) và kiểm tra hiển thị thực tế trên GitHub Pages.
