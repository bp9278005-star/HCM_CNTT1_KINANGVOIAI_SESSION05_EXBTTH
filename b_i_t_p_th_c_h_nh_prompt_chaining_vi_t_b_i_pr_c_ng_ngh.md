# BÀI TẬP THỰC HÀNH: XÂY DỰNG CHUỖI PROMPT (PROMPT CHAINING) VIẾT BÀI PR SẢN PHẨM CÔNG NGHỆ

**Họ và tên học sinh:** [Điền tên của bạn]  
**Chủ đề:** Ứng dụng kỹ thuật Prompt Chaining viết bài PR chuyên sâu (1000 - 1500 từ) cho giải pháp AI Chatbot doanh nghiệp.

---

## I. TỔNG QUAN QUY TRÌNH & NGUYÊN TẮC TRUYỀN NGỮ CẢNH

Để tránh việc AI viết bài dài bị hời hợt hoặc lặp ý khi dùng 1 prompt duy nhất, em chia quy trình thành **3 bước liên tiếp**. 

* **Nguyên tắc truyền dữ liệu:** Output của bước trước được đóng gói dưới dạng cấu trúc (Markdown/JSON-like) và dán vào biến `[INPUT_TU_BUOC_TRUOC]` của bước sau.
* **Tone & Voice xuyên suốt:** Chuyên nghiệp, tin cậy, am hiểu công nghệ nhưng dễ hiểu với chủ doanh nghiệp (B2B).

---

## II. CHI TIẾT CHUỖI 3 PROMPT THÀNH PHẦN

### BƯỚC 1: Nghiên cứu khách hàng mục tiêu & Nỗi đau (Pain Points)
*Mục tiêu: Tạo ra bộ dữ liệu nền tảng về khách hàng để định hướng nội dung.*

```text
[VAI TRÒ]
Bạn là một Chuyên gia Nghiên cứu Thị trường và Chiến lược gia Nội dung B2B trong lĩnh vực Công nghệ (SaaS/AI).

[BỐI CẢNH]
Công ty chúng tôi chuẩn bị ra mắt sản phẩm "AI Chatbot thế hệ mới" dành cho doanh nghiệp vừa và nhỏ (SMEs) tại Việt Nam, giúp tự động hóa chăm sóc khách hàng (CSKH) 24/7, tích hợp đa kênh và tự học từ dữ liệu nội bộ.

[NHIỆM VỤ]
Hãy phân tích chân dung khách hàng mục tiêu và liệt kê các nỗi đau (pain points) cốt lõi mà họ đang gặp phải trước khi dùng sản phẩm của chúng tôi.

[ĐỊNH DẠNG ĐẦU RA BẮT BUỘC]
Hãy trình bày kết quả chính xác theo cấu trúc dưới đây để làm dữ liệu đầu vào cho bước tiếp theo:
1. Chân dung người ra quyết định (Decision Maker): (Chức vụ, quy mô công ty, mục tiêu công việc).
2. Danh sách 4 Nỗi đau (Pain Points) lớn nhất:
   - Nỗi đau 1: [Tên nỗi đau] - [Mô tả chi tiết hậu quả nếu không giải quyết] - [Cách AI Chatbot giải quyết].
   - Nỗi đau 2: ...
   - Nỗi đau 3: ...
   - Nỗi đau 4: ...
3. Bộ từ khóa SEO gợi ý: (1 từ khóa chính + 4 từ khóa phụ liên quan đến giải pháp).
```

---

### BƯỚC 2: Lập dàn ý chi tiết chuẩn SEO (Outline)
*Mục tiêu: Sử dụng dữ liệu từ Bước 1 để xây dựng khung xương bài viết dài 1000 - 1500 từ, đảm bảo không bị thiếu ý.*

```text
[VAI TRÒ]
Bạn là một Biên tập viên Trưởng (Senior Content Editor) chuyên viết bài PR công nghệ trên các trang báo kinh doanh uy tín (như CafeF, VnExpress, Forbes).

[DỮ LIỆU ĐẦU VÀO]
Dưới đây là kết quả nghiên cứu khách hàng và từ khóa từ Bước 1:
"""
[DÁN TOÀN BỘ OUTPUT CỦA BƯỚC 1 VÀO ĐÂY]
"""

[NHIỆM VỤ]
Dựa trên dữ liệu đầu vào ở trên, hãy lập một Dàn ý chi tiết (Outline) cho bài viết PR dài khoảng 1200 - 1500 từ giới thiệu giải pháp AI Chatbot.

[YÊU CẦU CẤU TRÚC & RÀNG BUỘC]
1. Đề xuất 3 Tiêu đề chính (Headline) thu hút, chứa từ khóa chính, đánh trúng tâm lý chủ doanh nghiệp.
2. Phần Mở đầu (Lead - khoảng 150 từ): Nêu bối cảnh thị trường và xoáy sâu vào Nỗi đau 1 & 2.
3. Thân bài: Chia thành 4 thẻ H2 chính. Trong mỗi H2 phải có từ 2-3 thẻ H3 giải quyết triệt để các nỗi đau còn lại và làm nổi bật tính năng sản phẩm. Ghi rõ số từ dự kiến cho từng phần.
4. Kết bài & CTA (khoảng 150 từ): Tóm tắt giá trị cốt lõi và đưa ra Lời kêu gọi hành động (CTA) thuyết phục (ví dụ: đăng ký dùng thử miễn phí 14 ngày).
5. Giữ nguyên văn phong: Chuyên nghiệp, khách quan, tin cậy. Không viết nội dung chi tiết, chỉ lập dàn ý kèm gạch đầu dòng các ý chính cần triển khai trong mỗi mục.
```

---

### BƯỚC 3: Triển khai bài viết chi tiết & Tối ưu SEO
*Mục tiêu: Viết bài hoàn chỉnh dựa trên dàn ý ở Bước 2, kiểm soát độ dài và chất lượng câu chữ.*

```text
[VAI TRÒ]
Bạn là một Chuyên gia Copywriter B2B dày dặn kinh nghiệm.

[DỮ LIỆU ĐẦU VÀO]
1. Dữ liệu khách hàng & Từ khóa (Từ Bước 1):
"""
[DÁN LẠI MỤC 1 VÀ MỤC 3 CỦA BƯỚC 1 VÀO ĐÂY]
"""
2. Dàn ý chi tiết (Từ Bước 2):
"""
[DÁN TOÀN BỘ OUTPUT CỦA BƯỚC 2 VÀO ĐÂY]
"""

[NHIỆM VỤ]
Hãy viết bài PR hoàn chỉnh (độ dài mục tiêu: 1200 - 1500 từ) bám sát từng đề mục H2, H3 trong Dàn ý đã cung cấp.

[QUY TẮC VIẾT BÀI & TỐI ƯU SEO]
1. Giọng điệu (Tone): Duy trì xuyên suốt sự chuyên nghiệp, tin cậy, mang tính tư vấn giải pháp (không quảng cáo phô trương sáo rỗng).
2. Cấu trúc: Sử dụng đúng định dạng Markdown cho Headline (H1), các tiêu đề con (H2, H3).
3. Mở bài (Lead): Phải giải quyết ngay bài toán/nỗi đau của khách hàng để giữ chân người đọc.
4. Thân bài: Phân tích sâu, có ví dụ thực tế hoặc số liệu giả định hợp lý (ví dụ: "giảm 70% thời gian phản hồi") để tăng tính thuyết phục. Chèn từ khóa SEO tự nhiên vào H1, H2 và rải đều trong các đoạn văn.
5. Kết bài: Có đoạn CTA rõ ràng, thúc đẩy hành động ngay.

[LƯU Ý QUAN TRỌNG]
Hãy viết sâu sắc và chi tiết nhất có thể cho từng mục, không tóm tắt hay viết lướt qua. Bắt đầu viết ngay từ Tiêu đề bài viết.
```

---

## III. QUY TẮC XỬ LÝ KHI AI BỊ ĐỨT GÃY NGỮ CẢNH (MAX TOKEN)

Khi yêu cầu AI viết bài dài trên 1000 từ, hệ thống thường bị dừng đột ngột giữa chừng (hết giới hạn token). Nếu gõ "Viết tiếp đi" chung chung, AI dễ bị lặp lại ý hoặc đổi giọng văn. 

Dưới đây là **Prompt điều khiển tiếp tục** chuẩn xác để nối mạch văn hoàn hảo:

```text
[LỆNH ĐIỀU KHIỂN TIẾP TỤC]
Bạn vừa bị ngắt quãng do giới hạn độ dài. Hãy tiếp tục viết phần còn lại của bài PR dựa trên Dàn ý ở Bước 2.

[RÀNG BUỘC NỐI MẠCH]
1. KHÔNG viết lại tiêu đề, không chào hỏi, không tóm tắt lại những gì đã viết.
2. Đọc kỹ 2 câu cuối cùng bạn vừa tạo ra trước khi bị ngắt là:
   """
   [COPY VÀ DÁN 2 CÂU CUỐI CÙNG BỊ NGẮT VÀO ĐÂY]
   """
3. Hãy bắt đầu câu tiếp theo nối khớp hoàn hảo về mặt ngữ pháp và ý nghĩa ngay sau dấu chấm/từ cuối cùng ở trên.
4. Duy trì tuyệt đối giọng điệu chuyên nghiệp, tin cậy như các phần trước cho đến khi hoàn thành hết phần Kết bài và CTA.
```

---

## IV. TỰ ĐÁNH GIÁ CỦA HỌC SINH
* **Ưu điểm của chuỗi Prompt này:** Đã tách bạch rõ ràng khâu *Nghiên cứu (Tư duy)* -> *Lập dàn ý (Cấu trúc)* -> *Viết bài (Triển khai)*. Việc đóng khung dữ liệu bằng dấu ngoặc kép `"""` giúp AI nhận diện chính xác biến đầu vào từ bước trước.
* **Khắc phục lỗi đứt gãy:** Lệnh điều khiển tiếp tục có cơ chế "neo" lại 2 câu cuối cùng giúp AI không bị mất trí nhớ ngắn hạn và nối chữ mượt mà như một bài viết liền mạch.