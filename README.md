# Web/app học tập — Hóa học 8, Bài 3

**Bài 3: Mol và tỉ khối chất khí**
Môn Khoa học tự nhiên 8 (phân môn Hóa học) — Chương trình GDPT 2018, sách Kết nối tri thức với cuộc sống.

Giáo viên: Lê Văn Thắng — Trường TH và THCS Phước Hưng, xã Nhơn Hội, tỉnh An Giang.

## Nội dung

Web/app học tập 6 phần: Khởi động, Khám phá, Mô phỏng, Sơ đồ tư duy, Luyện tập (10 câu trắc nghiệm tự chấm), Vận dụng.

Bài 3 không có thí nghiệm trong sách giáo khoa nên phần Mô phỏng gồm 3 công cụ tính tương tác:
1. Máy tính mol — từ khối lượng ra số mol và số hạt (n = m/M, N = n × Nᴀ).
2. Thể tích khí ở điều kiện chuẩn (25 °C, 1 bar) — đổi hai chiều số mol ↔ thể tích (V = 24,79·n).
3. So sánh tỉ khối hai chất khí — khí nhẹ hơn bay lên, khí nặng hơn lắng xuống (d = Mᴀ/Mʙ).

## Cách dùng

- Mở file `index.html` bằng trình duyệt bất kì (không cần máy chủ).
- Học sinh đăng nhập bằng Họ tên + Lớp, học 6 phần, làm 10 câu trắc nghiệm rồi nộp bài.
- Điểm hiện lưu trên máy học sinh (localStorage). Sau khi Apps Script của bài được deploy và patch link Web App vào file, điểm sẽ tự động lưu về Google Sheets của giáo viên (qua Apps Script Web App, chạy bằng tài khoản giáo viên).

## File trong repo

- `index.html` — web/app hoàn chỉnh, tự chứa (hình ảnh nhúng base64).
- `Web_Hoc_Tap_Hoa8_Bai03.md` — bản sao toàn bộ mã nguồn kèm khóa đáp án.
- `Code.gs` — mã Apps Script ghi điểm về Google Sheets (deploy sau).
- `assets-flow/` — 3 ảnh nền gốc (JPG 1376×768) + logo giáo viên (PNG 500×500).
