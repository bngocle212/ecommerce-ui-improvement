# E-commerce UI Improvement

## 1. Giới thiệu
Dự án cải tiến giao diện trang Giỏ Hàng của Shopee, giúp người dùng thao tác và thanh toán thuận tiện hơn.

## 2. Website tham khảo
- Tên website: Shopee Việt Nam
- URL: https://shopee.vn/
- Khu vực đã khảo sát: Trang Giỏ Hàng (Cart).

## 3. Chức năng
- Hiển thị danh sách sản phẩm trong giỏ phân theo Shop.
- Có thanh tóm tắt đơn hàng (Sticky Summary) dính chặt bên phải trên PC.
- Bố cục tự động chuyển đổi phù hợp với màn hình điện thoại (Responsive).

## 4. Công nghệ
- HTML5
- CSS3

## 5. Cách chạy
Mở file `index.html` bằng trình duyệt web.

## 6. Cải tiến đã thực hiện
- Vấn đề ban đầu: Tổng tiền và nút mua hàng nằm dưới đáy trang, trên PC phải cuộn chuột rất mất thời gian. Các nút "Xóa" nhỏ, khó thấy.
- Thay đổi: Chia layout thành 2 cột (Flexbox). Cột phải chứa "Tóm tắt đơn hàng" được set `position: sticky` để luôn hiển thị. Giao diện sáng sủa và tập trung vào luồng thanh toán hơn.

## 7. Hỗ trợ từ AI
- AI hỗ trợ phân tích giao diện và tạo cấu trúc HTML/CSS ban đầu (grid/flexbox).
- Tôi đã tự kiểm tra, điều chỉnh lại CSS trên mobile để thanh tóm tắt đơn hàng ghim dưới đáy màn hình (fixed bottom) thay vì dính ở trên đầu, tránh che khuất sản phẩm.