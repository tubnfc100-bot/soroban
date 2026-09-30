# Bàn Tính Soroban

Trò chơi học toán bằng bàn tính **Soroban** (phương pháp Nhật Bản) cho trẻ khoảng 5–10 tuổi, có hướng dẫn chi tiết để phụ huynh kèm con học.

## Cách chạy

Mở file `index.html` bằng trình duyệt (Chrome, Edge, Safari, Firefox), trên máy tính hoặc máy tính bảng. Không cần cài đặt gì thêm.
Tiến độ (số sao) được lưu ngay trên trình duyệt đó.

## Cài lên điện thoại (PWA)

Trò chơi là một Progressive Web App: cài được lên màn hình chính và chơi được khi không có mạng.
Để cài, trò chơi cần được mở từ một địa chỉ **https** (mở file trực tiếp trên máy thì không cài được).

**Đưa lên mạng miễn phí bằng GitHub Pages**

1. Vào repo trên GitHub → **Settings** → **Pages**.
2. Ở *Build and deployment*, chọn **Source: Deploy from a branch**, chọn nhánh chứa trò chơi và thư mục **/ (root)**, bấm **Save**.
3. Sau 1–2 phút, trò chơi có ở địa chỉ dạng `https://<tên-tài-khoản>.github.io/soroban/`.

**Cài trên thiết bị**

- **Android (Chrome):** mở địa chỉ trên → bấm nút *Cài ứng dụng* trên trang, hoặc menu ⋮ → *Cài đặt ứng dụng* / *Thêm vào màn hình chính*.
- **iPhone, iPad (Safari):** mở địa chỉ trên → nút *Chia sẻ* → *Thêm vào MH chính*.
- **Máy tính (Chrome, Edge):** bấm biểu tượng cài đặt ở cuối thanh địa chỉ.

Các file liên quan: `manifest.webmanifest` (tên, màu, biểu tượng), `sw.js` (lưu sẵn để chơi ngoại tuyến), thư mục `icons/`.
Khi sửa trò chơi, hãy tăng `VERSION` trong `sw.js` để điện thoại tải bản mới.

## Nội dung

| Cấp | Kyū | Nội dung | Dạng luyện tập |
|---|---|---|---|
| 1 | 10 kyū | Làm quen bàn tính: hạt trên = 5, hạt dưới = 1, số 0–9 | Đặt số |
| 2 | 9 kyū | Đọc số 0–99 trên bàn tính | Chọn đáp án |
| 3 | 8 kyū | Đặt số 2–3 chữ số (kể cả 305, 820…) | Đặt số |
| 4 | 7 kyū | Cộng trừ trực tiếp | Tính trên bàn tính |
| 5 | 6 kyū | Bạn nhỏ (hợp 5): 1–4, 2–3 | Tính trên bàn tính |
| 6 | 5 kyū | Bạn lớn (hợp 10): cộng có nhớ, trừ có mượn | Tính trên bàn tính |
| 7 | 4 kyū | Dãy 3 số hai chữ số (dạng đề thi) | Tính trên bàn tính |
| 8 | 3 kyū | Bàn tính trên hai bàn tay (ngón cái = 5, mỗi ngón khác = 1) | Giơ/gập ngón tay |
| 9 | 2 kyū | Tính nhẩm Anzan một chữ số | Chiếu số nhanh |
| 10 | 1 kyū | Anzan hai chữ số | Chiếu số nhanh |

Mỗi cấp có 3 phần:

- **Bài học cho con**: giải thích ngắn gọn kèm bàn tính tự gạt minh họa từng bước.
- **Phụ huynh đọc**: mục tiêu, thời gian gợi ý, cách hướng dẫn, lỗi thường gặp, câu nói động viên.
- **Luyện tập**: 8–10 câu, tối đa 3 sao. Đạt 1 sao để mở cấp tiếp theo.

Ngoài ra:

- **Chế độ 2 tay**: tay phải lo cột đơn vị, tay trái lo cột chục. Bàn tính tô màu cột theo tay; bài học, gợi ý và minh họa ghi rõ tay nào, ngón nào (ngón cái đẩy hạt dưới lên, ngón trỏ kéo hạt dưới xuống và gạt hạt trên). Bạn lớn được làm bằng hai tay cùng lúc.
- **Tính nhẩm**: trang hướng dẫn 4 giai đoạn (bàn tính thật hai tay → bàn tính trên bàn tay → bàn tính ảo → Anzan), minh họa song song bàn tính và bàn tay, bài tập "Chụp ảnh bàn tính", lịch luyện mỗi ngày, dấu hiệu sẵn sàng và lỗi thường gặp.

- **Bàn tính tự do**: gạt thoải mái trên bàn tính hoặc trên hai bàn tay, hoặc nhập một phép tính để xem cách làm từng bước (khi nào dùng bạn nhỏ, bạn lớn).
- **Trang phụ huynh**: Soroban là gì, lộ trình, buổi học mẫu 15 phút, kỹ thuật ngón tay, bảng bạn nhỏ – bạn lớn, bảng tiến độ của con, cài đặt (âm thanh, mở khóa tất cả, xóa tiến độ).

## Điều khiển

- Bấm vào hạt để gạt. Hạt chỉ được tính khi chạm xà ngang.
- Bàn phím: chọn một cột bằng Tab, dùng mũi tên lên/xuống hoặc gõ số 0–9; mũi tên trái/phải để chuyển cột. Enter để sang câu tiếp theo.
