# Bài tập 4: Biểu Mẫu và Nhập Liệu

## 🎯 Mục tiêu
- Tạo biểu mẫu hoàn chỉnh với [`<form>`](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/form) và validation
- Sử dụng các loại [`<input>`](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/input) khác nhau
- Hiểu về khả năng tiếp cận biểu mẫu với [`<label>`](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/label)
- Xử lý trải nghiệm người dùng trong biểu mẫu

## 📋 Yêu cầu

### Tạo trang đăng ký khóa học HUFLIT online với:

1. **Biểu mẫu thông tin cá nhân**:
   - Họ tên ([`required`](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/input#required))
   - Email ([`type="email"`](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/input/email))
   - Số điện thoại ([`pattern`](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/input#pattern) validation)
   - Ngày sinh ([`type="date"`](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/input/date))
   - Giới tính ([`type="radio"`](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/input/radio))
   - Địa chỉ ([`<textarea>`](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/textarea))

2. **Form chọn khóa học**:
   - Khóa học ([`<select>`](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/select) với [`<option>`](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/option))
   - Kỹ năng hiện tại ([`type="checkbox"`](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/input/checkbox))
   - Mức độ kinh nghiệm ([`type="range"`](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/input/range))
   - Upload CV ([`type="file"`](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/input/file))

3. **Form thông tin bổ sung**:
   - Màu sắc yêu thích ([`type="color"`](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/input/color))
   - Tìm kiếm thành phố ([`type="search"`](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/input/search) với [`<datalist>`](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/datalist))
   - Số tiền học phí ([`type="number"`](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/input/number))
   - Thời gian học ([`type="time"`](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/input/time))

4. **Form controls**:
   - Nút submit ([`type="submit"`](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/input/submit))
   - Nút reset ([`type="reset"`](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/input/reset))
   - Hidden tracking field ([`type="hidden"`](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/input/hidden))
