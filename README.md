# BeautyGlow AI – Website bán mỹ phẩm

Dự án website bán mỹ phẩm phục vụ học tập, xây dựng theo Product Backlog BeautyGlow AI.

## 1. Công nghệ
- HTML5: cấu trúc trang.
- CSS3: giao diện responsive, chế độ sáng/tối.
- JavaScript: xử lý chức năng phía trình duyệt.
- LocalStorage: lưu tài khoản demo, giỏ hàng, sản phẩm và đơn hàng trên trình duyệt.

Không cần cài Node.js, XAMPP, MySQL hoặc backend.

## 2. Các Theme / nhóm chức năng

| Theme trong Product Backlog | Chức năng minh họa |
|---|---|
| Thiết kế giao diện website | Trang chủ, danh sách sản phẩm, hồ sơ, quản trị, chatbot |
| Xây dựng tài khoản và cá nhân hóa | Đăng ký, đăng nhập, đăng xuất, xem và cập nhật hồ sơ |
| Quản lý sản phẩm | Thêm, sửa, xóa sản phẩm trong trang quản trị demo |
| Tìm kiếm và lọc mỹ phẩm | Tìm theo tên/nhãn hiệu/danh mục, lọc danh mục, thương hiệu, giá; sắp xếp |
| Giỏ hàng và thanh toán | Xem giỏ, thêm sản phẩm, tăng giảm số lượng, xóa, tính tổng |
| Hệ thống đặt hàng và quản trị đơn | Nhập thông tin nhận hàng, chọn phương thức thanh toán demo, tạo đơn, cập nhật trạng thái |
| Chatbot AI tư vấn sản phẩm | Hỏi đáp theo loại da, nhu cầu và ngân sách dựa trên dữ liệu sản phẩm mẫu |
| Triển khai và hoàn thiện | Responsive, lưu dữ liệu trình duyệt, hướng dẫn chạy và đưa lên GitHub |

## 3. Cách chạy trên máy tính

**Cách 1 – Mở trực tiếp**
1. Tải file ZIP và giải nén.
2. Mở thư mục `BeautyGlow_AI`.
3. Nhấp đúp vào `index.html`.
4. Website sẽ mở trên trình duyệt Chrome, Edge hoặc Firefox.

**Cách 2 – Dùng Visual Studio Code**
1. Cài Visual Studio Code.
2. Chọn `File → Open Folder...` và mở thư mục `BeautyGlow_AI`.
3. Cài tiện ích **Live Server** (nếu chưa có).
4. Nhấp chuột phải `index.html` → `Open with Live Server`.

## 4. Cách sử dụng website

### Khách hàng
1. Chọn **Sản phẩm** để xem danh sách.
2. Nhập từ khóa hoặc dùng bộ lọc danh mục, thương hiệu, giá và sắp xếp.
3. Nhấn dấu `+` trên sản phẩm để thêm vào giỏ.
4. Mở **Giỏ hàng** để tăng/giảm số lượng hoặc xóa sản phẩm.
5. Chọn **Tiến hành đặt hàng**, nhập thông tin nhận hàng và xác nhận.
6. Vào **Đơn hàng** để xem đơn đã tạo.

### Tài khoản
1. Mở biểu tượng tài khoản.
2. Chọn **Đăng ký**, nhập họ tên, email và mật khẩu.
3. Đăng nhập bằng email và mật khẩu vừa tạo.
4. Cập nhật số điện thoại, địa chỉ trong hồ sơ nếu cần.

### Chatbot BeautyGlow AI
1. Chọn **Tư vấn AI**.
2. Nhập câu hỏi, ví dụ: “Da dầu nên dùng gì?”, “Mình muốn dưỡng ẩm dưới 300k”, “Gợi ý routine cho da nhạy cảm”.
3. Chatbot sẽ trả lời dựa trên sản phẩm mẫu đang có trong website.

### Quản trị demo
1. Chọn **Quản trị demo** ở cuối trang.
2. Thêm sản phẩm bằng biểu mẫu; dùng nút Sửa/Xóa để quản lý.
3. Cập nhật trạng thái đơn hàng trong phần quản lý đơn hàng.

## 5. Đưa dự án lên GitHub

1. Đăng nhập https://github.com.
2. Chọn **New repository**.
3. Đặt tên repository, ví dụ `BeautyGlow_AI`.
4. Chọn Public hoặc Private rồi nhấn **Create repository**.
5. Trong repository, chọn **Add file → Upload files**.
6. Giải nén ZIP trên máy, kéo các file `index.html`, `style.css`, `app.js`, `README.md` lên GitHub. Có thể tải cả thư mục `assets` nếu bổ sung ảnh sau này.
7. Nhấn **Commit changes**.

### Bật GitHub Pages để có đường link website
1. Mở repository → **Settings**.
2. Chọn **Pages** ở thanh bên.
3. Trong **Build and deployment**, chọn `Deploy from a branch`.
4. Chọn branch `main`, folder `/ (root)`, nhấn **Save**.
5. Đợi GitHub triển khai; địa chỉ website sẽ có dạng:
   `https://TEN-TAI-KHOAN.github.io/BeautyGlow_AI/`

## 6. Tài khoản và dữ liệu demo
- Tạo tài khoản ngay trên trang Đăng ký, sau đó đăng nhập.
- Sản phẩm mẫu được nạp tự động ở lần mở đầu.
- Dữ liệu được lưu trong LocalStorage của trình duyệt hiện tại. Xóa dữ liệu trình duyệt có thể làm mất tài khoản, giỏ hàng và đơn demo.
- Không có tài khoản quản trị/mật khẩu mặc định; trang quản trị demo đang mở để tiện trình bày đồ án.

## 7. Giới hạn cần nêu trong báo cáo
- Đây là prototype frontend, chưa có backend và cơ sở dữ liệu tập trung.
- Đăng nhập chỉ mô phỏng bằng LocalStorage; không lưu mật khẩu an toàn, không dùng cho người dùng thật.
- Chưa tích hợp OTP, email, thanh toán trực tuyến hoặc cổng vận chuyển thật.
- Chatbot hiện là chatbot theo luật/từ khóa và danh sách sản phẩm mẫu, **chưa kết nối API AI**. Muốn dùng AI thực tế cần xây dựng backend và tích hợp dịch vụ AI, không đặt API key trực tiếp trong JavaScript phía trình duyệt.
- Hình sản phẩm hiện dùng minh họa bằng ký hiệu và màu nền; có thể thay bằng ảnh thật khi bổ sung thư mục ảnh.

## 8. Cấu trúc thư mục

```text
BeautyGlow_AI/
├── index.html
├── style.css
├── app.js
├── README.md
└── assets/
```

## 9. Kiểm thử nhanh
- [ ] Trang chủ và danh sách sản phẩm hiển thị.
- [ ] Tìm kiếm, lọc, sắp xếp hoạt động.
- [ ] Đăng ký, đăng nhập, đăng xuất hoạt động.
- [ ] Thêm sản phẩm vào giỏ, tăng/giảm số lượng, xóa sản phẩm.
- [ ] Tạo đơn hàng và xem lịch sử đơn.
- [ ] Chatbot trả lời các câu hỏi mẫu.
- [ ] Quản trị thêm/sửa/xóa sản phẩm và cập nhật trạng thái đơn.
- [ ] Chuyển chế độ sáng/tối và kiểm tra trên màn hình điện thoại.

---
**BeautyGlow AI – Bản demo học tập.** Nội dung sản phẩm, giá và tư vấn chỉ là dữ liệu minh họa.
