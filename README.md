# Món quà nhỏ ♥

Trang web trái tim phát sáng kèm lời nhắn và nhạc nền.

## Các file

- `index.html`: toàn bộ trang (lời nhắn sửa trong phần `CONFIG` ở đầu đoạn `<script>`)
- `song.mp3`: nhạc nền; nếu thiếu file này, trang tự phát giai điệu hộp nhạc
- `.nojekyll`: để GitHub Pages đưa trang lên nguyên trạng

## Đưa lên GitHub Pages

1. Đăng nhập GitHub, bấm **New repository**.
2. Đặt tên repo:
   - `tên-tài-khoản.github.io` → địa chỉ sẽ là `https://tên-tài-khoản.github.io`
   - hoặc tên bất kỳ, ví dụ `monquanho` → địa chỉ là `https://tên-tài-khoản.github.io/monquanho`
3. Chọn **Public**, bấm **Create repository**.
4. Bấm **uploading an existing file**, kéo thả `index.html`, `song.mp3`, `.nojekyll` vào, bấm **Commit changes**.
5. Vào **Settings → Pages**, mục *Build and deployment* chọn **Deploy from a branch**, branch **main**, thư mục **/ (root)**, bấm **Save**.
6. Đợi 1–2 phút rồi mở địa chỉ ở bước 2.

## Sửa lời nhắn

Mở `index.html` trên GitHub (biểu tượng cây bút), tìm `const CONFIG`, sửa `lines`, `ending`, `since` (ngày bắt đầu, dạng `2024-02-14`), rồi **Commit changes**. Trang tự cập nhật sau khoảng một phút.
