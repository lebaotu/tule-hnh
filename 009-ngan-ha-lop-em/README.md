# 009 — Ngân Hà Lớp Em

Ứng dụng sinh hoạt lớp học của hệ tule-hnh: mỗi lớp là một ngân hà, mỗi học sinh là một ngôi sao, mỗi tổ là một chòm sao. Thầy gọi tên bằng trò chơi, tặng sao theo quy tắc rõ ràng, học sinh đổi sao lấy đặc quyền trong lớp — và hồ sơ sao của từng em đi theo em suốt nhiều năm học, từ lớp 3 lên lớp 5.

**Tác giả:** Lê Bảo Tú — Giáo viên Tin học, Trường Tiểu học Huỳnh Ngọc Huệ.
**Bản trực tuyến:** https://lebaotu.github.io/tule-hnh/009-ngan-ha-lop-em/

## Ý tưởng

009 là bản nâng cấp toàn diện của "Ngôi sao lớp em" — sản phẩm theo ý tưởng của chính thầy Tú, đã dùng thật trong lớp — kết hợp lợi thế riêng của nhà tule-hnh: danh sách 21 lớp / 708 học sinh nạp sẵn từ dữ liệu của 003, bộ 40 nhân vật đại diện vẽ riêng cho học sinh nam/nữ, và chế độ gọi tên kèm câu hỏi rút từ ngân hàng 10.923 câu của 004 theo đúng bài đang dạy.

## Chức năng chính

- **Sảnh Gọi Sao** — 4 vỏ trò gọi tên ngẫu nhiên (ưu tiên bạn ít được gọi, có công tắc không gọi trùng trong tiết):
  - **Vòng Xoáy Ngân Hà** — thẻ nhân vật xoay như dải ngân hà, dừng ở một ngôi sao và phóng to tỏa sáng.
  - **Đường Đua Sao Băng** — 6–8 ngôi sao ứng viên lao về đích, sao về nhất là bạn được gọi.
  - **Cần Cẩu Hái Sao** — cần cẩu vũ trụ gắp một quả cầu sao trên bầu trời và mở ra tên bạn được gọi.
  - **Rương Sao Bí Ẩn** — chạm mở một rương sao phát sáng, bên trong là bạn được gọi.
- **Hai chế độ gọi tên:** *Gọi Sao* (chỉ gọi tên) và *Gọi Sao Thử Thách* (bạn được gọi trả lời một câu hỏi rút từ gói dữ liệu của 004 theo Môn → Lớp → Chủ đề → Bài; đúng tự cộng sao, sai hiện lời giải thích để thầy chốt kiến thức).
- **Sao và cấp sao:** quy tắc cộng/trừ rõ ràng (Phát biểu tốt, Thực hành giỏi, Giúp đỡ bạn, Sáng tạo…; điểm trừ chỉ trừ sao khả dụng, không làm tụt cấp), thang cấp sao ngân hà 5 bậc, 8 huy chương vĩnh viễn trong hồ sơ.
- **Trạm Đổi Sao** — học sinh đổi sao khả dụng lấy đặc quyền trong lớp (chọn chỗ ngồi, làm tổ trưởng chòm sao một tuần…); mỗi lần đổi ghi vào sổ cái và chờ thầy duyệt trao.
- **Tiết học trọn vẹn:** lưới thẻ học sinh theo nhân vật + cấp sao, ghi nhận 2 chạm (kèm sửa nhanh giới tính/nhân vật), điểm danh 3 trạng thái, hẹn giờ, chọn nhiều / theo chòm sao / cả lớp, hoàn tác, kết thúc tiết bằng **Khoảnh Khắc Tỏa Sáng** (vinh danh kèm pháo giấy).
- **Thi đua chòm sao** theo tiết / tuần / tháng / cả năm, bảng cá nhân xuất sắc, **Bầu Trời Lớp** để ngắm toàn cảnh lớp.
- **Hồ sơ sao vĩnh cửu:** nhân vật, huy chương và lịch sử của từng em đi theo em khi lên lớp; trang **Hành Trình Sao** vẽ hành trình nhiều năm học — dùng được cả khi họp phụ huynh.
- **Chuẩn nhà tule-hnh:** chạy offline sau khi tải, đồng bộ Google Drive qua Apps Script, sao lưu/khôi phục bằng tệp qua USB, khóa PIN cho cài đặt, xuất tổng hợp tham gia & nề nếp sang 003.

## Nhật ký cập nhật

- **19/11/2026 — v1.0:** phát hành bản đầu tiên — Sảnh Gọi Sao với 4 vỏ trò × 2 chế độ (chế độ Thử Thách rút câu từ ngân hàng của 004), nạp sẵn 21 lớp / 708 học sinh với bộ 40 nhân vật tự gán theo giới tính, tặng sao theo quy tắc với thang cấp sao 5 bậc và 8 huy chương, Trạm Đổi Sao (quà đặc quyền), thi đua chòm sao, Bầu Trời Lớp, hồ sơ sao vĩnh cửu + Hành Trình Sao nhiều năm học, đồng bộ Drive qua Apps Script và sao lưu bằng tệp.
