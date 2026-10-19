# AI Usage Log

## 1. Công cụ AI
Tên công cụ: Gemini / ChatGPT

## 2. Mục đích sử dụng
Phân tích giao diện website Shopee, đề xuất bố cục cải tiến cho trang Giỏ hàng và hỗ trợ viết mã HTML/CSS.

## 3. Prompt đã sử dụng
"Tôi đang thực hiện bài tập phát triển giao diện website thương mại điện tử bằng HTML5 và CSS3. Tôi muốn cải tiến khu vực: Giỏ hàng. Đối tượng sử dụng: khách hàng mua sắm trực tiếp trên máy tính và điện thoại. Hãy đề xuất bố cục giao diện chia 2 cột trên PC (cột trái là sản phẩm, cột phải là tóm tắt đơn hàng dạng sticky) và gộp thành 1 cột trên mobile. Chỉ sử dụng HTML/CSS, không dùng backend. Hãy giải thích phương án thiết kế trước."

## 4. Kết quả AI đề xuất
AI đã đề xuất dùng Flexbox để chia 2 cột trên PC và dùng thuộc tính `position: sticky` cho cột tóm tắt đơn hàng. AI cũng cung cấp mã HTML và CSS cơ bản.

## 5. Kiểm tra và điều chỉnh
- Tôi đã kiểm tra giao diện trên cả PC và Mobile (bằng DevTools F12).
- Tôi không sử dụng toàn bộ code của AI mà đã tự sửa lại phần Responsive trên Mobile. Cụ thể, AI không tối ưu tốt phần khung tóm tắt, tôi đã đổi `position: sticky` thành `position: fixed; bottom: 0;` trên màn hình dưới 768px để thanh toán không bị che khuất.

## 6. Phần tôi hiểu và có thể giải thích
Tôi hiểu rõ cách hoạt động của Flexbox (`display: flex`) trong file CSS để chia 2 cột trái/phải, và ý nghĩa của `position: sticky` / `position: fixed` dùng để ghim thanh "Tóm tắt đơn hàng" đứng yên khi người dùng cuộn chuột.