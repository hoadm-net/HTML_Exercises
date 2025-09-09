# Bài tập 2: Liên Kết và Hình Ảnh

## 🎯 Mục tiêu
- Sử dụng thẻ [`<a>`](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/a) để tạo liên kết
- Chèn hình ảnh bằng thẻ [`<img>`](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/img)
- Hiểu về đường dẫn tương đối và tuyệt đối
- Tạo menu điều hướng đơn giản

## 📋 Yêu cầu

### Tạo một trang web giới thiệu Đại học Ngoại ngữ - Tin học TP.HCM (HUFLIT) với:

1. **Header** chứa:
   - Logo HUFLIT (sử dụng [`<img>`](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/img))
   - Tên trường và slogan
   - Menu điều hướng với [`<nav>`](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/nav) chứa 4 liên kết [`<a>`](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/a): Trang chủ, Giới thiệu, Khoa, Liên hệ

2. **Phần giới thiệu trường**:
   - Tiêu đề chính [`<h1>`](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/Heading_Elements)
   - Hình ảnh campus HUFLIT với [thuộc tính `alt`](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/img#alt)
   - Đoạn văn [`<p>`](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/p) giới thiệu có liên kết [`<a>`](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/a) đến website chính thức

3. **Phần thông tin liên hệ**:
   - Địa chỉ
   - Số điện thoại (sử dụng [`tel:` protocol](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/a#tel_links))
   - Email (sử dụng [`mailto:` protocol](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/a#email_links))
   - Link đến bản đồ Google Maps với [`target="_blank"`](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/a#target)

4. **Footer**:
   - Links đến mạng xã hội (Facebook, YouTube) với icons
   - Copyright với [`<small>`](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/small)

## 🖼️ Assets cần thiết
Các file trong thư mục `assets/images/`:
- `logo.png` - Logo HUFLIT (kích thước khuyến nghị: 150x50px)
- `campus.webp` - Hình ảnh campus HUFLIT (format WebP tối ưu)
- `facebook.png` - Icon Facebook (24x24px)
- `youtube.png` - Icon YouTube (24x24px)
