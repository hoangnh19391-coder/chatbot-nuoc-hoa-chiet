# Chatbot Giọt Hương Decant

Kịch bản chatbot cho dự án Marketing Automation, dựng trên thương hiệu hư cấu **Giọt Hương Decant** (nước hoa chiết từ chai fullsize).

Xem trực tiếp: https://hoangnh19391-coder.github.io/chatbot-nuoc-hoa-chiet/

## Nội dung

- **Trải nghiệm chatbot**: chat thử với bot "Giọt", kèm bảng workflow chạy song song (bước hiện tại, bộ đếm lỗi, thông tin đã thu thập, nhật ký).
- **Persona**: persona người dùng (Minh Khoa, 23 tuổi) và persona hệ thống (Giọt, xưng "mình", gọi "bạn").
- **Hành trình**: 4 chặng Nhận biết → Quan tâm → Cân nhắc → Chuyển đổi.
- **Kịch bản 6 lượt**: hoàn cảnh dùng → nhóm mùi → dung tích → mua kèm ống thử → cách nhận hàng → thanh toán.
- **Workflow**: sơ đồ luồng cấp cao, quy tắc xử lý nhánh không khớp, bảng trạng thái.

## Nhánh không khớp

1. Lần 1: xin lỗi ngắn kèm câu hỏi rút gọn.
2. Lần 2: thêm lựa chọn hoặc ví dụ, hiện nút trả lời nhanh.
3. Sau hai lần nhắc không thành, hoặc 3 lỗi liên tiếp: kết thúc, chỉ cách gặp nhân viên thật.

Gõ "gặp nhân viên" ở bất kỳ bước nào để chuyển ngay, "bắt đầu lại" để quay về lượt 1.

## Chạy

Một file `index.html` thuần, không cần build hay server. Bot dùng luật so khớp từ khoá, chạy hoàn toàn trong trình duyệt, không gửi dữ liệu đi đâu.
