# Bài tập 6: Đa Phương Tiện và Nội Dung Nhúng

## 🎯 Mục tiêu
- Chèn video với [`<video>`](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/video) và điều khiển
- Chèn âm thanh với [`<audio>`](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/audio)
- Sử dụng [`<iframe>`](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/iframe) để nhúng nội dung
- Hiểu về [`<source>`](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/source) và nhiều định dạng
- Tối ưu đa phương tiện cho web và khả năng tiếp cận

## 📋 Yêu cầu

### Tạo trang giới thiệu HUFLIT với đa phương tiện:

1. **Video giới thiệu trường**:
   - [`<video>`](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/video) với nhiều [`<source>`](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/source)
   - Attributes: [`controls`](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/video#controls), [`poster`](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/video#poster), [`preload`](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/video#preload)
   - Fallback content cho browsers không hỗ trợ

2. **Audio podcast/interview**:
   - [`<audio>`](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/audio) với controls
   - Multiple formats (MP3, OGG)
   - Transcript cho accessibility

3. **Embedded content**:
   - Google Maps với [`<iframe>`](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/iframe)
   - YouTube video embed
   - Facebook page plugin

4. **Interactive media**:
   - [`<object>`](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/object) cho PDF embed
   - [`<embed>`](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/embed) cho interactive content

5. **Responsive và accessibility**:
   - Media queries friendly
   - Alt text và captions
   - Loading optimization
