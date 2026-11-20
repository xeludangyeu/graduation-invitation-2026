THIỆP MỜI TỐT NGHIỆP 2026 — WEBSITE NGANG 5 TRANG
==================================================

1. CẤU TRÚC WEBSITE
- Trang 1: Bìa thiệp (dùng ảnh gốc cầm bó hoa do người dùng cung cấp).
- Trang 2: Lời mời cá nhân.
- Trang 3: Ngày và giờ bắt đầu.
- Trang 4: Địa điểm + ảnh cổng trường + nút mở Google Maps.
- Trang 5: Form phản hồi / RSVP.
- Trang Khoảnh khắc (trang số 4 của bản cũ) đã được gỡ bỏ theo yêu cầu.

2. MỞ BẢN DEMO
- Mở file index.html bằng trình duyệt để xem giao diện (ảnh gốc nằm trong thư mục assets/).
- Dùng mũi tên trái/phải, các nút chấm trang hoặc vuốt ngang để chuyển trang.
- Trên điện thoại đang dọc: website chỉ hiện thông báo yêu cầu xoay ngang.
- Sau khi xoay điện thoại sang ngang: thiệp sẽ hiện ra.
- Nếu điện thoại khóa xoay màn hình, hãy tắt khóa xoay trước.
- Đường dẫn Google Maps cần Internet để hoạt động.

3. EMAIL NHẬN PHẢN HỒI ĐÃ ĐƯỢC CẤU HÌNH
- Email nhận: 22123045@hcmuaf.edu.vn
- Khách mời không cần đăng nhập email hoặc tạo tài khoản.
- Khách chỉ cần nhập tên, chọn trạng thái tham dự và viết lời nhắn.
- Form gửi dữ liệu bằng AJAX qua FormSubmit: https://formsubmit.co/ajax/.
- Lần đầu website được xuất bản và có người gửi form, FormSubmit sẽ gửi thư xác nhận/kích hoạt đến 22123045@hcmuaf.edu.vn.
- Chủ email cần mở thư kích hoạt và bấm xác nhận. Kiểm tra cả mục Spam/Thư rác nếu chưa thấy.
- Sau khi kích hoạt, gửi thử một phản hồi từ website đã xuất bản và kiểm tra hộp thư đến.
- Nếu thay đổi email nhận sau này, địa chỉ mới cần được xác minh lại.
- Form hiện không hỏi email của khách, nên người mời không thể trả lời riêng qua email của khách từ dữ liệu form; có thể trả lời bằng cách khác nếu khách tự để thông tin liên hệ trong lời nhắn.

4. ĐĂNG WEBSITE CÔNG KHAI
- Đưa cả thư mục (index.html và assets) lên dịch vụ hosting static như Netlify, Cloudflare Pages hoặc GitHub Pages.
- Không chỉ tải riêng index.html mà bỏ thư mục assets (sẽ mất ảnh).
- FormSubmit cần website chạy qua HTTP/HTTPS; mở trực tiếp file index.html bằng file:// chỉ để xem giao diện, không dùng để kiểm tra gửi email thật.
- Sau khi có link HTTPS, kiểm tra bằng điện thoại: dọc bị chặn, ngang thấy thiệp.
- Gửi test form một lần và kiểm tra email nhận; kiểm tra nút Maps, ảnh và dấu tiếng Việt.

5. THÔNG TIN ĐÃ CHỐT
- Ngày: Thứ Tư, 25/11/2026.
- Bắt đầu: 11h30. Không tự đặt giờ kết thúc.
- Địa điểm: Trường Đại học Nông Lâm TP. HCM.
- Ảnh bìa dùng tệp ảnh gốc của người dùng, không tạo lại hoặc chỉnh sửa khuôn mặt.
- Ảnh trường chính là ảnh cổng trường người dùng gửi, đặt tại trang Google Maps.
- Văn bản tiếng Việt dùng Unicode UTF-8; font Be Vietnam Pro và Noto Serif.

6. QUYỀN RIÊNG TƯ
- Khi xuất bản, ảnh của người thật và email nhận phản hồi trong mã website có thể được truy cập bởi người xem/mã nguồn. Chỉ xuất bản khi chủ thể ảnh đồng ý.
- FormSubmit là dịch vụ bên thứ ba xử lý nội dung phản hồi; không yêu cầu khách gửi mật khẩu, thông tin thanh toán hoặc dữ liệu nhạy cảm.
