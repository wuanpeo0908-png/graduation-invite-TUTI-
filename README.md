# graduation-invite-TUTI-
# 🎓 Thiệp Mời Tốt Nghiệp 3D Tương Tác
*(Interactive 3D Graduation Invitation)*

Một dự án thiệp mời tốt nghiệp dạng web tĩnh (Static Web) sử dụng 100% HTML, CSS và JavaScript thuần (Vanilla). Dự án mang phong cách "Coquette Aesthetic" với tone màu pastel ngọt ngào, kết hợp hiệu ứng 3D mở phong bì và lật thiệp mượt mà.

## ✨ Tính Năng Nổi Bật

- **Hiệu ứng không gian 3D (3D CSS):** Trải nghiệm mở nắp phong bì, rút thiệp và lật mặt sau thiệp mượt mà bằng các thuộc tính `transform: preserve-3d`, `rotateX`, `rotateY`.
- **Tương tác vật lý ảo:** Parallax effect xoay nhẹ thiệp theo hướng di chuột (chỉ áp dụng trên máy tính/thiết bị có chuột).
- **Trang trí động (Animations):** Hạt sáng li ti bay bồng bềnh ở background và hiệu ứng pháo giấy (confetti/cánh hoa) rơi xuống khi thiệp được mở.
- **Tích hợp Âm thanh:** Nút bật/tắt nhạc nền Lofi nhẹ nhàng, kèm hiệu ứng âm thanh (Whoosh) dùng Web Audio API khi mở nắp phong bì.
- **Responsive Design:** Giao diện tự động co giãn hiển thị hoàn hảo trên các kích thước màn hình từ điện thoại di động đến màn hình lớn.
- **Zero Dependencies:** Không sử dụng bất kỳ thư viện hay framework ngoại vi nào (React, Vue, jQuery...), chỉ một file `index.html` duy nhất.

## 🚀 Hướng Dẫn Sử Dụng (Chạy Local)

1. Tải về file `index.html`.
2. Click đúp chuột vào file `index.html` để mở bằng bất kỳ trình duyệt web nào (Chrome, Safari, Edge, Firefox...).
3. Click vào phong bì để trải nghiệm hiệu ứng!

## 🎨 Hướng Dẫn Tùy Chỉnh (Customization)

Toàn bộ code được gói gọn trong file `index.html`. Bạn có thể mở file này bằng các trình soạn thảo như VS Code, Notepad++ hoặc Sublime Text để chỉnh sửa.

### 1. Thay Đổi Bảng Màu
Tìm đến đầu thẻ `<style>`, mục `:root`. Bạn có thể thay đổi mã màu HEX tại đây:
```css
:root {
    --pink-soft: #FADADD; /* Hồng nhạt */
    --pink-main: #F4B6C2; /* Hồng chủ đạo */
    --pink-deep: #E89BB0; /* Hồng đậm */
    --cream: #FFF8F0;     /* Trắng kem */
    --cream-2: #FDF6EC;   /* Kem đậm */
    --gold-rose: #D4A373; /* Vàng hồng */
}
