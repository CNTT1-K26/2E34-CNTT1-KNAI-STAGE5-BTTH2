| Bước | Đầu vào bắt buộc | Đầu ra (khối dữ liệu truyền) | Dùng ở |
|:---|:---|:---|:---|
| Prompt 1 | `<BRIEF>` | `<PERSONA_PAINPOINTS>` | Prompt 2 |
| Prompt 2 | `<BRIEF>` + `<PERSONA_PAINPOINTS>` | `<OUTLINE>` | Prompt 3 |
| Prompt 3 | `<BRIEF>` + `<PERSONA_PAINPOINTS>` + `<OUTLINE>` | Bài PR | Xuất bản |
Khối BRIEF (điền một lần, dùng xuyên suốt chuỗi)

<BRIEF>
- Tên sản phẩm: [VD: ...]

- Mô tả ngắn: AI Chatbot cho doanh nghiệp, [tính năng chính 1, 2, 3]

- Điểm khác biệt (USP): [...]

- Số liệu/bằng chứng có thật: [VD: giảm 40% thời gian phản hồi. Chỉ ghi số liệu thật]

- Thị trường: Việt Nam

- Từ khóa chính: [VD: AI chatbot cho doanh nghiệp]

- Từ khóa phụ: [3–5 từ khóa]

- CTA mong muốn: [VD: đăng ký dùng thử 14 ngày tại ...]

- Giọng điệu: Chuyên nghiệp, tin cậy, rõ ràng, không phóng đại

- Độ dài: 1.000–1.500 từ
</BRIEF>
3. Prompt 1: Nghiên cứu đối tượng và pain points
# VAI TRÒ
Bạn là chuyên gia nghiên cứu thị trường B2B công nghệ tại Việt Nam.

# NHIỆM VỤ
Dựa trên <BRIEF> bên dưới, xác định đối tượng khách hàng mục tiêu và lập danh sách
nỗi đau (pain points) mà sản phẩm giải quyết. Hãy suy nghĩ từng bước: xác định ngành
và vai trò ra quyết định trước, rồi mới suy ra pain point.

[DÁN <BRIEF> VÀO ĐÂY]

# QUY TẮC
1. Chỉ nêu pain point mà sản phẩm trong BRIEF thực sự giải quyết được. Không bịa tính năng.
2. Mỗi pain point phải có mã PP1, PP2... (tối đa 5, sắp xếp từ nghiêm trọng nhất).
3. Không bịa số liệu thống kê. Nếu cần số liệu, ghi "[cần xác minh]".
4. Không viết bài, chỉ nghiên cứu.

# ĐỊNH DẠNG ĐẦU RA (bắt buộc đúng cấu trúc)
<PERSONA_PAINPOINTS>
## Chân dung khách hàng
- Ngành: ...
- Quy mô doanh nghiệp: ...
- Người ra quyết định: ... (chức danh)
- Mục tiêu kinh doanh: ...
- Mối quan tâm khi mua: ...

## Danh sách Pain Points
| Mã | Pain point | Biểu hiện thực tế | Hậu quả kinh doanh | Tính năng giải quyết (từ BRIEF) |
|---|---|---|---|---|
| PP1 | ... | ... | ... | ... |

## Từ khóa/cụm từ khách hàng hay dùng khi tìm giải pháp
- ... (5–8 cụm, phục vụ SEO)
</PERSONA_PAINPOINTS>

Kiểm tra trước khi sang Prompt 2: mỗi PP đều ánh xạ được tới một tính năng trong BRIEF, và không có số liệu nào chưa xác minh bị đưa như sự thật.

4. Prompt 2: Lập dàn ý chi tiết
# VAI TRÒ
Bạn là biên tập viên nội dung kiêm chuyên gia SEO.

# NHIỆM VỤ
Dựa BẮT BUỘC vào <PERSONA_PAINPOINTS> và <BRIEF>, lập dàn ý chi tiết cho bài PR.
Hãy suy nghĩ từng bước: (1) chọn góc tiếp cận từ PP quan trọng nhất,
(2) sắp xếp mạch bài, (3) phân bổ số từ, (4) gán từ khóa cho từng mục.

[DÁN <BRIEF> VÀO ĐÂY]
[DÁN NGUYÊN VĂN <PERSONA_PAINPOINTS> TỪ PROMPT 1 VÀO ĐÂY]

# QUY TẮC
1. Mỗi pain point PP1...PPn phải được xử lý ít nhất một lần. Ghi rõ mã PP ở mỗi mục.
2. Cấu trúc bắt buộc: Headline → Lead → H2/H3 → CTA.
3. Tổng số từ các mục phải bằng 1.000–1.500 (ghi phép cộng).
4. Từ khóa chính xuất hiện trong Headline, Lead và ít nhất 2 H2. Mỗi H2 có 1 từ khóa phụ.
5. Mạch bài: Vấn đề → Hậu quả → Giải pháp → Bằng chứng → Hành động.
6. Chốt giọng điệu một lần ở đầu dàn ý. Các phần sau phải theo đúng giọng này.

# ĐỊNH DẠNG ĐẦU RA
<OUTLINE>
## Quy chuẩn viết (áp dụng cho mọi phần)
- Giọng điệu: ...
- Ngôi xưng: ... (VD: "chúng tôi" cho công ty, "doanh nghiệp của bạn" cho khách hàng)
- Thuật ngữ thống nhất: [Vvd: luôn dùng "AI Chatbot", không đổi sang "trợ lý ảo"]

## Dàn ý
| Mã | Cấp | Tiêu đề dự kiến | Nội dung chính | PP liên quan | Từ khóa | Số từ |
|---|---|---|---|---|---|---|
| S0 | H1 | Headline | ... | ... | từ khóa chính | - |
| S1 | Lead | Mở đầu | ... | PP1, PP2 | ... | 120 |
| S2 | H2 | ... | ... | ... | ... | ... |
| S2.1 | H3 | ... | ... | ... | ... | ... |
| Sn | H2 | CTA | ... | - | ... | 80 |

Tổng số từ: a + b + c + ... = ...
</OUTLINE>

Kiểm tra trước khi sang Prompt 3: mọi PP đều có mặt trong dàn ý, tổng số từ nằm trong 1.000–1.500, mạch bài không lặp ý giữa các mục.

5. Prompt 3: Viết chi tiết và tối ưu SEO

Khuyến nghị: viết theo từng cụm mục (S0–S2, S3–S4, S5–CTA...) thay vì cả bài một lần, để giảm nguy cơ đạt giới hạn token.

# VAI TRÒ
Bạn là chuyên gia viết nội dung PR công nghệ, giọng chuyên nghiệp, tin cậy.

# NHIỆM VỤ
Viết bài PR hoàn chỉnh bám sát <OUTLINE>. Hãy suy nghĩ từng bước: với mỗi mục,
kiểm tra mã PP và từ khóa được giao rồi mới viết.

[DÁN <BRIEF> VÀO ĐÂY]
[DÁN NGUYÊN VĂN <PERSONA_PAINPOINTS> VÀO ĐÂY]
[DÁN NGUYÊN VĂN <OUTLINE> VÀO ĐÂY]

# QUY TẮC NỘI DUNG
1. Viết theo đúng thứ tự mã S0 → Sn. Không thêm, bớt, đổi thứ tự mục.
2. Mỗi mục đạt số từ ±10% so với dàn ý.
3. Lead nêu ngay pain point (PP1, PP2) bằng tình huống cụ thể, không mở bằng câu sáo rỗng.
4. Chỉ dùng số liệu có trong BRIEF. Không bịa số liệu, không dùng "tốt nhất", "số 1" khi chưa có căn cứ.
5. Không lặp ý giữa các mục. Mỗi đoạn mang một thông tin mới.
6. Giọng điệu, ngôi xưng, thuật ngữ theo đúng "Quy chuẩn viết" trong OUTLINE.

# QUY TẮC SEO
1. Từ khóa chính: có trong Headline, 100 từ đầu và CTA. Mật độ khoảng 1–1,5%, không nhồi nhét.
2. Từ khóa phụ: đặt tự nhiên trong H2/H3 và đoạn đầu mỗi mục tương ứng.
3. Headline ≤ 60 ký tự. Thêm Meta description 140–155 ký tự ở cuối bài.
4. Đoạn văn ≤ 4 câu, dễ đọc.

# QUY TẮC ĐỊNH DẠNG
- Dùng Markdown: # cho Headline, ## cho H2, ### cho H3.
- Cuối mỗi mục, ghi dấu hiệu theo đúng mẫu: [[HẾT S2]] (đổi mã theo mục vừa viết).
- Cuối toàn bộ bài, ghi: [[HOÀN TẤT]].
- Nếu phải dừng giữa chừng, không tự tóm tắt hay kết bài vội. Cứ dừng, người dùng sẽ ra lệnh viết tiếp.

# ĐỊNH DẠNG ĐẦU RA
Chỉ xuất bài viết theo thứ tự, không giải thích thêm.
6. Quy tắc xử lý khi bài bị ngắt quãng (đạt max token)
6.1 Nhận biết đứt gãy

Bài bị cắt nếu: (a) kết thúc giữa câu hoặc giữa đoạn, hoặc (b) không có dấu [[HẾT Sx]] hay [[HOÀN TẤT]] ở cuối.

6.2 Câu lệnh tiếp tục chuẩn (Trường hợp A: đứt giữa câu/đoạn)
Bài viết bị ngắt giữa chừng. Hãy viết tiếp CHÍNH XÁC từ điểm dừng sau đây.

Đoạn cuối đã viết (không lặp lại, chỉ dùng để nối):
"""
[DÁN 2–3 CÂU CUỐI CÙNG AI ĐÃ VIẾT, KỂ CẢ CÂU DANG DỞ]
"""

Mục đang viết dở: [mã S, VD: S3 – tiêu đề]

YÊU CẦU:
1. Bắt đầu ngay bằng phần còn thiếu của câu dang dở. Không chào, không lời dẫn,
   không tóm tắt phần trước, không nhắc lại câu đã có.
2. Nếu câu cuối đã hoàn chỉnh, viết tiếp bằng câu kế tiếp trong mạch ý.
3. Giữ nguyên giọng điệu, ngôi xưng, 7huật ngữ theo <OUTLINE>.
4. Hoàn thành mục hiện tại theo đúng dàn ý rồi viết tiếp các mục còn lại.
5. Giữ nguyên quy tắc SEO, định dạng Markdown và dấu [[HẾT Sx]].

## 7. Danh sách kiểm tra cuối (trước khi xuất bản)

| Hạng mục | Đạt khi |
|:---|:---|
| Cấu trúc | Có Headline, Lead, H2/H3 đúng dàn ý, CTA cuối bài |
| Pain points | Mọi PP trong Prompt 1 đều xuất hiện trong bài |
| Giọng điệu | Đồng nhất từ Lead đến CTA, không chỗ nào quảng cáo thái quá |
| Số liệu | Chỉ dùng số liệu có trong BRIEF hoặc đã xác minh |
| SEO | Từ khóa chính ở Headline, Lead, CTA. Có meta description |
| Độ dài | 1.000–1.500 từ |
| Chỗ nối | Không lặp câu, không đứt mạch ở các điểm ngắt |
