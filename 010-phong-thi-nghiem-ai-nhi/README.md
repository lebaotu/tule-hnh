# 010 — Phòng thí nghiệm AI nhí (BẢN THỬ KỸ THUẬT GĐ0)

Trang thử nghiệm kỹ thuật cho sản phẩm 010: kiểm chứng việc nạp mô hình AI (MobileNet + TensorFlow.js) và dạy máy phân loại tranh vẽ hoàn toàn trong trình duyệt.

- Trạng thái: GĐ0 — bản thử, chưa phải sản phẩm chính thức (chưa có tên chính thức, chưa nối trang mục lục).
- Cấu trúc: `index.html` + `tf.min.js` + `mo-hinh-topo.js` + 3 chunk `mo-hinh-1..3.js` chứa trọng số mô hình dạng base64 (tổng 8.827.272 byte khi giải mã), nạp bằng `tf.io.fromMemory` — cùng tệp này gói lại thành một tệp HTML duy nhất là bản offline chạy trên USB.
- Ngày đưa lên: 25/11/2026.
