# THƯ VIỆN 100 CÂU LỆNH AI – HỘI CỰU CHIẾN BINH PHƯỜNG RẠCH GIÁ

Website phiên bản **2.0**: https://vukhanh121.github.io/100-CAU-LENH-AI-CCB/

## Các chức năng
- 100 câu lệnh gốc chia theo 8 nhóm nghiệp vụ (dữ liệu trong `data.js`).
- Tìm kiếm tiếng Việt không dấu, lọc nhóm và danh mục tác vụ thường dùng.
- Bật/tắt chữ lớn dành cho hội viên cao tuổi (ghi nhớ trên thiết bị).
- Nghe câu lệnh bằng giọng nói tiếng Việt nếu trình duyệt hỗ trợ Web Speech API.
- Tạo ô nhập tự động từ các đoạn `[thông tin]` trong câu lệnh; vẫn có thể sửa nội dung trực tiếp.
- Lưu yêu thích ngay trên thiết bị qua localStorage; không đồng bộ giữa các thiết bị.
- Hướng dẫn tập huấn 3 bước; mã QR và chế độ in.
- Sao chép câu lệnh rồi dán vào ChatGPT/Gemini (không chuyển dữ liệu tự động).

## Cấu trúc
- `index.html`: giao diện, điều hướng, trang hướng dẫn.
- `style.css`: giao diện responsive và chế độ chữ lớn.
- `script.js`: xử lý tìm kiếm, bộ lọc, yêu thích, biểu mẫu, giọng nói, sao chép.
- `data.js`: **100 câu lệnh gốc**, giữ nguyên khi nâng cấp.

## Lưu ý
- Website tĩnh không có backend; không nhập thông tin nhạy cảm lên công cụ AI.
- Đọc văn bản phụ thuộc giọng tiếng Việt trên thiết bị/trình duyệt.
- Mã QR sử dụng dịch vụ ảnh `api.qrserver.com`; nếu dịch vụ bị chặn, liên kết website vẫn hiển thị.
- Nội dung chính sách cần kiểm chứng theo quy định hiện hành trước khi sử dụng.
- Để xuất bản GitHub Pages: Settings → Pages → Deploy from a branch → main / (root).
