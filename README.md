# 🛒 AI Customer Support Agent - Cửa hàng Giả định

Ứng dụng trợ lý ảo chăm sóc khách hàng tự động, được xây dựng trên Google AI Studio nhằm xử lý các nghiệp vụ tra cứu đơn hàng, tư vấn sản phẩm và giải quyết khiếu nại dựa trên chính sách của cửa hàng:

---

## 📂 1. Nguồn Dữ Liệu Giả Lập (Data Source)
Dự án sử dụng dữ liệu hoàn toàn giả lập để phục vụ thử nghiệm:
* **Danh mục sản phẩm:** Tên, giá, thông số, tồn kho.
* **Chính sách cửa hàng:** Quy định đổi trả, bảo hành, vận chuyển.
* **Dữ liệu đơn hàng:** 30 đơn hàng giả lập kèm mã đơn và số điện thoại giả.

> ⚠️ **Quy tắc bảo mật:** Dự án tuân thủ nghiêm ngặt nguyên tắc **không sử dụng dữ liệu thật của khách hàng**. Mọi thông tin tra cứu đều đối chiếu với bảng dữ liệu giả định để đảm bảo an toàn thông tin.

---

## 🚀 2. Hướng Dẫn Cách Chạy Dự Án Dưới 15 Phút:
1. **Truy cập ứng dụng:** Mở đường link giao diện chat của Agent tại đây: `[Dán link Google AI Studio vào đây]`
2. **Khởi tạo hội thoại:** Nhắn tin chào hỏi Agent (Agent sẽ tự động xưng hô lịch sự "anh/chị" theo cấu hình System Instruction).
3. **Thử nghiệm tra cứu đơn hàng (Nâng cao):** 
   * Khi muốn kiểm tra đơn hàng, Agent sẽ yêu cầu cung cấp **Mã đơn** và **Số điện thoại** trước để xác thực (chống lộ thông tin đơn hàng của người khác).

---

## ⚙️ 3. Giới Hạn Lượt Gọi & Lưu Ý (Rate Limits):
* **Nền tảng:** Google AI Studio
* **Hạn mức miễn phí:** Gói miễn phí có giới hạn số lượng yêu cầu (requests) nhất định mỗi phút. Nếu gặp lỗi quá tải (`ResourceExhausted` hoặc lỗi 429), vui lòng đợi 1–2 phút trước khi tiếp tục gửi câu hỏi.
