# Hướng Dẫn Tạo QR Code Cho Lá Thư 20/10 💝

## Bước 1: Đưa file lên hosting

Bạn cần đưa file `20-10-letter.html` lên một dịch vụ hosting miễn phí. Có 3 cách dễ nhất:

### Cách 1: Sử dụng GitHub Pages (Khuyên dùng - Miễn phí mãi mãi)

1. Tạo tài khoản GitHub (nếu chưa có): https://github.com
2. Tạo repository mới (public)
3. Upload file `20-10-letter.html` và đổi tên thành `index.html`
4. Vào Settings > Pages > chọn branch main > Save
5. Đợi 1-2 phút, link sẽ có dạng: `https://[username].github.io/[repo-name]`

### Cách 2: Sử dụng Netlify Drop (Nhanh nhất)

1. Truy cập: https://app.netlify.com/drop
2. Kéo thả file `20-10-letter.html` vào (đổi tên thành `index.html` trước)
3. Nhận ngay link, ví dụ: `https://[random-name].netlify.app`

### Cách 3: Sử dụng Vercel

1. Truy cập: https://vercel.com
2. Đăng ký tài khoản miễn phí
3. New Project > Upload file `20-10-letter.html` (đổi tên thành `index.html`)
4. Deploy và nhận link

## Bước 2: Tạo QR Code

Sau khi có link, tạo QR code bằng một trong các cách sau:

### Cách 1: QR Code Generator Online (Dễ nhất)

1. Truy cập: https://www.qr-code-generator.com/
2. Dán link của bạn vào ô "Enter content"
3. Chọn "Download" để tải QR code (PNG)
4. In ra hoặc gửi trực tiếp cho bạn gái

### Cách 2: QR Monkey (Có thể tùy chỉnh màu sắc, logo)

1. Truy cập: https://www.qrcode-monkey.com/
2. Dán link vào
3. Tùy chỉnh màu sắc, thêm logo (có thể thêm trái tim ❤️)
4. Download QR code chất lượng cao

### Cách 3: Sử dụng Python (Nếu bạn biết lập trình)

```python
pip install qrcode pillow

import qrcode

# Thay YOUR_LINK bằng link thực của bạn
url = "YOUR_LINK"

qr = qrcode.QRCode(version=1, box_size=10, border=5)
qr.add_data(url)
qr.make(fit=True)

img = qr.make_image(fill_color="red", back_color="white")
img.save("qr_20_10.png")
```

## Bước 3: Tặng quà

### Ý tưởng 1: In QR code
- In QR code ra giấy đẹp
- Viết dòng chữ: "Quét mã để nhận thư yêu 💕"
- Tặng kèm hoa hồng hoặc quà

### Ý tưởng 2: Gửi qua điện thoại
- Gửi ảnh QR code qua Zalo/Messenger
- Kèm lời nhắn: "Em hãy quét mã này nhé 😊"

### Ý tưởng 3: Tạo bất ngờ
- Đặt QR code ở nơi bạn gái hay đi qua
- Dẫn em đến và để em khám phá

## Lưu ý

✅ Test kỹ QR code trước khi tặng bằng cách quét thử trên điện thoại
✅ Đảm bảo link hoạt động tốt trên cả điện thoại và máy tính
✅ File HTML đã bao gồm responsive design, hiển thị đẹp trên mọi thiết bị
✅ Có thể chỉnh sửa nội dung thư trong file HTML trước khi upload

## Tùy chỉnh thông điệp

Để thay đổi nội dung lá thư, mở file `20-10-letter.html` và tìm đoạn:

```html
<div class="letter-content">
    <h2>Gửi em yêu của anh ❤️</h2>
    <p>Nhân ngày Phụ nữ Việt Nam 20/10...</p>
    ...
</div>
```

Sửa các đoạn văn bản theo ý muốn của bạn!

---

💝 Chúc bạn và bạn gái có một ngày 20/10 thật ý nghĩa và hạnh phúc! 💝
