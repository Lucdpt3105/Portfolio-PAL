# Hướng dẫn thêm CV vào Portfolio

## Bước 1: Chuẩn bị file CV
1. Đổi tên file CV của bạn thành: **CV_PhungAnhLuc.pdf**
2. Copy file này vào folder: `portfolio-complete/documents/`

## Bước 2: Kiểm tra
- Đường dẫn file CV phải là: 
  ```
  h:\2025-2026\Web programming\Portfolio\portfolio-complete\documents\CV_PhungAnhLuc.pdf
  ```

## Bước 3: Test
1. Mở file `index.html` trong trình duyệt
2. Scroll xuống phần "About Me"
3. Click button "Download CV"
4. File CV của bạn sẽ được tải xuống

## Lưu ý:
- Nếu bạn muốn đổi tên file CV khác, hãy cập nhật tên trong file `index.html` dòng 70:
  ```html
  <a href="./documents/TEN_FILE_CUA_BAN.pdf" download="TEN_FILE_CUA_BAN.pdf" class="btn-download">Download CV</a>
  ```

## Đã hoàn thành ✅
- ✅ Tạo folder `documents/`
- ✅ Cập nhật button Download CV thành link download
- ✅ Đưa project "Mini App E-Learning" lên đầu tiên (featured project)
- ✅ Xóa duplicate Mini App E-Learning ở cuối
- ✅ Thêm hover effect cho button Download CV
