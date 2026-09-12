# 01 — Individual Problem Scan

> Điền theo Phase 1 + Phase 2 trong `01-worksheet.md`. Tự scan trước, dùng AI sau để phản biện. Không copy ví dụ Weekly Report.

## Thông tin cá nhân

- Họ và tên: Nguyễn Quang Tuấn
- Mã học viên: 2A202602470
- Vai trò / bối cảnh : sinh viên ra trường, làm AI software engineer, vai trò researcher
- Công việc hằng tuần (3-5 gạch đầu dòng để soi problem):
  - Tìm hiểu và survey kiến thức mới (paper, tài liệu kỹ thuật, case study).
  - Đọc và kiểm chứng số liệu/nguồn trước khi đưa vào báo cáo hoặc đề xuất kỹ thuật.
  - Tổng hợp thông tin từ nhiều nguồn rời rạc (PDF, docs, web) thành báo cáo/kết luận có truy vết nguồn.
  - Trao đổi trong nhóm để chốt số liệu, giả định, và bảo vệ kết luận trước phản biện.

---

## Phase 1 — Scan 5+ problems (tối thiểu 5, khuyến khích 8-10)

**Cách điền:** mỗi dòng = việc gì + ai chịu + đo bằng gì. Cột `Dấu hiệu thật` bắt buộc có số: mất bao lâu (bấm giờ mấy lần), mấy lần/tuần, bao nhiêu người gặp, log/ticket/quote nào.

| # | Lăng kính (Lặp lại / Tốn thời gian / AI có thể tốt hơn / Pain từ người khác) | Problem quan sát được | Ai chịu ảnh hưởng? | Dấu hiệu thật (số + bằng chứng) |
|---|---|---|---|---|
| 1 | AI có thể tốt hơn / Tốn thời gian | Đọc và phân tích báo cáo tài chính (BCTC) hợp nhất đã kiểm toán của doanh nghiệp Việt Nam để trích số liệu, tính chỉ số tài chính và nhận diện cảnh báo, hiện phải làm thủ công từng file PDF dài 80-150 trang. | Researcher/sinh viên phân tích tài chính, intern phòng phân tích đầu tư, người tự học đầu tư chứng khoán. | Mỗi BCTC 1 năm mất khoảng 2-3 giờ để trích số + tính 5 nhóm chỉ số thủ công; nếu so sánh 3-5 năm thì mất 6-10 giờ; sai sót thường gặp ở bước dò lại số liệu giữa các trang thuyết minh. |
| 2 | Lặp lại / Tốn thời gian | Tìm lại nguồn/số liệu đã trích dẫn trước đó khi viết báo cáo/tài liệu kỹ thuật — không nhớ số liệu lấy từ đâu, phải mở lại file gốc để dò. | Researcher, thành viên nhóm viết báo cáo chung. | Trung bình mất 5-10 phút/lần tìm lại nguồn, xảy ra khoảng 5-8 lần mỗi báo cáo; nhiều lần số liệu bị trích sai do nhớ nhầm nguồn. |
| 3 | Pain từ người khác | Thành viên nhóm hay hỏi lại "số này lấy từ đâu, tính thế nào" khi review báo cáo/tài liệu chung, vì báo cáo không ghi rõ công thức và nguồn trích. | Cả nhóm khi review chéo báo cáo trước khi nộp. | Trong 3 buổi review gần nhất, câu hỏi "nguồn ở đâu" xuất hiện trung bình 4-6 lần/buổi; mỗi lần giải thích lại mất 3-5 phút. |
| 4 | Tốn thời gian / AI có thể tốt hơn | So sánh nhiều nguồn/tài liệu tham khảo (paper, bài báo, case study) khi survey kiến thức mới cho báo cáo/đề xuất kỹ thuật — phải đọc dàn trải nhiều tab, tự ghi chú điểm giống/khác. | Researcher trong nhóm, đặc biệt ở giai đoạn Phase 4 (Validation + Research) của lab. | Với 3-5 nguồn, việc đọc + tổng hợp bảng so sánh mất khoảng 45-60 phút; dễ bỏ sót vì không có checklist cố định cho từng nguồn. |
| 5 | Lặp lại / Tốn thời gian | Định dạng lại báo cáo (Word/Docx) theo đúng template trước khi nộp/trình bày — canh bảng, mục lục, số thứ tự, format số liệu — làm thủ công mỗi lần chỉnh nội dung. | Researcher/writer chịu trách nhiệm bản nộp cuối. | Mỗi lần chỉnh nội dung phải format lại mất 10-15 phút; với báo cáo chỉnh sửa 3-4 lần trước khi chốt, tổng mất 30-60 phút chỉ riêng cho format. |

> Gợi ý tự soi: tuần trước mất nhiều thời gian nhất vào việc gì? Việc gì hay trì hoãn? Người khác hay hỏi lại câu gì? Workflow nào ai cũng biết là chậm?

**AI đã dùng ở Phase 1 (nếu có):**
- Prompt đã hỏi: "Tôi là researcher trong nhóm, công việc gồm đọc tài liệu, kiểm chứng số liệu, tổng hợp báo cáo. Gợi ý thêm problem theo 4 lăng kính: lặp lại, tốn thời gian, AI có thể tốt hơn, pain từ người khác."
- Ý dùng được: gợi ý về việc trích dẫn/truy vết nguồn số liệu và việc format báo cáo lặp lại — đã đưa vào bảng scan (#2, #3, #5).
- Ý bỏ vì không phải pain thật: AI gợi ý "xây trợ lý AI tổng hợp tin tức tài chính real-time" — quá rộng, không có trải nghiệm thật, không đo được impact cụ thể trong phạm vi lab.

**Self-check Phase 1:**
- [x] Đủ 5+ dòng, mỗi dòng có actor + số đo cụ thể
- [x] Dùng ít nhất 3/4 lăng kính
- [x] Không có dòng chung chung kiểu "mất nhiều thời gian"

---

## Phase 2 — Top 3 Problem Cards

### 2.1. Chọn top 3

Giữ bài nào: actor cụ thể, workflow vẽ được 3-7 bước, bottleneck ở 1 bước, impact đo được. Loại bài quá rộng.

| Rank | Problem (copy từ bảng scan) | Vì sao chọn (2-3 ý) | Điều còn chưa chắc |
|---|---|---|---|
| 1 | Phân tích báo cáo tài chính (BCTC) doanh nghiệp Việt Nam từ PDF | Actor rõ (researcher/sinh viên phân tích tài chính), workflow trích số liệu → tính chỉ số → nhận diện cảnh báo rất rõ ràng và lặp lại theo mẫu VAS; impact đo được bằng giờ tiết kiệm; đúng chuyên môn của vai trò researcher trong nhóm. | Chưa chắc độ chính xác trích xuất số liệu từ PDF (đặc biệt bảng scan/ảnh) có đạt yêu cầu kiểm toán không; chưa rõ cần review bằng tay bao nhiêu % kết quả. |
| 2 | Tìm lại nguồn/số liệu đã trích dẫn khi viết báo cáo nhóm | Xảy ra lặp lại nhiều lần mỗi báo cáo, ai trong nhóm cũng gặp, dễ đo bằng số phút mỗi lần tìm lại. | Chưa chắc nguyên nhân gốc là thiếu công cụ hay thiếu thói quen ghi chú nguồn ngay từ đầu — cần hỏi thêm để không nhầm sang vấn đề quy trình. |
| 3 | So sánh nhiều nguồn tham khảo khi survey kiến thức mới | Bottleneck rõ ở bước đọc + tổng hợp bảng so sánh; đây đúng là công việc chính của researcher nên có nhiều trải nghiệm thật để mô tả. | Chưa chắc AI tổng hợp có giữ được sắc thái/nhận định đúng của từng nguồn hay chỉ tóm tắt hời hợt — cần kiểm tra bằng tay. |

### 2.2. Problem Cards chi tiết (lặp lại cho cả 3 cards)

---

#### Problem Card #1 — Phân tích BCTC doanh nghiệp Việt Nam từ PDF

```text
Problem 1 câu:
Researcher/sinh viên phân tích tài chính mất 2-3 giờ mỗi BCTC để trích số liệu, tính 5 nhóm chỉ số tài chính và kiểm tra tính đúng đắn số học một cách thủ công.

Actor:
Researcher/sinh viên phân tích tài chính, intern phòng phân tích đầu tư/kế toán.

Thời điểm / bối cảnh:
Khi cần phân tích BCTC hợp nhất đã kiểm toán (2-5 năm) của một doanh nghiệp niêm yết (VD: MWG, FRT, DGW, PNJ, HPG) để làm báo cáo, bài tập hoặc hỗ trợ ra quyết định đầu tư.

Current workflow 3-7 bước:
1. Tải file PDF BCTC hợp nhất kiểm toán (2-5 năm) từ website công ty/HOSE/HNX.
2. Đọc và trích thủ công số liệu từ Bảng cân đối kế toán, KQKD, Lưu chuyển tiền tệ, Thuyết minh — ghi chú lại trang nguồn.
3. Kiểm tra chéo tính đúng đắn số học (tổng tài sản = tổng nguồn vốn, các dòng cộng dồn khớp).
4. Tính thủ công 5 nhóm chỉ số: thanh khoản, đòn bẩy, hiệu quả, sinh lời, dòng tiền — qua nhiều năm.
5. Phân tích xu hướng qua các năm, tự nhận diện các điểm bất thường/cảnh báo.
6. Soạn báo cáo tổng hợp, định dạng lại theo template Word.
7. Gửi chuyên viên/giảng viên kiểm tra và ký duyệt.

Bottleneck:
Bước 2 + 4 (trích số liệu có truy vết nguồn + tính 5 nhóm chỉ số qua nhiều năm) — khoảng 90-120 phút/lần, dễ sai sót khi dò số liệu giữa nhiều trang thuyết minh.

Impact:
Tốn 2-3 giờ/BCTC, nhân với việc phải phân tích nhiều mã và nhiều năm để so sánh thì tổng thời gian tăng tuyến tính; rủi ro sai số liệu ảnh hưởng trực tiếp đến chất lượng kết luận và uy tín báo cáo.

Success metric:
Giảm thời gian trích số liệu + tính chỉ số từ ~2-3 giờ xuống dưới 30-45 phút/BCTC (bao gồm thời gian chuyên viên review), đo bằng bấm giờ từ lúc có file PDF đến lúc có bảng chỉ số đã kiểm tra xong; tỷ lệ số liệu sai lệch giữa bản AI trích và bản đối chiếu tay dưới 2%.

Non-AI alternative:
Dùng template Excel có công thức tính sẵn 5 nhóm chỉ số, nhập tay số liệu theo checklist cố định các dòng cần lấy.

AI hypothesis:
AI (workflow trích xuất PDF có cấu trúc + tính toán + đối chiếu) có thể tự động trích số liệu có ghi rõ nguồn (trang/mục), tự tính chỉ số và tự đánh dấu điểm bất thường, nhưng vẫn cần chuyên viên kiểm tra số liệu trích xuất trước khi ký duyệt do rủi ro đọc sai bảng/đơn vị tính (nghìn đồng, triệu đồng, tỷ đồng) trong PDF.

Quick gut:
[ ] No AI / process fix
[x] Workflow
[ ] Rule
[ ] Agent
[ ] Chưa biết
```

**Draft workflow Card #1** (ASCII / Mermaid / ảnh đính kèm):

```text
CURRENT STATE — 150 phút

[1 Tải PDF BCTC: 5'] → [2 Trích số liệu thủ công: 60'] → [3 Kiểm tra số học: 15'] → [4 Tính 5 nhóm chỉ số: 40']  <-- bottleneck
→ [5 Phân tích xu hướng: 20'] → [6 Format báo cáo: 10']

FUTURE STATE — 40 phút

[1 Tải PDF: 5'] → [2 AI trích số liệu có truy vết nguồn: 5'] → [3 AI kiểm tra số học + tính chỉ số + cảnh báo: 5']
→ [4 Chuyên viên review số liệu + kết luận, ký duyệt: 20']  <-- human boundary
→ [5 Xuất báo cáo .docx: 5']

Fallback: nếu AI trích sai số liệu hoặc đơn vị tính (VD nhầm nghìn đồng/triệu đồng) → chuyên viên đối chiếu lại bằng tay với PDF gốc trước khi ký duyệt.
```

File đính kèm (nếu vẽ riêng): `01-individual-problem-scan-workflow-card-1.png`

---

#### Problem Card #2 — Tìm lại nguồn/số liệu đã trích dẫn khi viết báo cáo nhóm

```text
Problem 1 câu:
Researcher trong nhóm mất 5-10 phút mỗi lần phải mở lại file gốc để tìm lại số liệu/nguồn đã trích dẫn trước đó khi viết hoặc review báo cáo chung.

Actor:
Researcher và các thành viên nhóm cùng viết/review báo cáo chung.

Thời điểm / bối cảnh:
Trong quá trình viết báo cáo nhóm nhiều vòng chỉnh sửa, khi một thành viên khác hỏi "số này lấy ở đâu" hoặc khi tự mình cần dẫn lại nguồn cho phần mới viết.

Current workflow 3-7 bước:
1. Đọc lại đoạn báo cáo có số liệu cần kiểm tra nguồn.
2. Nhớ lại (hoặc đoán) file/tài liệu đã lấy số liệu đó.
3. Mở lại nhiều file để tìm đúng vị trí.
4. Dò tìm bằng Ctrl+F hoặc đọc lướt để xác nhận số liệu khớp.
5. Copy lại nguồn/trích dẫn vào báo cáo.

Bottleneck:
Bước 2 + 3 (nhớ lại và mở lại nhiều file để tìm) — vì lúc trích số liệu ban đầu không ghi chú nguồn ngay.

Impact:
5-10 phút/lần, khoảng 5-8 lần mỗi báo cáo nhóm; cộng dồn có thể mất 40-60 phút riêng cho việc tìm lại nguồn trong một báo cáo.

Success metric:
Giảm thời gian tìm lại nguồn xuống dưới 1 phút/lần bằng cách bắt buộc ghi nguồn ngay khi trích số liệu; đo bằng số lần phải hỏi lại "nguồn ở đâu" trong buổi review giảm từ 4-6 lần xuống 0-1 lần.

Non-AI alternative:
Quy ước ghi chú (file, trang, ngày lấy) ngay cạnh mỗi số liệu trong bản nháp — quy tắc làm việc, không cần công cụ AI.

AI hypothesis:
Đây là vấn đề quy trình/kỷ luật ghi chú nhiều hơn là vấn đề cần AI giải quyết.

Quick gut:
[x] No AI / process fix
[ ] Rule
[ ] Workflow
[ ] Agent
[ ] Chưa biết
```

**Draft workflow Card #2:**

```text
CURRENT STATE — 8 phút/lần

[1 Nhớ lại nguồn: 2'] → [2 Mở lại file: 3'] → [3 Dò tìm số liệu: 3']  <-- bottleneck

FUTURE STATE — 1 phút/lần

[1 Ghi nguồn ngay lúc trích: 0'] → [2 Tra lại trong bảng ghi chú: 1']  <-- human boundary (tự kỷ luật, không phải AI)

Fallback: nếu vẫn quên ghi nguồn → quay lại cách cũ, chấp nhận mất thời gian tìm lại.
```

File đính kèm: `01-individual-problem-scan-workflow-card-2.png`

---

#### Problem Card #3 — So sánh nhiều nguồn tham khảo khi survey kiến thức mới

```text
Problem 1 câu:
Researcher mất 45-60 phút để đọc và tự tổng hợp bảng so sánh 3-5 nguồn tham khảo (paper, case study, tài liệu) khi survey kiến thức mới cho báo cáo/đề xuất kỹ thuật.

Actor:
Researcher trong nhóm, đặc biệt ở Phase 4 (Validation + Research) của lab hoặc khi làm báo cáo/đề xuất kỹ thuật.

Thời điểm / bối cảnh:
Khi cần tìm hiểu xem đã có giải pháp/case study nào tương tự với bài toán nhóm đang phân tích, để tránh nghĩ trong chân không.

Current workflow 3-7 bước:
1. Tìm kiếm nguồn liên quan (Google, paper, tài liệu chính thức).
2. Mở từng nguồn, đọc lướt để xác định có liên quan không.
3. Đọc kỹ các nguồn liên quan, ghi chú thủ công.
4. Tự dựng bảng so sánh (điểm mạnh, khoảng trống, bài học).
5. Viết nhận xét tổng hợp cho nhóm.

Bottleneck:
Bước 3 + 4 (đọc kỹ và tự dựng bảng so sánh) — không có checklist cố định nên dễ tổng hợp thiếu nhất quán giữa các nguồn.

Impact:
45-60 phút cho 3-5 nguồn; nếu thiếu nhất quán, nhóm phải họp lại để làm rõ, tốn thêm 15-20 phút.

Success metric:
Giảm thời gian tổng hợp bảng so sánh xuống 20-25 phút cho 3-5 nguồn (đo bằng bấm giờ), với tiêu chí bảng so sánh đủ 4 cột (điểm mạnh, khoảng trống, bài học, link nguồn) không bị bỏ sót.

Non-AI alternative:
Dùng một template bảng so sánh cố định (điểm mạnh / khoảng trống / bài học / link) và tự điền tay theo checklist.

AI hypothesis:
AI có thể hỗ trợ đọc nhanh và điền nháp bảng so sánh theo template cố định, nhưng researcher vẫn phải tự đọc nguồn gốc để xác nhận nhận định đúng, tránh AI tóm tắt hời hợt hoặc bỏ sót sắc thái quan trọng.

Quick gut:
[ ] No AI / process fix
[ ] Rule
[x] Workflow
[ ] Agent
[ ] Chưa biết
```

**Draft workflow Card #3:**

```text
CURRENT STATE — 60 phút

[1 Tìm nguồn: 10'] → [2 Đọc lướt lọc nguồn: 10'] → [3 Đọc kỹ + ghi chú: 25']  <-- bottleneck → [4 Dựng bảng so sánh: 15']

FUTURE STATE — 25 phút

[1 Tìm nguồn: 10'] → [2 AI tóm tắt nháp theo template cố định: 5'] → [3 Researcher đọc gốc để xác nhận + sửa bảng: 10']  <-- human boundary

Fallback: nếu AI tóm tắt sai/bỏ sót ý quan trọng → researcher tự đọc lại toàn bộ nguồn đó như cách cũ.
```

File đính kèm: `01-individual-problem-scan-workflow-card-3.png`

---

### 2.3. Card muốn pitch nhất (chuẩn bị 2 phút)

**Card tôi muốn pitch nhất:**

```text
Card #1 — Phân tích BCTC doanh nghiệp Việt Nam từ PDF (phan-tich-bctc)
```

**Vì sao (2-3 câu: workflow gì, số đo gì, impact gì):**

```text
Workflow rất rõ ràng và lặp lại theo đúng chuẩn VAS: trích số liệu có truy vết nguồn → kiểm tra tính đúng đắn số học → tính 5 nhóm chỉ số → phân tích xu hướng → xuất báo cáo .docx chờ ký duyệt. Hiện mỗi BCTC tốn 2-3 giờ làm thủ công và dễ sai khi dò số liệu qua nhiều trang thuyết minh; nếu AI hỗ trợ đúng các bước trích xuất và tính toán, có thể giảm còn 30-45 phút bao gồm cả thời gian chuyên viên kiểm tra lại.
```

**Câu hỏi tôi muốn nhóm challenge (1-2 câu hỏi đúng chỗ yếu):**

```text
1. Nếu AI đọc sai đơn vị tính (nghìn đồng/triệu đồng/tỷ đồng) hoặc trích nhầm số liệu từ PDF dạng ảnh/scan, ai là người phát hiện đầu tiên và quy trình kiểm tra chéo sẽ tốn thêm bao nhiêu thời gian so với mức tiết kiệm kỳ vọng?
2. Bài toán này có thật sự cần đến Agent (tự quyết định bước tiếp theo) hay một Workflow cố định (trích → tính → cảnh báo → người kiểm tra) đã đủ, vì các bước gần như luôn đi theo một trình tự cố định?
```

**AI phản biện Card (nếu có):**
- Điểm yếu AI chỉ ra: Rủi ro lớn nhất nằm ở độ tin cậy của bước trích xuất số liệu từ PDF (đặc biệt bảng phức tạp hoặc file scan chất lượng thấp) — nếu sai ở đây thì toàn bộ chỉ số phía sau đều sai theo, nên "human review" không thể chỉ là bước hình thức cuối cùng mà cần review ngay sau bước trích xuất.
- Tôi sửa gì: Thêm bước "chuyên viên kiểm tra số liệu trích xuất" ngay sau bước AI trích xuất (trước khi tính chỉ số), thay vì chỉ review ở bước cuối trước khi ký duyệt — đã cập nhật vào future workflow Card #1.

### Self-check nộp phần 01
- [x] Có 5+ problems + top 3 Cards đủ field
- [x] Mỗi Card có workflow trước/sau + bottleneck + metric + fallback
- [x] Đã chọn 1 card pitch + câu hỏi challenge
