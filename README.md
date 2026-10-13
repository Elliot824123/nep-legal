# Nếp. — Website hỗ trợ & chính sách quyền riêng tư

**Mỗi ngày, một bước.**

Website tĩnh bằng HTML dành cho ứng dụng iOS **Nếp**, gồm trang giới thiệu, hỗ trợ và chính sách quyền riêng tư. Thiết kế tối giản, hiển thị tốt trên điện thoại; không cần cài đặt thư viện hoặc máy chủ backend.

## Các tệp

| Tệp | Mục đích |
| --- | --- |
| `index.html` | Trang chủ của Nếp. |
| `nep_support.html` | Trang hỗ trợ, hướng dẫn, câu hỏi thường gặp và email liên hệ. |
| `nep_privacy.html` | Chính sách quyền riêng tư. |
| `README.md` | Hướng dẫn xuất bản website. |

**Email hỗ trợ:** [nep.support@gmail.com](mailto:nep.support@gmail.com)

## Đưa lên GitHub Pages

1. Tạo một **public repository** mới trên GitHub, ví dụ `nep-pages`.
2. Tải cả **4 tệp** trong bộ này vào **thư mục gốc** (root) của repository. Không đặt chúng trong thư mục con nếu bạn muốn dùng đường dẫn ở dưới.
3. Trên GitHub, mở **Settings → Pages**.
4. Trong **Build and deployment**, chọn **Deploy from a branch**.
5. Chọn nhánh `main`, thư mục `/(root)`, rồi **Save**.
6. Khi GitHub Pages hiển thị địa chỉ, mở website để kiểm tra ba trang và nút gửi email.

Ví dụ địa chỉ (thay `TEN_GITHUB` và `TEN_REPO` bằng tên thực của bạn):

- **Trang chủ**: `https://TEN_GITHUB.github.io/TEN_REPO/`
- **Support URL** cho App Store Connect: `https://TEN_GITHUB.github.io/TEN_REPO/nep_support.html`
- **Privacy Policy URL** cho App Store Connect: `https://TEN_GITHUB.github.io/TEN_REPO/nep_privacy.html`

Nếu bạn dùng repository tên `TEN_GITHUB.github.io`, URL có thể là `https://TEN_GITHUB.github.io/` và các tệp tương ứng ở ngay sau tên miền.

> GitHub Pages cần thời gian để xuất bản sau khi lưu thiết lập. Chỉ dán đường dẫn vào App Store Connect sau khi mở được trang HTTPS công khai trong trình duyệt.

## Kiểm tra trước khi phát hành

- [ ] Email `nep.support@gmail.com` nhận được thư.
- [ ] Cả ba trang web mở được công khai bằng HTTPS.
- [ ] Các liên kết qua lại hoạt động đúng trên điện thoại.
- [ ] Nếp thực sự **không yêu cầu đăng nhập, không có mua hàng trong ứng dụng**.
- [ ] Thông tin lưu trên thiết bị và cách xóa/khôi phục dữ liệu trong phần hỗ trợ phù hợp với bản phát hành thực tế.
- [ ] Kiểm tra những SDK còn tích hợp (ví dụ RevenueCat, analytics, crash reporting) và dữ liệu chúng có thể truyền đi. Cập nhật chính sách và phần **App Privacy** trong App Store Connect cho khớp với hành vi thực tế; việc không có tài khoản hay thu phí không tự động có nghĩa là ứng dụng không thu thập dữ liệu.
- [ ] Nếu sau này thêm tính năng đăng nhập, thanh toán, đồng bộ, quảng cáo hoặc phân tích hành vi, hãy cập nhật chính sách trước khi phát hành bản tương ứng.

## Chỉnh sửa

Các tệp `.html` có CSS tích hợp sẵn, không phụ thuộc font, ảnh hoặc thư viện bên ngoài. Bạn có thể mở trực tiếp bằng trình duyệt hoặc sửa bằng trình soạn thảo văn bản. Khi cập nhật trang trên GitHub, chỉ cần commit bản sửa; đường dẫn vẫn giữ nguyên.

© 2026 Nếp.
