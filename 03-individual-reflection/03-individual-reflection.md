# 03 — Individual Reflection

> Viết bằng lời của bạn (Phase 7 trong `01-worksheet.md`). Có thể dùng AI gợi ý câu hỏi tự soi, không dùng AI viết thay. 8-12 câu, có chuyện cụ thể.

## Thông tin cá nhân

- Họ và tên:  Nguyễn Ngọc Thái An
- Mã học viên: 2A202602462
- Nhóm: Biệt đội ánh sáng
- Candidate problem nhóm chọn: Tự kê khai thuế 01/CNKD hằng quý

---

## 1. Tôi đã tham gia vào phần nào?

Ghi việc cụ thể + kết quả cụ thể. Không ghi chung chung kiểu "tham gia thảo luận".

| Hoạt động | Tôi đã làm gì? (việc cụ thể) | Kết quả / ảnh hưởng tới nhóm |
|---|---|---|
| Scan cá nhân | Scan 6 vấn đề trong workflow tìm việc, ghi actor và số liệu cho từng vấn đềư | Đưa vào thảo luận các problem có bằng chứng cá nhân, thay vì chỉ nêu ý tưởng chung. Đóng góp ý tưởng #13, #14, #15 trong phần report nhóm. |
| Pitch Problem Card | Pitch Card #1 về lọc và đối chiếu JD trước khi apply, với workflow hiện tại/tương lai và metric mismatch. | Nhóm có thêm một candidate có workflow rõ, nhưng cũng thấy tỷ lệ mismatch 30% cần kiểm chứng lại. Vấn đề được đánh giá là đã có nhiều tool hỗ trợ trên thị trường và chưa tìm được góc khai thác hợp lí.|
| Challenge bài của bạn khác | Đặt câu hỏi tính cần thiết của việc sử dụng AI trong việc khai báo thuế theo luật mới | Làm rõ mảng AI sẽ sử dụng tránh trường hợp hiểu nhầm cách ứng dụng Agent và ORC + Deep learning |
| Gom trùng / cluster | Thảo luận và phân loại 15 ý tưởng | Gom gọn được 4 cụm chủ đề rõ ràng |
| Chọn candidate problem | Đặt ra các góc nhìn khác nhau về top các ý tưởng nhóm đã chọn ra, so sánh để xem tính khả thi của cả 3 | Nhóm chọn #10 — tự kê khai thuế 01/CNKD — với tổng điểm 35/35. |
| Validation / research | Cùng nhóm đọc poll 8 người, đối chiếu quote công khai và rà các công cụ như eTax, HTKK, MISA. Tìm hiểu về quy trình thuế hiện tại, trước và sau khi được áp dụng luật thuế mới. | Nhóm thu hẹp actor và xác định pain chính là hiểu field, chọn phương pháp và đối chiếu doanh thu, không phải nút nộp. |
| Workflow nhóm | Góp ý từ kinh nghiệm phân tích workflow cá nhân về việc phải tách phần Rule, AI và human boundary. | Workflow cuối giữ chủ hộ ở bước review và tự nộp, AI chỉ tạo draft trong sandbox. |
| Problem Statement | Đóng góp việc kiểm tra actor, bottleneck, metric và boundary có khớp với evidence research hay không | Problem statement v1 ghi rõ scope PP1, chưa làm PP2, không nộp thật và không bịa doanh thu. |
| Rule / Workflow / Agent | Tham gia đối chiếu mức phù hợp: Rule đủ cho checklist nhưng không đọc chứng từ rời, Agent có rủi ro quá cao, Workflow phù hợp nhất. | Nhóm chọn Workflow, dùng Rule ở checklist và AI ở bước đọc/giải thích, thay vì làm Agent tự nộp. |
| Decision | Đồng ý với quyết định chỉ Go ở mức sandbox, chưa Go production. Baseline thật và dữ liệu hóa đơn thật vẫn cần validate thêm. | Quyết định giữ được human review và có điều kiện rollback về Excel/checklist nếu AI sai quá nhiều. |

**Dấu tay rõ nhất của tôi trong artifact cuối (1-2 câu):** Đóng góp các ý tưởng #13, #14, #15, tham gia phân loại 15 ý tưởng thành 4 cụm và so sánh các candidate để nhóm chọn bài toán tự kê khai thuế 01/CNKD. Ở artifact cuối, dấu tay của tôi rõ nhất ở phần research và boundary: làm rõ pain nằm ở việc hiểu field, chọn phương pháp và đối chiếu doanh thu; đồng thời giữ giải pháp ở mức Workflow với human review, nguồn chính thức và không để AI tự nộp thuế.

---

## 2. Bảng dùng AI (mỗi dòng 1 phase có dùng AI — 2 cột cuối bắt buộc)

| Phase | Tôi dùng AI để làm gì? | AI hữu ích ở đâu? | AI sai / hời hợt ở đâu? | Tôi sửa gì bằng nhận định của mình? |
|---|---|---|---|---|
| Scan | Dùng Claude để phản biện 6 problem và kiểm tra số liệu có phải bằng chứng thật không. | AI giúp tách hiện tượng “đọc sót JD” khỏi nguyên nhân “thiếu bước đối chiếu”, đồng thời gợi ý nhìn đúng bottleneck của case Glassdoor | AI có thể đẩy tôi về các cảnh báo JD phổ biến trên mạng, dù đó không phải trải nghiệm cá nhân | Bỏ ý “bẫy trong JD” vì là thông tin thứ cấp và thay bằng case Glassdoor thực tế, giữ lại các con số có nguồn từ workflow của mình |
| Problem Card | AI hỗ trợ soi lại cách viết problem và đặt câu hỏi phản biện cho Card #1 | Gợi ý kiểm tra false negative và yêu cầu xác minh lại con số mismatch 30% | Ban đầu bỏ qua con số ước lượng 30% | Ghi rõ 30% là ước tính, đưa việc kiểm tra từng case vào phần chưa chắc và không trình bày nó như ground truth |
| Workflow | Dùng AI để vẽ các workflow trong phần scan | Giúp tạo hình ảnh workflow nhanh chóng | Hình ảnh AI tạo ra chưa thể hiện đầy đủ các bước, thời gian và điểm người dùng kiểm tra | Kiểm tra lại workflow, bổ sung bottleneck, thời gian, fallback và human boundary |
| Research | Không dùng AI để thay việc kiểm chứng nguồn| AI chỉ có thể giúp gợi ý hướng tìm công cụ hoặc câu hỏi cần kiểm tra | Tóm tắt AI về quy định thuế có thể cũ hoặc nhầm | Ưu tiên nguồn chính thức, ghi rõ quote thứ cấp, baseline chưa bấm giờ và không dùng số liệu AI nếu không có link kiểm được |
| Problem Statement | Dùng AI để phản biện bản Problem Statement và tìm những chỗ còn thiếu. | AI gợi ý nhóm làm rõ actor, bottleneck, metric và boundary | AI không thể tự xác nhận baseline thật và có thể đề xuất scope quá rộng | Tự kiểm tra lại bằng research, thu hẹp scope còn PP1, ghi rõ thời gian chỉ là ước lượng và chọn sandbox thay vì nộp thật. |
| Rule / Workflow / Agent | Dùng AI để nhận xét những ý kiến của nhóm về vấn đề này | Giúp nhóm so sánh rõ ưu, nhược điểm của Rule, Workflow và Agent | AI có thể đề xuất Agent quá phức tạp, chưa phù hợp với rủi ro pháp lý của việc kê khai thuế | Cùng nhóm chọn Workflow, dùng Rule cho checklist, giữ human review và không để AI tự nộp thuế |
| Decision | Không dùng AI thay quyết định Go/Not Yet/No-Go | Các câu hỏi phản biện giúp kiểm tra dữ liệu, người review và rollback | Nếu chỉ nhìn impact, nhóm có thể kết luận Go production quá sớm | Tôi giữ quyết định Go nhỏ trong sandbox, Not Yet với dữ liệu thật và đặt ngưỡng rollback nếu AI sai hơn 70% draft |


---

## 3. Reflection câu hỏi mở

Chọn 3-4 câu trong 6 câu dưới để viết thành đoạn 8-12 câu (không trả lời bullet 1 dòng):
- Tôi học được gì khi nghe top 3 problems của các bạn khác?
- Nhóm có lúc nào bị solution-first, đòi làm Agent cho ngầu không?
- Tôi có thay đổi ý kiến sau khi bị challenge không, vì sao đổi?
- Tôi đóng góp gì thật sự vào artifact cuối, phần nào có dấu tay của tôi?
- Điều khó nhất khi viết Problem Statement là gì, metric hay boundary?
- Nếu làm lại, tôi sẽ challenge nhóm mạnh hơn ở điểm nào?

**Reflection:**
Khi nghe top 3 problem của các bạn, tôi học được rằng một problem tốt cần có actor, workflow, evidence và metric rõ ràng. Tôi cũng nhận ra rằng không phải problem nào cũng cần AI. Nhiều vấn đề có thể được giải quyết bằng rule hoặc một quy trình đơn giản. Ban đầu, tôi tập trung nhiều vào bài toán candidate lọc và đối chiếu với JD vì problem này có số liệu và tiêu chí khá cụ thể. Sau khi được các bạn challenge, tôi thay đổi quan điểm và đồng ý chọn bài toán tự kê khai thuế 01/CNKD. Tôi thấy bài toán này phù hợp hơn vì nhóm có thể thu hẹp scope và kiểm chứng workflow rõ ràng. Tôi vẫn cho rằng AI chỉ nên hỗ trợ một phần trong quy trình. AI không nên tự quyết định hoặc tự nộp tờ khai. Trong artifact cuối, tôi đóng góp các ý tưởng #13, #14 và #15. Tôi cũng tham gia phân loại 15 ý tưởng thành 4 nhóm và so sánh các candidate để nhóm chọn bài toán tự kê khai thuế 01/CNKD. Ở phần research, tôi cùng nhóm kiểm tra poll, các quote công khai và tìm hiểu các công cụ như eTax, HTKK và MISA. Dấu ấn của tôi nằm ở việc làm rõ pain point xoay quanh việc hiểu các field, lựa chọn phương pháp kê khai và đối chiếu doanh thu. Tôi cũng góp phần giữ human review, ưu tiên nguồn chính thức và xác định rõ boundary của giải pháp. Ngoài ra quan trọng nhất là tôi cho rằng AI không nên được phép tự nộp thuế.


---

## 4. Tự kiểm cuối bài (check trước khi nộp repo)

- [x] [12đ] Cá nhân có 5+ problems + top 3 Problem Cards
- [x] [12đ] Tôi đã pitch rõ + challenge nhóm đúng trọng tâm (ghi ở bảng mục 1)
- [x] Nhóm có nhật ký hội tụ từ candidates về 1 bài
- [x] [15đ] Nhóm có workflow trước/sau
- [x] [20đ] Nhóm có PS v0/v1 với metric + boundary rõ
- [x] [15đ] Nhóm có so sánh No AI / Rule / Workflow / Agent
- [x] [10đ] Nhóm có Go / Not Yet / No-Go + lý do rõ
- [x] [10đ] Reflection này có vai trò thật + AI giúp/sai ở đâu + điều học được + nếu làm lại đổi gì
- [x] [6đ] Tôi tự giải thích được mạch problem → workflow → metric → boundary → độ phù hợp AI
