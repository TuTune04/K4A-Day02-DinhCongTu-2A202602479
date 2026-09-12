# 03 — Individual Reflection

> Viết bằng lời của bạn (Phase 7 trong `01-worksheet.md`). Có thể dùng AI gợi ý câu hỏi tự soi, không dùng AI viết thay. 8-12 câu, có chuyện cụ thể.

## Thông tin cá nhân

- Họ và tên: Đinh Công Tú
- Mã học viên: 2A202602479
- Nhóm: Nhóm 6 thành viên (Lê Phan Việt Cường, Nguyễn Đức Danh, Bùi Đức Thông, Bùi Đức Vinh, Đỗ Phúc Hưng, Đinh Công Tú)
- Candidate problem nhóm chọn: Hỗ trợ chủ xe VinFast hiểu cảnh báo/lỗi, xác định hành động an toàn và chuyển đủ dữ liệu cho kỹ thuật viên khi cần.

---

## 1. Tôi đã tham gia vào phần nào?

Ghi việc cụ thể + kết quả cụ thể. Không ghi chung chung kiểu "tham gia thảo luận".

| Hoạt động | Tôi đã làm gì? (việc cụ thể) | Kết quả / ảnh hưởng tới nhóm |
|---|---|---|
| Scan cá nhân | Tôi rà soát 8 vấn đề trong bối cảnh sinh viên mới tốt nghiệp, đo thời gian và chọn ba vấn đề về dựng khung GitHub, viết CV có dấu ấn cá nhân và tìm tài liệu ôn tập. | Nhóm có thêm ba candidate thuộc cluster tạo nội dung/hỗ trợ quyết định và tìm kiếm/tổng hợp thông tin để so sánh. |
| Pitch Problem Card | Tôi trình bày ba card với actor, workflow, bottleneck và metric; trong đó card dựng khung GitHub có baseline 60–90 phút và phương án AI skills dựa trên CV/GitHub. | Nhóm hiểu được pain cá nhân, nhưng cũng nhận ra template hoặc script có thể đã đủ nên không ưu tiên candidate này. |
| Challenge bài của bạn khác | Với candidate hỗ trợ chủ xe VinFast, tôi tập trung hỏi về khả năng truy cập dữ liệu xe, độ chính xác, hậu quả khi phân loại sai và ai chịu trách nhiệm duyệt kết quả. | Ý tưởng được thu hẹp từ “AI Technician” tự chủ thành workflow hỗ trợ read-only có rule an toàn và kỹ thuật viên kiểm tra. |
| Gom trùng / cluster | Tôi cùng nhóm đối chiếu ba candidate cá nhân với các bài khác và xếp chúng vào cluster tìm kiếm/tổng hợp hoặc tạo nội dung/hỗ trợ quyết định. | Nhóm nhìn được các pattern chung và tránh chọn bài chỉ vì giải pháp AI nghe hấp dẫn. |
| Chọn candidate problem | Tôi tham gia so sánh tính khả thi kỹ thuật giữa hỗ trợ cảnh báo VinFast, đối soát phạt nguội và nối ticket sự cố. | Nhóm chọn bài VinFast vì actor, trigger và workflow rõ hơn, đồng thời ghi nhận dữ liệu và an toàn là hai điều chưa chắc. |
| Validation / research | Tôi xem xét tính khả dụng của mã lỗi, model/software version, manual, log ẩn danh và nhãn do kỹ thuật viên cung cấp; tôi không trực tiếp phỏng vấn chủ xe. | Báo cáo ghi rõ dữ liệu còn thiếu, không dùng nguồn NHTSA để khái quát tình hình tại Việt Nam và yêu cầu validation trước khi triển khai thật. |
| Workflow nhóm | Tôi phân tích các điểm can thiệp kỹ thuật: đọc dữ liệu read-only, rule phân loại severity, truy xuất manual đúng phiên bản, AI giải thích và tạo gói handoff. | Future workflow có sáu bước, có safety gate, human boundary và fallback khi confidence thấp hoặc nguồn mâu thuẫn. |
| Problem Statement | Tôi góp phần làm rõ AI chỉ đứng sau bước rule an toàn và trước bước chủ xe chọn hành động; đồng thời xác định các giới hạn không điều khiển xe, không xóa lỗi và không tự kết luận xe an toàn. | Problem Statement v1 có intervention point và boundary cụ thể, tránh biến vấn đề hỗ trợ thông tin thành bài toán chẩn đoán hoặc điều khiển xe. |
| Rule / Workflow / Agent | Tôi so sánh khả năng kỹ thuật và rủi ro của ba mức: Rule cho mã lỗi xác định, Workflow cho phần giải thích/handoff và Agent cho hành động tự chủ. | Nhóm chọn Workflow cho MVP, giữ Rule làm safety gate và chưa chọn Agent vì rủi ro an toàn, quyền riêng tư và thiếu cơ chế phê duyệt. |
| Decision | Tôi ủng hộ chỉ làm prototype offline, read-only và kiểm thử trên case ẩn danh thay vì tích hợp trực tiếp lên xe. | Nhóm chốt NOT YET cho AI Technician on-board và GO cho prototype để đo pain, routing accuracy, thời gian cùng số lượt hỏi bổ sung. |

**Dấu tay rõ nhất của tôi trong artifact cuối (1-2 câu):**

```text
Dấu tay rõ nhất của tôi là phần phân tích tính khả thi kỹ thuật: xác định dữ liệu đầu vào, giới hạn quyền của AI và điểm bắt buộc con người xác nhận. Phần này giúp artifact cuối chuyển từ ý tưởng Agent tự chủ sang Workflow read-only có rule an toàn, kỹ thuật viên kiểm tra và điều kiện rollback rõ ràng.
```

---

## 2. Bảng dùng AI (mỗi dòng 1 phase có dùng AI — 2 cột cuối bắt buộc)

| Phase | Tôi dùng AI để làm gì? | AI hữu ích ở đâu? | AI sai / hời hợt ở đâu? | Tôi sửa gì bằng nhận định của mình? |
|---|---|---|---|---|
| Scan | Sau khi tự xác định các pain chính, tôi dùng AI để mở rộng theo bốn lăng kính và gợi ý cách đo. | AI giúp tách các việc tìm JD, chỉnh CV, khởi tạo dự án và tìm tài liệu thành workflow riêng có actor và metric. | Một số gợi ý như tự động gửi hàng loạt CV hoặc tự trả lời nhà tuyển dụng không phải pain thật của tôi và đi quá nhanh sang solution. | Tôi loại các ý không có trải nghiệm thật, giữ 8 problem và ghi số đo cá nhân hoặc đánh dấu số liệu còn là ước tính. |
| Problem Card | Tôi dùng AI để phản biện ba card, viết rõ bottleneck, impact, metric, non-AI alternative và AI hypothesis. | AI giúp tôi nhìn Card 1 như một hệ thống skills gồm Capability Profile, blueprint, scaffolding, validation và human gate. | AI ban đầu mô tả Card 1 như một template chung và Card 2 như bài tối ưu từ khóa CV, chưa phản ánh việc năng lực thay đổi hoặc cá tính cá nhân. | Tôi bổ sung cơ chế cập nhật từ CV/GitHub cho Card 1 và cân bằng tiêu chí sàng lọc với giọng văn cá nhân cho Card 2. |
| Workflow | Tôi dùng AI để chuẩn hóa current/future workflow và tạo ba ảnh minh họa. | AI thể hiện được thứ tự bước, thời gian, bottleneck, human boundary và fallback một cách dễ nhìn. | AI có thể làm workflow tương lai trông chắc chắn hơn bằng chứng hiện có, đặc biệt với các con số mục tiêu dưới 30 phút hoặc dưới 5 phút. | Tôi giữ các con số dưới dạng mục tiêu cần đo, thêm bước phê duyệt của con người và phương án quay về template, checklist hoặc tài liệu gốc. |
| Research | AI hỗ trợ nhóm tổng hợp câu hỏi cần kiểm chứng và phân biệt nguồn chính thức với suy luận. | AI giúp nhận ra ứng dụng VinFast đã giải quyết một phần cảnh báo, đặt dịch vụ và hỗ trợ trên đường nên bài toán phải được thu hẹp. | Nếu đọc hời hợt, AI có thể dùng 14 báo cáo NHTSA hoặc một đợt triệu hồi để suy rộng thành “xe VinFast có nhiều lỗi”. | Nhóm chỉ dùng nguồn đó để xác nhận trường hợp cụ thể, ghi rõ phạm vi VF 8 tại Hoa Kỳ và không khái quát cho người dùng Việt Nam. |
| Problem Statement | AI giúp rà lại các field actor, workflow, bottleneck, impact, metric, boundary và intervention point. | AI chỉ ra các cụm mơ hồ như “xe có nhiều lỗi”, “mất nhiều thời gian” và “AI Technician”. | AI có xu hướng viết impact mạnh dù nhóm chưa có phỏng vấn hoặc baseline phút/case. | Tôi cùng nhóm đổi trọng tâm sang hành trình xử lý cảnh báo, ghi rõ điều chưa đo và giới hạn AI ở giải thích cùng chuẩn hóa handoff. |
| Rule / Workflow / Agent | Tôi dùng AI để so sánh khả năng và rủi ro của Rule, Workflow và Agent. | AI giúp tách phần quyết định an toàn xác định cho Rule và phần ngôn ngữ/tổng hợp cho AI trong Workflow. | AI có thể mặc định mơ hồ cao, phức tạp cao thì nên dùng Agent, nhưng suy luận đó không phù hợp với miền safety-critical. | Tôi ưu tiên Workflow có đường đi cố định, Rule làm safety gate và con người duyệt; Agent tự điều khiển hoặc tự gọi dịch vụ bị loại khỏi MVP. |
| Decision | AI hỗ trợ lập checklist Go/Not Yet/No-Go, pilot nhỏ nhất và exit condition. | AI giúp chuyển tranh luận thành các điều kiện đo được như routing accuracy, case safety-critical, nguồn đúng phiên bản và kỹ thuật viên chấp nhận handoff. | AI không thể tự xác nhận pain, quyền sử dụng log hoặc người chịu trách nhiệm kỹ thuật. | Tôi cùng nhóm chọn NOT YET cho triển khai thật và chỉ GO prototype offline; yêu cầu phỏng vấn, dữ liệu ẩn danh và kỹ thuật viên gán nhãn trước khi đi tiếp. |

> Nếu phase nào không dùng AI, ghi `Không dùng` và vì sao tự làm.

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

```text
Ở giai đoạn hội tụ, mỗi thành viên trong nhóm chọn một dự án tiêu biểu của mình, vì vậy nhóm có sáu ý tưởng để lần lượt trình bày và review. Sau mỗi phần trình bày, cả sáu thành viên cùng đặt câu hỏi, phản biện điểm yếu và ghi nhận những điểm có giá trị thay vì chỉ bỏ phiếu theo sở thích. Nhóm thực hiện hai vòng lọc; sau vòng đầu, ý tưởng dựng khung dự án GitHub của tôi, bài hỗ trợ chủ xe VinFast và bài tìm vị trí đặt trạm sạc của bạn Cường được đưa vào vòng thảo luận thứ hai. Qua quá trình này, tôi nhận ra một ý tưởng có quy mô lớn hoặc sử dụng nhiều dữ liệu chưa chắc đã cần AI. Với bài tìm vị trí đặt trạm sạc, nhóm đặt câu hỏi “có thực sự cần AI không?” vì dữ liệu có thể được gán nhãn và xử lý bằng thuật toán truyền thống với chi phí thấp hơn, tốc độ nhanh hơn và kết quả dễ kiểm soát hơn. Bài dựng khung dự án GitHub của tôi được nhận xét là đơn giản hơn, chủ yếu giải quyết nhu cầu cá nhân hoặc một nhóm lập trình nhỏ, nên mức độ ảnh hưởng chưa rộng bằng bài toán VinFast. Tuy không được chọn làm bài chính, phản hồi này giúp tôi hiểu rằng tính gần gũi và khả năng làm được chưa đủ; tôi còn phải chứng minh số người gặp vấn đề, tần suất và giá trị mang lại khi mở rộng. Đối với bài VinFast, nhóm đánh giá cao actor, thời điểm phát sinh vấn đề và tác động rõ hơn, nhưng vẫn thu hẹp từ “AI Technician” thành workflow hỗ trợ có rule an toàn và con người xác nhận. Tôi học được rằng lựa chọn Rule, Workflow hay Agent phải dựa trên độ mơ hồ, dữ liệu, rủi ro và phương án thay thế, chứ không dựa trên việc giải pháp nào nghe hiện đại hơn. Nếu làm lại, tôi sẽ chuẩn bị thêm bằng chứng từ các lập trình viên mới khác để kiểm tra liệu bài dựng khung GitHub có phải pain của một nhóm người dùng đủ lớn hay chỉ là khó khăn riêng của tôi.
```

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
