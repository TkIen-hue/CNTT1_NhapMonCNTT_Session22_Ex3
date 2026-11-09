# Bài 3 : Sử dụng AI an toàn khi xử lý lỗi phần mềm
**Báo cáo phân tích (IPO):**
- **Input:** Gửi yêu cầu trợ giúp đến AI.
- **Process:** Lên Google gõ `site:stackoverflow.com Path not found python` sẽ hiện ra các trang câu hỏi về `Path not found python` trên stackoverflow khi vào bạn hãy lướt xuống và tìm các câu trả lời có nhiều votes và có tích xanh cũng như nhận xét của những người đã áp dụng và thành công.
- **Output:** Chú ý các lệnh AI đưa ra có `rm -rf`, có tác động đến các mục `System`.

**Prompt "hỏi ngược lại" AI để yêu cầu nó giải thích độ an toàn của câu lệnh trước khi bạn thực thi:**
- Bạn hãy phân tích ý nghĩa của từng dòng trên, đánh giá độ nguy hiểm và thiệt hại nó có thể gây ra khi cho chạy và đưa ra phương án khác an toàn hơn.(Dán dòng lệnh trên vào)