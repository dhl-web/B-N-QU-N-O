# ⚡ PROSPORT - Website Bán Hàng Quần Áo & Phụ Kiện Thể Thao Đỉnh Cao

Chào mừng bạn đến với **PROSPORT** — Website thương mại điện tử chuyên nghiệp dành riêng cho trang phục, đồ tập và phụ kiện thể thao hiệu năng cao. Dự án được xây dựng với tiêu chuẩn hiện đại, giao diện trực quan, giàu tính tương tác và tương thích hoàn hảo trên mọi thiết bị (Mobile, Tablet, Desktop).

---

## 🌟 Tính Năng Nổi Bật

### 1. Trải Nghiệm Mua Sắm Thể Thao Chuyên Nghiệp
- **Danh mục thể thao đa dạng**: Bóng đá, Chạy bộ (Running), Gym & Thể hình, Tennis & Cầu lông, Bóng rổ, Yoga & Pilates, Phụ kiện thể thao.
- **Bộ lọc thông minh (Multi-filter)**:
  - Lọc theo môn thể thao
  - Lọc theo giới tính (Nam / Nữ / Unisex)
  - Lọc theo khoảng giá (< 300k, 300k-500k, > 500k)
  - Lọc nhanh theo kích cỡ (S, M, L, XL, XXL)
  - Tìm kiếm tức thì (Live Search) theo tên, công nghệ vải (Dri-FIT, Mesh, Compression...)
  - Sắp xếp: Phổ biến, Bán chạy nhất, Đánh giá cao, Giá tăng/giảm dần.

### 2. Chi Tiết Sản Phẩm & Xem Nhanh (Quick View Modal)
- Bộ sưu tập ảnh sản phẩm với thumbnail tương tác.
- Lựa chọn màu sắc, kích cỡ trực quan.
- Tăng/giảm số lượng sản phẩm linh hoạt.
- Thẻ công nghệ thể thao độc quyền (*Dri-FIT 4D, AirFlex, HydroShield, Silver-Ion...*).
- Nút **"Thêm vào giỏ"** và **"Mua ngay"** mượt mà.

### 3. Công Cụ Thông Minh & Tiện Ích
- **Công cụ tính Size chuẩn thể thao (AI Size Calculator)**: Nhập chiều cao (cm), cân nặng (kg) và form mặc (Standard / Muscle / Loose) để nhận ngay gợi ý kích thước tối ưu.
- **Bảng đo size chi tiết (Size Guide Popup)**: Tra cứu nhanh số đo chiều cao, cân nặng, vòng ngực, vòng eo theo tiêu chuẩn thể thao.
- **Đồng hồ đếm ngược Flash Sale**: Hiệu ứng đếm ngược trực tiếp thời gian thực tạo sự gấp rút và hấp dẫn.

### 4. Giỏ Hàng & Mã Giảm Giá (Cart Drawer)
- Ngăn kéo giỏ hàng (Slide-over drawer) không cần reload trang.
- **Thanh đo Miễn phí vận chuyển**: Tự động tính khoảng tiền còn thiếu để đạt mốc Freeship (499.000₫).
- **Hệ thống mã giảm giá (Promo Vouchers)**:
  - `SPORT2026`: Giảm 15% tổng hóa đơn.
  - `FREESHIP`: Miễn phí vận chuyển (tối đa 30.000₫).
  - `PRO50K`: Giảm 50.000₫ cho đơn từ 300.000₫.
  - `VIPMEMBER`: Giảm 20% cho thành viên VIP từ 500.000₫.
- Dữ liệu giỏ hàng và danh sách yêu thích được lưu trữ tự động trong `localStorage`.

### 5. Thanh Toán Đa Dạng & Sinh Mã VietQR Động
- Form đặt hàng chuẩn thương mại điện tử với kiểm tra tính hợp lệ số điện thoại và thông tin giao hàng.
- Hỗ trợ các phương thức:
  - **COD**: Thanh toán tiền mặt khi nhận hàng.
  - **VietQR 24/7**: Tự động sinh mã QR ngân hàng chuẩn VietQR chứa chính xác số tiền và mã đơn hàng giúp khách hàng quét thanh toán trong 30 giây.
  - **Ví điện tử**: MoMo / ZaloPay.
- Modal xác nhận đặt hàng thành công và giả lập thông báo đơn hàng.

### 6. Giao Diện & Trải Nghiệm (UI/UX)
- **Dark Mode & Light Mode**: Nút chuyển đổi nhanh chế độ Sáng / Tối, lưu cấu hình người dùng.
- **Hệ thống thông báo Toast**: Thông báo sinh động khi thêm giỏ, yêu thích, áp mã giảm giá...
- **Mobile Bottom Navigation**: Thanh điều hướng ngón tay cái tối ưu cho điện thoại thông minh.

---

## 📁 Cấu Trúc Thư Mục Dự Án

```
sportswear-store/
│
├── index.html            # Giao diện chính Semantic HTML5, cấu trúc trang & modal
├── css/
│   └── styles.css        # Hệ thống CSS Design System, Responsive, Dark/Light mode
├── js/
│   ├── data.js           # Dữ liệu sản phẩm, danh mục, mã voucher, size guide, đánh giá
│   ├── cart.js           # Logic giỏ hàng, wishlist, tính tiền, voucher, localStorage
│   └── app.js            # Điều khiển giao diện, bộ lọc, modal, QR code, toast notification
└── README.md             # Hướng dẫn sử dụng và tài liệu kỹ thuật
```

---

## 🚀 Hướng Dẫn Khởi Chạy

Dự án hoàn toàn độc lập, không yêu cầu cài đặt môi trường phức tạp hay Node.js/build tool:

1. **Cách 1: Mở trực tiếp bằng trình duyệt**
   - Truy cập vào thư mục: `C:\Users\duy lâm\.gemini\antigravity\scratch\sportswear-store\`
   - Nhấp đúp chuột vào tệp `index.html` để mở trên Google Chrome, Microsoft Edge hoặc trình duyệt bất kỳ.

2. **Cách 2: Chạy qua Live Server hoặc Web Server**
   - Nếu bạn dùng VS Code / Antigravity IDE: Cài đặt extension **Live Server** và nhấn **Go Live**.
   - Hoặc dùng Python (nếu có): `python -m http.server 8000`

---

## 📌 Khuyến Nghị Cài Đặt Workspace
Để làm việc thuận tiện nhất với toàn bộ mã nguồn của dự án này trong Antigravity:
- Bạn hãy mở thư mục sau làm **Active Workspace**:
  `C:\Users\duy lâm\.gemini\antigravity\scratch\sportswear-store`
