# campaign-new — Mockup Tạo phiên Callbot (MAFC Happy Call)

Mockup nâng cấp màn **Tạo phiên Callbot** của OMICRM theo yêu cầu **FR-005** cho dự án **MAFC VoiceBot Happy Call**.

## Nội dung
- `index.html` — mockup tương tác (tự chứa, mở bằng trình duyệt là chạy).
- `MAFC-TaoPhien-Upgrade-FR005.html` — bản sao cùng nội dung (tên mô tả).

## Phần nâng cấp (đánh dấu viền vàng "NÂNG CẤP" + mã FR)
- Thời gian chờ kết nối tối đa (2–30s) — FR-008
- Ưu tiên chạy khi thêm data + giới hạn 2.000 bản ghi/lần upload — FR-005 / FR-024
- Cấu hình gọi lại (Recall): kết hợp nhiều điều kiện (Trạng thái + Action + Reason), số lần tối đa, 2 tùy chọn thời điểm (sau khi đợt data hoàn thành / sau khoảng thời gian cấu hình), recall khi đầu số bị block — FR-005 / FR-025
- Tab "Theo thời gian thực" (N(t) = α × Fa(t) / Ra(t)) áp chung recall

> Ngoài phạm vi nâng cấp: "Thời gian cho phép gọi" (Cả ngày / Khung giờ) và nguồn nạp data tự động (SFTP/API) — giữ nguyên tính năng OMICRM hiện có.

## Xem online
Bật **GitHub Pages** (Settings → Pages → branch `main`) rồi mở `https://dnq98.github.io/campaign-new/`.
