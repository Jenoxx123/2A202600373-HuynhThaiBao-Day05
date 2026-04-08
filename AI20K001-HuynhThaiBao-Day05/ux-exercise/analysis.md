# UX exercise — MoMo Moni AI

## Sản phẩm: MoMo — Moni AI Assistant (Trợ lý tài chính)

## 4 paths

### 1. AI đúng
* **Trạng thái:** Hệ thống hiển thị đúng các hóa đơn, giao dịch khi người dùng yêu cầu.
* **Vấn đề:** Hệ thống xác nhận (confirm) chưa rõ ràng, chỉ mới hiển thị kết quả mà chưa tạo sự tương tác hai chiều.
* **Đánh giá:** Đây là path xử lý tốt nhất hiện tại vì đáp ứng được nhu cầu tối thiểu như marketing.

### 2. AI không chắc
* **Trạng thái:** Hệ thống hỏi lại để xác nhận thông tin nhưng vẫn không đưa ra được kết quả cuối cùng.
* **Vấn đề:** Có trường hợp AI "im lặng" cho qua thay vì chủ động tương tác.
* **Hậu quả:** Người dùng cảm thấy bế tắc vì bot không phản hồi đúng trọng tâm.

### 3. AI sai
* **Trạng thái:** Thông tin mâu thuẫn. AI liên tục đưa ra các mốc thời gian trái ngược nhau trong cùng một hội thoại.
* **Vấn đề:** Người dùng tự nhận ra thông tin vô lý nhưng **hiện tại chưa thể sửa trực tiếp**.
* **Hậu quả:** Gây ức chế vì thông tin sai lệch mà không có nút đính chính ngay tại chỗ.

### 4. User mất niềm tin
* **Trạng thái:** Người dùng cảm thấy phiền vì AI chưa hiểu được ý mình hoặc nhắc nhở không đúng lúc.
* **UI hiện tại:** Có nút Exit để bỏ dùng tính năng; có Fallback kết nối nhân viên hỗ trợ; có mục đề xuất trong chat.
* **Vấn đề:** Thao tác tìm nút hỗ trợ còn rườm rà, chưa tạo được sự an tâm tức thì khi AI gây lỗi.

## Path yếu nhất: Path 2 + 3
* **Thiếu tương tác:** Khi AI không chắc hoặc sai, hệ thống thường im lặng hoặc đưa ra thông tin mâu thuẫn.
* **Thiếu công cụ chỉnh sửa:** User phát hiện sai nhưng không thể can thiệp nhanh vào nội dung AI vừa trả lời.
* **Khả năng học hỏi:** Chưa có cơ chế để user "ghim" thông tin đúng làm dữ liệu gốc cho AI học tập.

## Gap marketing vs thực tế
* **Marketing:** App được giới thiệu là trợ lý tài chính thông minh, phân tích và kiểm soát chi tiêu chuyên nghiệp.
* **Thực tế:** AI phản ứng ở mức trung bình (không nhanh không chậm), chưa tự hiểu người dùng.
* **Gap lớn nhất:** Kỳ vọng từ marketing so với thực tế chỉ khớp ở **mức tối thiểu**. AI chưa đủ "thông minh" để chủ động nhắc nhở hay hiểu sâu ngữ cảnh của user.

## Sketch (Cải thiện To-be)
* **As-is:** User hỏi về mốc thời gian → AI trả lời mâu thuẫn → User phát hiện vô lý → User bế tắc, không sửa được hoặc phải tạm dừng "thinking" để cứu đoạn chat.
* **To-be (Giải pháp đề xuất):**
    * **Thêm:** Nút **"Edit"** trực tiếp vào nội dung AI vừa trả lời để user đính chính thông tin.
    * **Thêm:** **Reference (Nguồn/Trích dẫn)** để user đối chiếu dữ liệu ngay lập tức.
    * **Bớt:** Loại bỏ sự im lặng của hệ thống khi có mâu thuẫn; bớt các bước rườm rà khi tìm hỗ trợ.
    * **Đổi:** Thay đổi cơ chế phản hồi từ "chỉ xem" sang **"cho phép ghi nhận"**. User có thể ghim thông tin đúng để AI lấy đó làm căn cứ cho các câu trả lời sau.

