# BỘ PROMPT CLAUDE DESIGN — LANDING PAGE IELTS SMART

> **Nguyên tắc bản quyền:** Selfomy.com được dùng làm tham chiếu *cấu trúc thông tin* và *chủ đề nội dung*. Không có hình ảnh, icon, illustration, screenshot hay token màu nào của Selfomy đi vào bộ prompt này. Phần chữ ở PHỤ LỤC COPY được viết lại hoàn toàn bằng cách diễn đạt riêng của IELTS SMART, đổi cấu trúc câu, đổi ví dụ và đổi thuật ngữ sản phẩm — không sao chép nguyên văn. Màu sắc, thông tin doanh nghiệp và toàn bộ copy khối chính lấy từ ieltssmart.vn và brand guideline IELTS SMART.
>
> **Nguồn nội dung:** ieltssmart.vn (đã đọc đầy đủ) · app.ieltssmart.vn (client-side render sau đăng nhập, chưa đọc được — dùng PROMPT 14 để nạp thủ công) · selfomy.com (tham chiếu, đã paraphrase).

---

## PHẦN A — PHÂN TÍCH WIREFRAME THAM CHIẾU

### A1. Bộ khung 15 khối của một landing page B2B EdTech (rút ra từ Selfomy)

```
┌──────────────────────────────────────────────┐
│ 0  Utility bar: hotline / hỗ trợ kỹ thuật    │
├──────────────────────────────────────────────┤
│ 1  Header sticky: logo · menu · lang · CTA   │
├──────────────────────────────────────────────┤
│ 2  Announcement pill (link bản cập nhật mới) │
├──────────────────────────────────────────────┤
│ 3  HERO   H1 + chip tính năng + 2 CTA        │
│           + microcopy trấn an + ảnh sản phẩm │
├──────────────────────────────────────────────┤
│ 4  Câu chốt giá trị (1 dòng, cỡ lớn)         │
├──────────────────────────────────────────────┤
│ 5  Feature blocks so le trái/phải × 4        │
│    (tag → H2 → bullet → CTA → ảnh)           │
├──────────────────────────────────────────────┤
│ 6  Logo wall khách hàng                      │
├──────────────────────────────────────────────┤
│ 7  Vì sao chọn: 1 đoạn dẫn + 4 lý do ngắn    │
├──────────────────────────────────────────────┤
│ 8  Dải số liệu (3 con số lớn + diễn giải)    │
├──────────────────────────────────────────────┤
│ 9  Báo chí / giải thưởng                     │
├──────────────────────────────────────────────┤
│ 10 Case study (2 card lớn)                   │
├──────────────────────────────────────────────┤
│ 11 Blog / tài nguyên (3 card)                │
├──────────────────────────────────────────────┤
│ 12 FAQ accordion                             │
├──────────────────────────────────────────────┤
│ 13 CTA band cuối                             │
├──────────────────────────────────────────────┤
│ 14 Footer 4 cột + pháp lý + social           │
└──────────────────────────────────────────────┘
   + Floating widget Zalo/hotline góc phải
```

**3 bài học bố cục đáng học nhất:**
1. **CTA lặp đúng nhịp** — cùng một hành động ("Tạo LMS ngay") được nhắc lại ở cuối *mỗi* feature block, không đợi tới cuối trang.
2. **Trấn an ngay dưới nút chính** — "Đăng ký miễn phí, không cần nhập thẻ, không cần gặp sales" là câu gỡ rào cản, đặt sát CTA hero.
3. **Bằng chứng xếp tầng** — logo wall → số liệu → báo chí → case study → FAQ. Mỗi tầng trả lời một nỗi nghi ngờ khác nhau.

### A2. Bảng chuyển đổi sang IELTS SMART

| # | Khối | Nội dung IELTS SMART | Trạng thái |
|---|------|----------------------|-----------|
| 0 | Utility bar | Hotline 037 416 8445 · Zalo | ✅ có |
| 1 | Header | Logo + "for centers", menu 6 mục, VI/EN, CTA "Đặt lịch demo" | ✅ có |
| 2 | Announcement pill | — | 🟨 khung rỗng |
| 3 | Hero | "Luyện tập và thi thử IELTS bằng AI" + mock báo cáo band 7.5 | ✅ có |
| 4 | Vấn đề vs Giải pháp | Bảng so sánh 2 cột (4 dòng mỗi bên) | ✅ có |
| 5 | Quy trình 3 bước | Test đầu vào → Chấm định kỳ → Báo cáo tiến độ | ✅ có |
| 6 | Báo cáo band | Band tổng 8.0 + TA/CC/LR/GRA + word count | ✅ có |
| 7 | Giao diện chấm bài | Highlight lỗi 3 màu + panel gợi ý sửa + duyệt GV | ✅ có |
| 8 | Dashboard năng suất | Bảng 4 giáo viên + tỷ lệ AI 82% / GV 18% | ✅ có |
| 9 | 6 lý do chọn | Grid 6 card | ✅ có |
| 10 | Logo wall trung tâm | — | 🟨 khung rỗng |
| 11 | Số liệu ấn tượng | — | 🟨 khung rỗng |
| 12 | Case study | — | 🟨 khung rỗng |
| 13 | Bảng giá theo quy mô | — | 🟨 khung rỗng |
| 14 | Tài nguyên / Blog | — | 🟨 khung rỗng |
| 15 | FAQ | — | 🟨 khung rỗng |
| 16 | Form đặt lịch demo | Form 6 trường đầy đủ validation | ✅ có |
| 17 | Footer | NOVAFORGE, GPKD, địa chỉ, 7 link chính sách | ✅ có |

---

## PHẦN B — CÁCH DÙNG BỘ PROMPT

1. Dán **PROMPT 1** vào Claude Design → nhận bản đầy đủ.
2. Dùng **PROMPT 2 → 10** để tinh chỉnh từng khối khi chưa ưng.
3. Dùng **PROMPT 11 → 13** cho responsive, song ngữ, và QA cuối.
4. Mỗi lần sửa nội dung sau này: chỉ cần bảo Claude Design *"sửa trong khối CONTENT"* — vì Prompt 1 đã bắt buộc tách toàn bộ chữ ra một nơi.

---

## PROMPT 1 — MASTER PROMPT (dán nguyên khối)

```
Bạn là design lead. Hãy dựng cho tôi một landing page B2B hoàn chỉnh, một trang,
tiếng Việt, cho sản phẩm IELTS SMART (ieltssmart.vn) — nền tảng chấm IELTS bằng AI
bán cho trung tâm tiếng Anh tại Việt Nam. Chủ sở hữu: Công ty Cổ phần Công nghệ NOVAFORGE.

=== ĐỐI TƯỢNG & MỤC TIÊU ===
Người xem: chủ trung tâm Anh ngữ và học thuật trưởng, quy mô 20–500 học viên.
Nỗi đau: giáo viên mất 15–25 phút/bài Writing, điểm không nhất quán giữa các lớp,
muốn mở rộng là phải tuyển thêm giám khảo.
Mục tiêu duy nhất của trang: điền form "Đặt lịch demo".
Giọng văn: chuyên nghiệp, đi thẳng vào con số vận hành, không hype, không dùng
từ ngữ marketing rỗng. Câu ngắn, động từ chủ động.

=== HỆ THỐNG THIẾT KẾ (BẮT BUỘC ĐÚNG) ===
Màu — khai báo dưới dạng CSS custom properties trong :root:
  --navy:      #0E2149   /* nền tối, chữ heading */
  --indigo:    #1D1B7F   /* màu thương hiệu chính, nút primary */
  --sky:       #4BC4F9   /* nhấn, gradient, biểu đồ */
  --teal:      #00B89C   /* trạng thái tốt, tăng trưởng, tick */
  --white:     #FFFFFF
  --gray-soft: #F9FAFB   /* nền section xen kẽ */
Chỉ dùng 5 màu này + các sắc độ pha loãng của chúng. Không thêm màu mới.
Đỏ/cam chỉ được dùng cho highlight lỗi ngữ pháp trong mock giao diện chấm bài.

Chữ:
  Heading — Poppins (Bold / SemiBold / Medium). Geometric, tự tin, thân thiện.
  Thân bài & UI — Inter (Regular / Medium / SemiBold).
  Thang cỡ chữ rõ ràng: h1 56/1.05, h2 40/1.15, h3 24/1.3, body 17/1.65, caption 14/1.5.
  Desktop giữ độ dài dòng dưới 75 ký tự.

Hình khối & bề mặt:
  Bo góc mềm: card 20px, nút 12px, chip 999px.
  Bóng đổ nhẹ, khuếch tán rộng: 0 12px 32px rgba(14,33,73,.08). Không dùng bóng cứng.
  Đường viền hairline 1px rgba(14,33,73,.08) cho card trên nền trắng.
  Icon: nét mảnh (stroke 1.75), bo đầu tròn, đặt trong ô vuông bo góc nền màu pha loãng 8%.

Không dùng: nền kem, chữ serif display, accent terracotta, eyebrow chữ hoa
tracking rộng trên MỌI heading, mũi tên "→" gắn đuôi mọi link, hiệu ứng
fade-up rải đều mọi section. Chọn đúng MỘT khoảnh khắc chuyển động đáng nhớ
(gợi ý: hero — thanh band score chạy từ 0 lên đúng điểm khi trang tải).

=== YÊU CẦU TỐI QUAN TRỌNG VỀ KHẢ NĂNG TÙY CHỈNH ===
Đây là điều kiện bắt buộc, không được bỏ qua:

1. Tách toàn bộ chữ ra một object `CONTENT` duy nhất đặt ở đầu file, cấu trúc lồng
   theo tên section (CONTENT.hero.h1, CONTENT.pricing.tiers[0].name...).
   Trong phần render KHÔNG được hardcode bất kỳ chuỗi tiếng Việt nào.

2. Toàn bộ hình ảnh gom vào object `MEDIA` riêng, mỗi ảnh là một khoá có dạng:
     { src: "", alt: "", ratio: "16/9", note: "Mô tả ảnh cần thay" }
   Khi src rỗng → render một placeholder có viền đứt nét, hiển thị đúng tên khoá,
   tỉ lệ khung và dòng note ở giữa, nền --gray-soft. Đặt tên khoá dễ đọc:
   MEDIA.heroProductShot, MEDIA.logoWall[0..7], MEDIA.caseStudy1Cover,
   MEDIA.pressLogos[0..4], MEDIA.blogCover1...
   Nhờ vậy tôi chỉ cần dán URL vào là ảnh hiện ra, không phải sửa layout.

3. Mỗi section là một component/khối độc lập, đặt tên rõ ràng, xếp theo đúng thứ tự
   liệt kê bên dưới, để tôi có thể xoá hoặc đảo vị trí mà không vỡ trang.

4. Các section chưa có nội dung thật (đánh dấu [KHUNG] bên dưới) vẫn phải dựng đủ
   layout, đúng số lượng ô, và điền nội dung mẫu hợp lý làm chỗ giữ. Đánh dấu
   nội dung mẫu bằng cờ `isPlaceholder: true` trong CONTENT để tôi biết chỗ nào cần thay.

5. Mọi khoảng cách dùng thang 4px (4/8/12/16/24/32/48/64/96). Padding dọc section:
   96px desktop, 56px mobile — khai báo qua một biến chung, sửa một chỗ đổi cả trang.

=== NGUỒN NỘI DUNG & QUY TẮC VIẾT COPY ===
Nội dung của trang được lấy từ ba nguồn, theo thứ tự ưu tiên:

Nguồn 1 — ieltssmart.vn (ưu tiên cao nhất): mọi câu đã được trích nguyên văn trong
phần cấu trúc bên dưới. Giữ đúng từng chữ, không viết lại.

Nguồn 2 — app.ieltssmart.vn (sản phẩm thật): dùng để mô tả tính năng cho đúng
với những gì học viên và giáo viên thực sự thấy khi đăng nhập. Sản phẩm phục vụ
HAI vai trò trong cùng một hệ thống — giáo viên/quản lý trung tâm và học viên —
nên phần mô tả tính năng phải nói rõ mỗi vai trò nhận được gì.
Tôi sẽ dán chi tiết màn hình của app ở tin nhắn tiếp theo; chỗ nào chưa có,
hãy để placeholder và gắn isPlaceholder: true, đừng bịa tính năng.

Nguồn 3 — copy tham chiếu từ đối thủ (phần PHỤ LỤC COPY ở cuối prompt này):
đây là các đoạn đã được VIẾT LẠI HOÀN TOÀN cho IELTS SMART. Quy tắc bắt buộc:
  - Dùng chúng như nội dung gợi ý cho các khối chưa có chữ thật.
  - TUYỆT ĐỐI không copy nguyên văn từ bất kỳ website đối thủ nào. Mọi câu phải
    được diễn đạt lại bằng cách nói riêng của IELTS SMART, đổi cấu trúc câu,
    đổi ví dụ, đổi cách sắp xếp ý.
  - Đổi toàn bộ danh từ sản phẩm sang thuật ngữ của IELTS SMART: nói "chấm bài
    Writing & Speaking bằng AI", "báo cáo band", "dashboard năng suất" — không
    dùng khái niệm chung chung của sản phẩm khác như "LMS", "phòng thi ảo",
    "website tự học thương hiệu riêng" trừ khi IELTS SMART thật sự có.
  - IELTS SMART chỉ làm IELTS. Không nhắc TOEIC, SAT, THPT.
  - Không bê nguyên con số của đối thủ. Mọi số liệu chưa xác nhận phải để dạng
    placeholder rõ ràng (ví dụ "[số] trung tâm") và gắn isPlaceholder: true.

Giọng văn chung: nói bằng ngôn ngữ vận hành của chủ trung tâm — giờ chấm bài,
chi phí giám khảo, độ nhất quán điểm, tỷ lệ giữ chân học viên. Câu ngắn, động từ
chủ động, không tính từ rỗng ("tuyệt vời", "vượt trội", "đột phá").

=== CẤU TRÚC TRANG — DỰNG ĐÚNG THỨ TỰ 17 KHỐI ===

[0] UTILITY BAR — dải mỏng trên cùng, nền --navy, chữ trắng 14px:
"Hỗ trợ trung tâm: 037 416 8445 · Zalo phản hồi trong giờ hành chính"

[1] HEADER dính khi cuộn, nền trắng mờ blur khi đã cuộn:
Logo IELTS SMART (MEDIA.logo) + nhãn nhỏ "for centers" cạnh logo.
Menu: Cách hoạt động · Quy trình · Báo cáo band · Năng suất · Bảng giá · Tài nguyên
Chuyển ngữ VI/EN dạng hai chữ cái, VI đang active.
Nút primary "Đặt lịch demo" nền --indigo.

[2] ANNOUNCEMENT PILL [KHUNG] — chip bo tròn nằm giữa, trên H1:
chấm tròn --teal nhấp nháy + "Bản cập nhật tháng 8 · Chấm Speaking đa giọng" + link.

[3] HERO — hai cột 52/48, nền chuyển sắc rất nhẹ từ trắng sang --gray-soft.
Cột trái:
  Eyebrow: "Giải pháp chấm chữa IELTS cho trung tâm"
  H1: "Luyện tập và thi thử IELTS bằng AI"
  Mô tả: "Tiết kiệm 90% thời gian so với chấm thủ công. AI tự động chấm và nhận xét
  chi tiết 4 kỹ năng theo tiêu chí chấm IELTS tiêu chuẩn — trung tâm hoàn toàn có thể
  kiểm tra lại kết quả."
  Hai nút: "Đặt lịch demo ngay" (primary) · "Xem cách hoạt động" (viền)
  Microcopy dưới nút: "Demo 1-1 với đội sản phẩm · Không cần cài đặt · Miễn phí"
Cột phải — KHÔNG dùng ảnh chụp màn hình, hãy DỰNG BẰNG UI THẬT một card nổi
"IELTS SMART · Chấm Writing Task 2" với:
  - nhãn trạng thái "Đã chấm" màu --teal
  - đoạn bài viết học viên, trong đó 3 cụm được highlight nền màu khác nhau:
    "more easier", "a lot of", "attended"
  - ba chip lọc: Ngữ pháp · Từ vựng · Liên kết
  - khối band: số 7.5 rất lớn, nhãn "Overall band · Good user",
    bốn ô nhỏ L 8.0 / R 7.5 / W 7.0 / S 7.5
  - dòng cuối: avatar tròn chữ "MT" + "Giáo viên đã duyệt · giữ điểm 7.5" + nhãn "Đã duyệt"
Một badge nhỏ nổi lệch ra ngoài card: "90% thời gian tiết kiệm so với chấm thủ công".

[4] VẤN ĐỀ ↔ GIẢI PHÁP — hai cột đối xứng.
Eyebrow "Vấn đề". H2: "Quản lý chất lượng dạy IELTS đang tốn quá nhiều thời gian thủ công"
Dẫn: "Việc vận hành lớp học và chấm điểm bài tập IELTS Writing/Speaking truyền thống
đang kìm hãm sự tăng trưởng của các trung tâm."
Cột trái "Giáo viên chấm truyền thống" — nền xám nhạt, dấu gạch ngang xám:
  · 15–25 phút cho mỗi bài Writing — giáo viên quá tải vào mùa cao điểm.
  · Phụ thuộc hoàn toàn vào giáo viên chấm.
  · Muốn mở rộng quy mô là phải tuyển thêm giám khảo — chi phí cố định tăng.
  · Không có dữ liệu tập trung về năng suất hay tiến bộ học viên.
Cột phải "Với IELTS SMART" — nền trắng, viền --indigo mảnh, tick --teal:
  · AI chấm trước, trả band & nhận xét trong vài phút.
  · Thang điểm chuẩn hoá & nhất quán trên toàn trung tâm.
  · Tăng năng lực chấm không cần tuyển thêm giám khảo.
  · Giáo viên chỉ duyệt & chỉnh — vẫn giữ quyền quyết định cuối.

[5] QUY TRÌNH 3 BƯỚC — đây thực sự là chuỗi tuần tự nên ĐƯỢC dùng số thứ tự.
H2: "Vận hành lớp học IELTS thông minh"
Dẫn: "Hệ thống AI IELTS SMART thay đổi hoàn toàn cách thức vận hành dạy và học
chỉ với 3 bước tinh gọn."
01 Test đầu vào / xếp lớp · 02 Chấm bài định kỳ · 03 Báo cáo tiến độ
Nối 3 bước bằng một đường mảnh có nhịp, mỗi bước một icon và 1 câu mô tả ngắn
(tự viết cho hợp, đánh dấu isPlaceholder).

[6] BÁO CÁO BAND — bố cục 40/60, chữ trái, UI phải.
Eyebrow "Báo cáo band score"
H2: "Band tổng & breakdown 4 tiêu chí, trình bày như báo cáo chuyên nghiệp"
Mô tả: "Mỗi bài có band tổng, điểm từng tiêu chí, đếm số từ, danh sách lỗi và bản sửa
— sẵn sàng gửi cho học viên và phụ huynh."
UI phải dựng thật, gồm: "8.0 Band tổng", nhãn "IELTS Writing · Task 1",
bốn dòng thanh tiến trình TA_TR 8.0 / CC 8.0 / LR 8.0 / GRA 7.0,
dòng "Số từ: 191 / 150 từ yêu cầu", nhãn "Tier A", tab "Lỗi 6 | Bài sửa",
và một ô nhận xét: "Trả lời đầy đủ các phần của đề, ý chính rõ ràng và có dẫn chứng.
Có thể phát triển ý phụ sâu hơn để chạm band 8.5."

[7] GIAO DIỆN CHẤM BÀI — bố cục ngược lại: UI trái rộng, chữ phải.
Eyebrow "Giao diện chấm bài"
H2: "Lỗi được highlight theo màu, kèm gợi ý sửa"
Mô tả: "Giáo viên thấy ngay loại lỗi ở từng vị trí trong bài, chấp nhận hoặc chỉnh sửa
— quyền quyết định cuối luôn thuộc về giáo viên."
UI: khung "Writing Task 2 — bài của học viên" chứa 3 đoạn văn mẫu với các cụm
highlight: more easier, a lot of, the technology, attended, good thing, have, to meet.
Ba chú giải màu: Ngữ pháp (GR) · Từ vựng (LR) · Liên kết / câu (CC).
Panel gợi ý sửa bên cạnh, 3 thẻ:
  "Ngữ pháp · mạo từ" — the technology → technology
  "So sánh kép" — more easier → easier
  "Từ vựng học thuật" — good thing → advancement
Chân khung: avatar "MT" + "Giáo viên duyệt cuối — Cô Mai Trang đã xác nhận 9/9
nhận xét · giữ điểm 7.5" + nhãn "Đã duyệt".

[8] DASHBOARD NĂNG SUẤT — chữ trái, dashboard phải.
Eyebrow "Dashboard report trực quan"
H2: "Theo dõi năng suất theo lớp, giáo viên & toàn trung tâm"
Mô tả: "Quản lý nhìn được ai đang chấm bao nhiêu, thời gian tiết kiệm và mức độ
nhất quán điểm giữa các lớp — tất cả ở một nơi."
Dashboard: nhãn "Tổng quan trung tâm · Tháng 5", tab Giáo viên | Lớp | Trung tâm | Học viên
Bảng 4 cột (Giáo viên · Bài chấm · Giờ tiết kiệm · Nhất quán):
  MT Mai Trang 1,284 · 214h · 98%
  HL Hữu Lộc 1,021 · 170h · 96%
  PA Phương Anh 948 · 158h · 97%
  KD Khánh Duy 812 · 135h · 95%
Dưới bảng: "Phân bổ thời gian chấm" — thanh ngang chia đôi
AI chấm tự động 82% (--indigo) / Giáo viên duyệt 18% (--sky).

[9] SÁU LÝ DO — grid 3×2.
Eyebrow "Vì sao trung tâm chọn IELTS SMART"
H2: "Công cụ vận hành, quản lý trung tâm và kiểm soát toàn diện"
  · Chấm nhanh ở quy mô lớp — Tải hàng loạt bài Writing & Speaking, nhận band và
    nhận xét đồng loạt trong vài phút.
  · Chuẩn hoá & nhất quán — AI được huấn luyện theo khung CEFR & Cambridge.
    Phân tích chi tiết từng tiêu chí Speaking & Writing.
  · Mở rộng không tăng nhân sự — Nhận thêm học viên mà không phải tuyển thêm
    giám khảo — chi phí biên giảm rõ rệt.
  · Giáo viên giữ quyền cuối — Mọi điểm AI đề xuất đều qua bước giáo viên duyệt & chỉnh.
  · Dữ liệu tập trung — Năng suất theo giáo viên, lớp, trung tâm và tiến bộ học viên
    trong một dashboard.
  · Riêng tư & an toàn — Dữ liệu bài làm của trung tâm được bảo mật, phân quyền
    theo vai trò rõ ràng.

[10] LOGO WALL [KHUNG] — "Các trung tâm đang vận hành cùng IELTS SMART"
8 ô logo xám nhạt bo góc, dùng MEDIA.logoWall[0..7], mỗi ô là placeholder có nhãn
"Logo trung tâm 01"… Trên mobile cho trượt ngang.

[11] SỐ LIỆU [KHUNG] — dải nền --navy, chữ trắng, 3 con số lớn font Poppins Bold,
mỗi số kèm 1 dòng diễn giải. Điền số mẫu và đánh dấu isPlaceholder.

[12] CASE STUDY [KHUNG] — 2 card lớn: ảnh bìa (MEDIA.caseStudy1Cover / 2Cover),
nhãn loại hình + thành phố, tiêu đề, 2 dòng tóm tắt, một chỉ số nổi bật
(vd "tiết kiệm 214 giờ/tháng"), link "Đọc thêm".

[13] BẢNG GIÁ [KHUNG] — 3 cột theo quy mô, khớp đúng 3 mốc trong form:
"Dưới 20 học viên" · "20–50 học viên" · "Trên 50 học viên".
Cột giữa nổi bật (viền --indigo, nhãn "Phổ biến"). Mỗi cột: tên gói, chỗ trống cho
giá VND, 5 dòng tính năng có tick, nút "Nhận báo giá". Ghi rõ giá là placeholder.

[14] TÀI NGUYÊN [KHUNG] — 3 card bài viết: ảnh bìa, chip chuyên mục
(Cập nhật sản phẩm / Kiến thức vận hành / Tin tức), tiêu đề 2 dòng, ngày, link đọc thêm.

[15] FAQ [KHUNG] — accordion 1 cột hẹp giữa trang, 6 câu, mở sẵn câu đầu.
Chủ đề gợi ý để tôi thay sau: độ chính xác AI, dùng thử, bảo mật dữ liệu,
thời gian triển khai, tuỳ chỉnh gói, hỗ trợ kỹ thuật.

[16] FORM ĐẶT LỊCH DEMO — hai cột. Trái là lý do, phải là form.
H2: "Liên hệ ngay đặt lịch demo miễn phí"
Dẫn: "Chúng tôi sẽ đồng hành cùng bạn thiết kế mô hình tự động hoá học và thi
phù hợp nhất với quy mô trung tâm Anh ngữ của bạn."
Ba gạch đầu dòng:
  · Demo trực tiếp hiệu quả, tập trung đúng nhu cầu thực tế của trung tâm.
  · Tư vấn gói sản phẩm và hỗ trợ thiết lập lớp học thử nghiệm miễn phí.
  · Liên hệ và hỗ trợ kỹ thuật cực nhanh qua Zalo riêng.
Form "Thông tin đăng ký", các trường và thông báo lỗi đúng nguyên văn:
  Tên của bạn *              → "Vui lòng nhập tên của bạn."
  Trung tâm / cơ sở dạy học * → "Vui lòng nhập tên trung tâm."
  Số học viên trung bình *    → select: Dưới 20 / 20–50 / Trên 50 học viên;
                                lỗi "Vui lòng chọn quy mô."
  Nhu cầu hiện tại (chọn nhiều): Cần cả hệ thống thi thử và chấm bài định kỳ /
    Chỉ cần chấm Writing & Speaking bằng AI / Cần test đầu vào & xếp lớp tự động /
    Cần dashboard quản lý năng suất
  Email liên hệ *            → "Vui lòng nhập email hợp lệ."
  Số điện thoại / Zalo *     → "Vui lòng nhập số điện thoại Việt Nam hợp lệ
                                (09/03/07/05/08, 10 chữ số)."
  Nút: "Gửi & nhận lịch demo"
  Ghi chú: "Bằng việc gửi, bạn đồng ý để IELTS SMART liên hệ tư vấn."
Trạng thái thành công thay chỗ form: "Đã nhận thông tin! Cảm ơn bạn. Team IELTS SMART
sẽ liên hệ trong vòng 24h để sắp xếp buổi demo." — có icon tick --teal.

[17] FOOTER — nền --navy, chữ trắng/xám nhạt. Cột 1 là khối thương hiệu:
Logo + "Nền tảng chấm IELTS bằng AI dành cho trung tâm tiếng Anh. Chấm chuẩn hoá,
nhanh và đồng đều — giáo viên giữ quyền duyệt cuối."
Khối pháp lý:
  Công ty Cổ phần Công nghệ NOVAFORGE
  GPKD: Số 0111498091 — cấp ngày 14/05/2026, Sở Tài chính TP. Hà Nội
  Địa chỉ: Số 12 Xa La, phường Hà Đông, TP. Hà Nội, Việt Nam
  Người đại diện: Ông Mai Đức Giang
  Email: novaforge.stu@gmail.com · Điện thoại: 0374168445
Cột "Sản phẩm": Chấm Writing · Chấm Speaking · Dashboard quản lý · Báo cáo band
Cột "Trung tâm": Bảng giá theo quy mô · Ước tính ROI · Câu chuyện khách hàng · Onboarding
Cột "Chính sách & Hỗ trợ": Điều kiện giao dịch chung · Chính sách bảo mật thông tin ·
Chính sách xử lý khiếu nại · Chính sách giá · Chính sách thanh toán ·
Chính sách phương thức cung cấp, chấm dứt dịch vụ và hoàn tiền ·
Chính sách về điều kiện và hạn chế cung cấp hàng hoá, dịch vụ
Dòng cuối: "© 2026 IELTS SMART. Công cụ vận hành cho trung tâm Anh ngữ."
+ link Zalo, Facebook, số điện thoại. Chừa chỗ cho logo "Đã thông báo Bộ Công Thương".

[18] FLOATING — nút Zalo tròn góc phải dưới, luôn hiện sau khi cuộn qua hero.

=== CHẤT LƯỢNG TỐI THIỂU ===
Responsive tới 360px. Focus bàn phím nhìn thấy rõ. Tôn trọng prefers-reduced-motion.
Tương phản chữ đạt AA. Không dùng localStorage. Ảnh có alt thật.

Trước khi dựng, hãy trình bày ngắn gọn kế hoạch thiết kế (bảng token, ý tưởng
bố cục, khoảnh khắc chuyển động duy nhất), tự phản biện xem có chỗ nào đang rơi
vào khuôn mẫu chung không, rồi mới build.

=== PHỤ LỤC COPY — NỘI DUNG CHO CÁC KHỐI CHƯA CÓ CHỮ THẬT ===
Dùng nguyên văn phần dưới đây (đã viết riêng cho IELTS SMART). Mọi mục có dấu
[?] là số liệu tôi chưa xác nhận — để trống hoặc giữ nguyên dấu [?] và gắn
isPlaceholder: true.

[2] ANNOUNCEMENT PILL
  "Mới · Chấm Speaking nhận diện được nhiều giọng vùng miền" + link "Xem thay đổi"

[10] LOGO WALL
  Eyebrow: "Trung tâm đang dùng"
  Tiêu đề: "Những trung tâm đã chuyển việc chấm bài sang IELTS SMART"

[11] SỐ LIỆU — ba con số, mỗi con số kèm một câu giải thích ý nghĩa vận hành:
  "[?]+  trung tâm Anh ngữ"
    → "Từ lớp học một phòng đến chuỗi nhiều cơ sở, trải khắp ba miền."
  "[?]+  bài Writing & Speaking đã chấm"
    → "Tương đương khoảng [?] giờ giáo viên không phải ngồi chấm tay."
  "[?]%  mức nhất quán điểm giữa các lớp"
    → "Cùng một bài, cùng một band — dù học viên học ở cơ sở nào."

[12] CASE STUDY
  Tiêu đề khối: "Trung tâm đã thay đổi cách chấm bài như thế nào"
  Dẫn: "Ba câu chuyện về việc bỏ quy trình chấm tay: điều gì thay đổi trong tuần
  đầu, và con số nào cải thiện sau ba tháng."
  Card mẫu 1 — nhãn "Trung tâm luyện thi IELTS · Hà Nội":
    Tiêu đề: "Từ 20 phút một bài xuống còn 4 phút duyệt"
    Tóm tắt: "Giáo viên không còn ngồi chấm buổi tối. Học viên nhận nhận xét ngay
    hôm sau thay vì đợi đến buổi học kế tiếp."
    Chỉ số nổi bật: "[?] giờ tiết kiệm mỗi tháng"
  Card mẫu 2 — nhãn "Chuỗi 3 cơ sở · TP. Hồ Chí Minh":
    Tiêu đề: "Ba cơ sở, một thang điểm duy nhất"
    Tóm tắt: "Trước đây mỗi cơ sở chấm một kiểu, phụ huynh thắc mắc. Giờ ban giám
    đốc nhìn được độ lệch điểm giữa các lớp ngay trên dashboard."
    Chỉ số nổi bật: "[?]% độ nhất quán giữa các cơ sở"

[13] BẢNG GIÁ
  Tiêu đề: "Giá theo quy mô trung tâm"
  Dẫn: "Trả theo số học viên đang học, không tính theo số bài chấm. Trung tâm
  biết trước chi phí mỗi tháng."
  Gói 1 "Lớp nhỏ" — Dưới 20 học viên:
    "Dành cho giáo viên tự mở lớp hoặc trung tâm mới bắt đầu."
    · Chấm Writing & Speaking bằng AI
    · Báo cáo band gửi học viên
    · 1 tài khoản quản lý
    · Hỗ trợ qua Zalo
    · Không cần cam kết dài hạn
  Gói 2 "Trung tâm" — 20–50 học viên  [nhãn: Phổ biến]:
    "Dành cho trung tâm có nhiều lớp chạy song song."
    · Toàn bộ tính năng gói Lớp nhỏ
    · Test đầu vào & xếp lớp tự động
    · Dashboard năng suất theo giáo viên và lớp
    · Phân quyền theo vai trò
    · Hỗ trợ thiết lập ban đầu
  Gói 3 "Chuỗi" — Trên 50 học viên:
    "Dành cho trung tâm nhiều cơ sở cần kiểm soát chất lượng đồng bộ."
    · Toàn bộ tính năng gói Trung tâm
    · So sánh độ nhất quán điểm giữa các cơ sở
    · Xuất báo cáo định kỳ cho ban giám đốc
    · Người phụ trách hỗ trợ riêng
    · Thoả thuận mức độ dịch vụ
  Dòng dưới bảng: "Cần cấu hình riêng hoặc gói theo mùa cao điểm? Nói với chúng
  tôi tính năng nào cần và không cần, chúng tôi báo giá theo đúng phần đó."

[14] TÀI NGUYÊN
  Tiêu đề: "Đọc thêm trước khi quyết định"
  Dẫn: "Ghi chép về vận hành trung tâm Anh ngữ, cập nhật sản phẩm, và cách các
  trung tâm khác đang tổ chức việc chấm bài."
  Ba chuyên mục: "Cập nhật sản phẩm" · "Vận hành trung tâm" · "Chấm bài & học thuật"
  Ba tiêu đề bài mẫu:
    · "Mùa cao điểm: chuẩn bị năng lực chấm bài trước sáu tuần"
    · "Ba dấu hiệu cho thấy điểm chấm giữa các lớp đang lệch nhau"
    · "Test đầu vào nên hỏi gì để xếp lớp không phải sửa lại sau hai buổi"

[15] FAQ — tám câu, viết lại theo ngữ cảnh IELTS SMART:

  Q: IELTS SMART là gì và giải quyết việc gì cho trung tâm?
  A: Đây là hệ thống chấm bài IELTS bằng AI dùng trong nội bộ trung tâm. AI chấm
  trước bài Writing và Speaking, trả band cùng nhận xét theo bốn tiêu chí chính
  thức; giáo viên đọc lại, chỉnh nếu cần rồi duyệt. Trung tâm có thêm phần test
  đầu vào để xếp lớp và một dashboard theo dõi năng suất chấm.

  Q: Chấm bằng AI có chính xác không, và ai chịu trách nhiệm cho điểm cuối?
  A: AI đưa ra điểm đề xuất kèm giải thích ở từng vị trí lỗi, nhưng điểm gửi cho
  học viên chỉ phát hành sau khi giáo viên bấm duyệt. Nghĩa là trách nhiệm học
  thuật vẫn thuộc về trung tâm — AI rút ngắn thời gian, không thay người quyết định.
  Mức tương đồng giữa điểm AI và điểm giáo viên [?] — chúng tôi sẽ chia sẻ số liệu
  đo lường cụ thể trong buổi demo.

  Q: Dùng file Word và Google Sheet như hiện tại thì thiếu gì?
  A: Cách làm thủ công vẫn chạy được khi trung tâm nhỏ. Vấn đề xuất hiện lúc mở
  thêm lớp: bài nằm rải rác nhiều nơi, mỗi giáo viên chấm một chuẩn, và ban giám
  đốc không có cách nào biết lớp nào đang chậm tiến độ ngoài việc đi hỏi từng người.
  IELTS SMART gom bài, điểm, nhận xét và tiến độ về một chỗ.

  Q: Học viên nhìn thấy gì?
  A: Học viên đăng nhập vào phần dành riêng cho mình, làm bài, rồi nhận lại báo
  cáo band gồm điểm tổng, điểm bốn tiêu chí, danh sách lỗi kèm bản sửa và số từ.
  Báo cáo trình bày đủ gọn để gửi thẳng cho phụ huynh.

  Q: Triển khai mất bao lâu và có cần người làm IT không?
  A: Không cần. Trung tâm nhận tài khoản, tạo lớp, thêm học viên là dùng được.
  Đội chúng tôi hỗ trợ thiết lập lớp đầu tiên và hướng dẫn giáo viên trong buổi
  đầu, thường xong trong [?].

  Q: Dữ liệu bài làm của trung tâm được xử lý thế nào?
  A: Dữ liệu của mỗi trung tâm tách riêng, truy cập phân quyền theo vai trò —
  giáo viên chỉ thấy lớp mình phụ trách, quản lý thấy toàn trung tâm. Bài làm và
  bản ghi âm của học viên không dùng cho mục đích nào khác ngoài chấm và báo cáo
  cho chính trung tâm đó.

  Q: Có dùng thử trước khi ký không?
  A: Có. Chúng tôi mở một lớp thử nghiệm miễn phí để trung tâm chấm thật vài chục
  bài, so kết quả AI với điểm giáo viên, rồi mới quyết định.

  Q: Nếu trung tâm cần thêm tính năng thì sao?
  A: Nói với chúng tôi. Yêu cầu nào lặp lại ở nhiều trung tâm sẽ được đưa vào lộ
  trình phát triển; yêu cầu riêng thì bàn theo từng trường hợp.

  Dòng dưới FAQ: "Chưa thấy câu trả lời? Nhắn Zalo 037 416 8445, thường phản hồi
  trong giờ hành chính."

[13b] CTA BAND CUỐI (đặt trước footer, nếu form không nằm ngay trên đó)
  Tiêu đề: "Xem hệ thống chấm bài chạy trên chính đề của trung tâm bạn"
  Dẫn: "Gửi cho chúng tôi vài bài Writing thật. Buổi demo sẽ chấm trực tiếp trên
  những bài đó để bạn tự so với điểm giáo viên đang cho."
  Nút: "Đặt lịch demo" · "Nhắn Zalo"
```

---

## PROMPT 2 — Siết lại HERO

```
Hero chưa đủ sức nặng. Sửa lại:
- H1 tăng lên 60px desktop, Poppins Bold, letter-spacing -0.02em, tối đa 2 dòng.
- Card demo bên phải: nghiêng nhẹ 2 độ, nâng bóng lên 0 24px 60px rgba(14,33,73,.12),
  cho lệch ra ngoài lưới container khoảng 24px về phải để tạo cảm giác chiều sâu.
- Khoảnh khắc chuyển động duy nhất: khi trang tải, 4 thanh L/R/W/S chạy từ 0 lên
  đúng giá trị trong 900ms, lệch pha nhau 80ms, easing cubic-bezier(.2,.8,.2,1);
  số điểm đếm tăng theo. Tắt hoàn toàn nếu prefers-reduced-motion.
- Bỏ mọi hiệu ứng hover phóng to trên card này.
```

## PROMPT 3 — Khối Vấn đề ↔ Giải pháp

```
Làm rõ tương phản hai cột hơn:
- Cột "truyền thống": nền --gray-soft, chữ giảm xuống 92% độ đậm, icon dấu trừ xám.
- Cột "IELTS SMART": nền trắng, nhô cao hơn cột trái 16px, viền trên dày 3px --indigo,
  tick màu --teal.
- Thêm ở giữa hai cột một dải mảnh dọc với nhãn xoay đứng "trước / sau".
- Trên mobile: xếp dọc, cột IELTS SMART lên trước.
```

## PROMPT 4 — Ba khối demo sản phẩm (báo cáo band / chấm bài / dashboard)

```
Ba khối [6][7][8] đang trông giống nhau quá. Phân biệt bằng nền và hướng:
- Báo cáo band: nền trắng, chữ trái / UI phải.
- Giao diện chấm bài: nền --gray-soft, UI trái / chữ phải.
- Dashboard: nền --navy chữ trắng, UI nổi trên nền tối, chữ trái / UI phải.
Giữ nguyên nội dung. Đảm bảo mọi con số vẫn nằm trong CONTENT, không hardcode.
Bảng dashboard trên mobile: cho cuộn ngang, cột "Giáo viên" dính trái.
```

## PROMPT 5 — Bảng giá (khung)

```
Dựng lại khối bảng giá cho đúng chuẩn B2B Việt Nam:
- 3 cột theo đúng 3 mốc quy mô trong form đăng ký.
- Mỗi cột: tên gói, dòng giá dạng "Liên hệ báo giá" (để trống chờ tôi điền số VND),
  đơn vị "/tháng", 5 dòng tính năng, nút.
- Cột giữa gắn nhãn "Phổ biến" nền --indigo chữ trắng, nhô cao 20px.
- Thêm một toggle "Trả theo tháng / Trả theo năm (−15%)" ở trên bảng, chưa cần chạy logic.
- Dưới bảng thêm một dải: "Cần gói riêng cho chuỗi nhiều cơ sở?" + link.
Toàn bộ giá và tính năng để trong CONTENT.pricing với isPlaceholder: true.
```

## PROMPT 6 — Social proof (logo wall + số liệu + case study)

```
Ba khối bằng chứng đang rời rạc. Gom thành một mạch liền:
- Logo wall đặt ngay dưới hero, thu nhỏ, chỉ một dòng, có chú thích
  "Đang được tin dùng tại các trung tâm Anh ngữ".
- Dải số liệu chuyển xuống ngay trước case study, nền --navy, 3 con số.
- Case study: card có ảnh bìa tỉ lệ 3/2, và một khối trích dẫn ngắn kèm tên +
  chức danh người nói (đánh dấu placeholder).
Tất cả ảnh vẫn dùng placeholder viền đứt nét có tên khoá MEDIA.
```

## PROMPT 7 — FAQ

```
FAQ dựng dạng accordion một cột, rộng tối đa 760px, canh giữa.
- Mỗi hàng: câu hỏi Poppins SemiBold 19px, dấu +/− bên phải, đường kẻ hairline dưới.
- Mở mượt bằng grid-template-rows 0fr → 1fr, 240ms.
- Chỉ mở một câu tại một thời điểm; câu đầu mở sẵn.
- 6 câu placeholder theo chủ đề: độ chính xác AI, dùng thử miễn phí, bảo mật dữ liệu,
  thời gian triển khai, tuỳ chỉnh gói theo nhu cầu, kênh hỗ trợ kỹ thuật.
- Dưới FAQ thêm dòng: "Chưa thấy câu trả lời? Nhắn Zalo 037 416 8445."
```

## PROMPT 8 — Form đặt lịch demo

```
Nâng chất lượng form:
- Nhãn nằm trên ô nhập, ô cao 52px, bo 12px, viền hairline, focus đổi viền --indigo
  kèm ring 3px --indigo 12%.
- Lỗi hiện dưới ô, chữ 14px màu đỏ trầm, kèm icon cảnh báo nhỏ; ô lỗi viền đỏ.
- Trường "Nhu cầu hiện tại" render dạng 4 chip chọn nhiều, chip đang chọn nền
  --indigo 8% viền --indigo.
- Nút submit full-width, có trạng thái loading (spinner + "Đang gửi…") và disabled.
- Trạng thái thành công thay hẳn form bằng khối tick --teal, có nút "Gửi đăng ký khác".
- Không dùng thẻ <form>, xử lý bằng onClick.
```

## PROMPT 9 — Header & điều hướng

```
Header:
- Mặc định trong suốt nằm trên hero; sau khi cuộn 80px thì nền trắng 88% + blur 12px
  + hairline dưới. Chuyển đổi 200ms.
- Mục "Tài nguyên" là dropdown 3 mục: Blog · Hướng dẫn sử dụng · Câu chuyện khách hàng.
- Thêm chỉ báo section đang xem: mục menu tương ứng đổi màu --indigo khi cuộn tới.
- Mobile: menu toàn màn hình, nút CTA cố định dưới cùng.
- Thanh tiến trình đọc mảnh 2px màu --sky bám mép dưới header.
```

## PROMPT 10 — Chuẩn hoá lại hệ thống (chạy sau khi trang đã xong)

```
Rà soát lại toàn trang và chuẩn hoá:
- Gom mọi giá trị lặp (bán kính, bóng, padding section, chiều rộng container 1200px)
  thành CSS variables ở :root.
- Kiểm tra không còn chuỗi tiếng Việt nào nằm ngoài CONTENT.
- Kiểm tra mọi ảnh đều đi qua MEDIA và có placeholder khi src rỗng.
- Liệt kê cho tôi danh sách đầy đủ các khoá trong MEDIA kèm tỉ lệ khung ảnh
  cần chuẩn bị, dạng bảng.
- Liệt kê các mục đang gắn isPlaceholder: true để tôi biết chỗ nào cần viết nội dung thật.
```

## PROMPT 11 — Responsive

```
Rà responsive ở 3 mốc: 1440 / 768 / 375.
- Mọi khối 2 cột chuyển thành 1 cột ở 768, thứ tự ưu tiên: chữ trước, UI sau,
  RIÊNG hero thì UI xuống dưới.
- Grid 6 lý do: 3 cột → 2 cột → 1 cột.
- Bảng giá ở mobile: cuộn ngang có snap, cột "Phổ biến" hiện đầu tiên.
- Cỡ chữ h1 giảm còn 34px ở 375, h2 còn 26px.
- Padding dọc section giảm từ 96 xuống 56.
- Không để bất kỳ phần tử nào tràn ngang gây cuộn ngang toàn trang.
```

## PROMPT 12 — Song ngữ VI / EN

```
Thêm lớp ngôn ngữ:
- Đổi CONTENT thành CONTENT = { vi: {...}, en: {...} } giữ nguyên cấu trúc khoá.
- Nút VI/EN trên header đổi ngôn ngữ toàn trang, mặc định VI.
- Dịch sang tiếng Anh cho đối tượng chủ trung tâm; giữ nguyên thuật ngữ IELTS
  (band, Task 1, Task Achievement, Coherence & Cohesion, Lexical Resource,
  Grammatical Range & Accuracy) không dịch.
- Giữ nguyên phần pháp lý công ty bằng tiếng Việt ở cả hai ngôn ngữ.
```

## PROMPT 13 — QA cuối

```
Tự kiểm tra và báo cáo lại cho tôi:
1. Tương phản màu mọi cặp chữ/nền có đạt WCAG AA không, liệt kê chỗ chưa đạt.
2. Trang có bao nhiêu CTA dẫn tới form, đặt ở những vị trí nào.
3. Thứ tự tab bàn phím có đi đúng luồng đọc không.
4. Có hiệu ứng chuyển động nào chạy khi prefers-reduced-motion không.
5. Đếm số font-family và số màu thực tế đang dùng — nếu vượt quá 2 font và 5 màu
   nền tảng, chỉ ra chỗ thừa và đề xuất cắt.
```

## PROMPT 14 — Nạp nội dung sản phẩm thật từ app.ieltssmart.vn

> Dán prompt này **sau** Prompt 1, khi anh đã điền phần trong ngoặc vuông. `app.ieltssmart.vn`
> là ứng dụng render phía client và nằm sau đăng nhập nên Claude Design không tự đọc được —
> anh cần mô tả lại hoặc dán ảnh chụp màn hình kèm theo.

```
Đây là mô tả sản phẩm thật lấy từ app.ieltssmart.vn. Hãy dùng nó để viết lại phần
mô tả tính năng trên landing page cho đúng với những gì người dùng thật sự thấy,
thay cho nội dung placeholder hiện tại. Cập nhật trực tiếp vào CONTENT.

Hệ thống có hai vai trò đăng nhập:

VAI TRÒ GIÁO VIÊN / QUẢN LÝ TRUNG TÂM
  Các màn hình chính: [liệt kê tên từng màn hình]
  Với mỗi màn hình, mô tả: [làm được gì · mất bao lâu · thay thế thao tác thủ công nào]
  Thao tác thường dùng nhất: [...]
  Quyền hạn phân theo cấp: [...]

VAI TRÒ HỌC VIÊN
  Các màn hình chính: [liệt kê]
  Học viên nộp bài bằng cách nào: [...]
  Học viên nhận lại những gì và trong bao lâu: [...]
  Có xem được lịch sử tiến bộ không: [...]

Dạng bài / kỹ năng hệ thống đang hỗ trợ: [Writing Task 1 / Task 2 / Speaking Part
1-2-3 / Listening / Reading — ghi rõ cái nào đã có, cái nào đang phát triển]

Quy tắc viết lại:
- Mỗi tính năng nêu theo công thức: người dùng làm gì → hệ thống trả lại gì →
  tiết kiệm được thao tác nào. Không mô tả bằng thuật ngữ kỹ thuật.
- Tính năng nào đang phát triển thì ghi nhãn "Sắp có", đừng viết như đã chạy.
- Ảnh chụp màn hình tôi gửi kèm chỉ để bạn hiểu bố cục — đừng chèn ảnh đó vào
  trang, hãy dựng lại bằng UI thật như các khối demo khác.
- Sau khi cập nhật, liệt kê cho tôi những chỗ trong CONTENT đã đổi.
```

---

## PHẦN C — DANH SÁCH BẠN CẦN CHUẨN BỊ SAU

**Hình ảnh (điền vào `MEDIA`)**

| Khoá | Tỉ lệ | Nội dung cần |
|---|---|---|
| `logo` | tự do | Logo IELTS SMART bản sáng + bản tối |
| `logoWall[0..7]` | 3/1 | Logo 8 trung tâm đối tác (cần văn bản đồng ý dùng logo) |
| `caseStudy1Cover`, `caseStudy2Cover` | 3/2 | Ảnh lớp học / phòng máy tại trung tâm |
| `pressLogos[0..4]` | 3/1 | Logo báo chí, giải thưởng nếu có |
| `blogCover1..3` | 16/9 | Ảnh bìa bài viết |
| `teamPhoto` | 16/9 | Ảnh đội ngũ (dự phòng cho khối Về chúng tôi) |

**Nội dung cần viết**
- 3 con số thật cho dải số liệu (số trung tâm, số bài đã chấm, số giờ tiết kiệm)
- 2 case study có sự đồng ý của trung tâm
- Giá VND cho 3 mốc quy mô
- 6 câu FAQ và câu trả lời
- 3 bài viết cho khối Tài nguyên

**Lưu ý pháp lý**
- Logo trung tâm và trích dẫn khách hàng cần văn bản cho phép trước khi lên trang.
- Con số "90% thời gian tiết kiệm" nên có phương pháp đo lường lưu nội bộ để phòng khi bị hỏi.
