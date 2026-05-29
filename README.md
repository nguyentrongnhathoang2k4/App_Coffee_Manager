# App Quản Lý Cửa Hàng Cà Phê (Coffee Shop Management Application)

Ứng dụng di động được phát triển trên nền tảng Android dành cho việc quản lý các hoạt động vận hành của cửa hàng cà phê. Dự án tập trung tối ưu hóa quy trình gọi món, quản lý doanh thu, bàn ăn và kho nguyên vật liệu một cách hiệu quả, trực quan.

##  Tính Năng Cốt Lõi

### 1. Quản Lý Hệ Thống & Phân Quyền
* **Đăng nhập/Đăng ký:** Xác thực tài khoản nhân viên và quản lý.
* **Phân quyền người dùng:** Tách biệt quyền thao tác giữa Quản lý (Admin) và Nhân viên (Staff).

### 2. Quản Lý Gọi Món (Order) & Hóa Đơn
* **Đặt món tại bàn:** Giao diện chọn món nhanh, tùy chỉnh số lượng, ghi chú (đá, đường,...).
* **Tự động tính hóa đơn:** Áp dụng mã giảm giá, tính tổng tiền và xuất hóa đơn thời gian thực.
* **Trạng thái bàn đơn:** Theo dõi bàn nào đang trống, bàn nào có khách để sắp xếp tối ưu.

### 3. Quản Lý Danh Mục & Sản Phẩm
* **Menu điện tử:** Thêm, sửa, xóa các món ăn, đồ uống (hình ảnh, giá bán, danh mục nhóm món).
* **Quản lý danh mục:** Phân loại đồ uống (Cà phê, Trà sữa, Sinh tố, Bánh ngọt,...).

### 4. Thống Kê & Báo Cáo Doanh Thu
* **Biểu đồ trực quan:** Thống kê doanh thu theo ngày, tuần, tháng.
* **Lịch sử hóa đơn:** Xem lại danh sách và chi tiết các hóa đơn đã thanh toán.
* **Món chạy nhất:** Thống kê các mặt hàng có số lượng tiêu thụ cao nhất để tối ưu nguồn cung.

---

## 🛠️ Công Nghệ Sử Dụng (Tech Stack)

* **Ngôn ngữ phát triển:** Kotlin / Java (Android SDK)
* **Kiến trúc ứng dụng:** MVVM (Model - View - ViewModel) giúp tách biệt logic và giao diện, dễ bảo trì.
* **UI/UX Components:** Material Design Components, Jetpack (LiveData, ViewModel, Navigation Component).
* **Cơ sở dữ liệu (Database):** Room Database (SQLite cục bộ) hoặc Firebase FireStore / Realtime Database *(Tùy thuộc cấu hình thực tế của dự án)*.
* **Xử lý hình ảnh:** Glide / Picasso.

---

##  Hướng Dẫn Cài Đặt & Chạy Dự Án

### Yêu cầu hệ thống
* Android Studio Jellyfish (hoặc phiên bản mới hơn).
* JDK 17 hoặc Gradle phù hợp theo cấu hình.
* Thiết bị giả lập (Emulator) hoặc điện thoại thật chạy Android 8.0 (API 26) trở lên.

### Các bước thực hiện

1. **Clone mã nguồn về máy cục bộ:**
   ```bash
   git clone [https://github.com/nguyentrongnhathoang2k4/App-qu-n-l-Coffee.git](https://github.com/nguyentrongnhathoang2k4/App-qu-n-l-Coffee.git)
