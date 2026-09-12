# 02 — Group Problem Statement (Bản nộp nhóm)


> Làm chung 1 bản, mỗi thành viên copy vào repo cá nhân. Đi theo Phase 3 → 6 trong `01-worksheet.md`. Nhóm chỉ chọn **candidate problem** ở Phase 3, viết Problem Statement sau khi validate + vẽ workflow.


## Thành viên nhóm


| STT | Họ và tên          | Mã học viên | Vai trò trong nhóm                      |
|----:|--------------------|-------------|-----------------------------------------|
|   1 | Lê Phan Việt Cường | 2A202602641 | Phân tích quy trình vận hành và dữ liệu |
|   2 | Nguyễn Đức Danh    | 2A202602722 | Tổng hợp báo cáo và workflow            |
|   3 | Bùi Đức Thông      | 2A202602931 | Chủ đề xuất candidate VinFast           |
|   4 | Bùi Đức Vinh       | 2A202602801 | Phân tích actor, pain và rủi ro         |
|   5 | Đỗ Phúc Hưng       | 2A202602762 | Xây dựng metric và so sánh phương án    |
|   6 | Đinh Công Tú       | 2A202602479 | Phân tích tính khả thi kỹ thuật         |


**Candidate problem nhóm chọn:**


```text
Khi xe xuất hiện cảnh báo hoặc vận hành bất thường, chủ xe VinFast khó
hiểu mức độ nghiêm trọng, thu thập đủ thông tin và chọn hành động an toàn
tiếp theo mà không phải tự tra nhiều nguồn hoặc mô tả lại cho kỹ thuật viên.
```


---


## Phase 3 — Group Convergence: từ 18 candidates về 1


### 3.1. Trình bày top 3 mỗi người (mỗi candidate 1-2 phút)


|  # | Người đưa ra       | Candidate problem                                                 | Người gặp vấn đề                     | Điểm nghẽn                                                 | Cảm nhận nhanh                                                             |
|---:|--------------------|-------------------------------------------------------------------|--------------------------------------|------------------------------------------------------------|----------------------------------------------------------------------------|
|  1 | Lê Phan Việt Cường | Đối soát và quản lý hồ sơ phạt nguội                              | Đơn vị vận hành đội xe               | Chuẩn hóa thông báo, nối tài xế–xe–ca và tạo hồ sơ         | Workflow và KPI rõ; phụ thuộc dữ liệu nội bộ                               |
|  2 | Lê Phan Việt Cường | Đề xuất vị trí xây trạm sạc mới                                   | Đội quy hoạch hạ tầng                | Kết hợp nhu cầu, lộ trình, điện lưới, đất và chi phí       | Impact lớn nhưng scope/data quá rộng cho lab                               |
|  3 | Lê Phan Việt Cường | Chuẩn hóa bằng chứng bàn giao ngoại thất                          | Khách hàng và đơn vị giao nhận xe    | Ảnh trước/sau không đồng nhất góc chụp và ánh sáng         | Pain rõ; cần dữ liệu ảnh và kiểm thử CV                                    |
|  4 | Đỗ Phúc Hưng       | Tổng hợp weekly report                                            | PM và leadership                     | Biến dữ liệu nhiều nguồn thành narrative                   | Workflow rõ; có phương án mẫu trong worksheet                              |
|  5 | Đỗ Phúc Hưng       | Phân loại lead từ form                                            | Sales/marketing                      | Đánh giá và chuyển lead đúng người đúng lúc                | Impact đo được; cần dữ liệu lịch sử                                        |
|  6 | Đỗ Phúc Hưng       | Viết mô tả căn hộ cho landing page                                | Marketing Vinhomes                   | Giữ đúng dữ kiện và giọng thương hiệu                      | AI fit tốt; quality metric còn chủ quan                                    |
|  7 | Bùi Đức Vinh       | Đọc lịch sử bệnh án dài trước khi khám                            | Bác sĩ                               | Tìm diễn biến và quyết định quan trọng                     | Impact cao nhưng dữ liệu nhạy cảm và rủi ro y khoa lớn                     |
|  8 | Bùi Đức Vinh       | Tổng hợp hàng trăm email mỗi sáng                                 | CEO và PM                            | Tách nội dung cần hành động khỏi email ít quan trọng       | Tiết kiệm thời gian; cần quyền truy cập email                              |
|  9 | Bùi Đức Vinh       | Đọc CV và nhập dữ liệu vào ATS/Sheet                              | Recruiter và HR                      | Trích xuất, chuẩn hóa và nhập lại dữ liệu                  | Lặp lại, đo được; rule/OCR có thể đã đủ                                    |
| 10 | Bùi Đức Thông      | Hỗ trợ chủ xe VinFast khi có lỗi/cảnh báo phần cứng hoặc phần mềm | Chủ xe và kỹ thuật viên              | Hiểu cảnh báo, đánh giá mức độ và mô tả đủ tình trạng      | Liên quan hệ sinh thái Vin; cần thu hẹp khỏi “xe có nhiều lỗi”             |
| 11 | Bùi Đức Thông      | Nối các ticket sự cố lặp lại trong khu đô thị                     | Cư dân và ban quản lý                | Mỗi phản ánh bị xử lý như ticket mới, thiếu lịch sử vấn đề | Workflow phù hợp; chưa có số liệu/ticket mẫu                               |
| 12 | Bùi Đức Thông      | Giải đáp tiện ích trong phòng khách sạn                           | Khách lưu trú và lễ tân              | Thông tin phí và cách sử dụng không rõ tại thời điểm cần   | Trải nghiệm thật; FAQ/rule có thể đủ                                       |
| 13 | Nguyễn Đức Danh    | Lựa chọn món ăn hoặc quán ăn mỗi ngày                             | Sinh viên/người trẻ ăn ngoài         | So sánh quá nhiều lựa chọn theo giá, vị trí, sở thích      | Tần suất và baseline rõ; ít liên quan bài toán doanh nghiệp nhóm muốn chọn |
| 14 | Nguyễn Đức Danh    | Theo dõi deadline và yêu cầu phân tán                             | Sinh viên/người đi làm               | Phải kiểm tra 5–6 nguồn mỗi ngày                           | Impact rõ; tích hợp và quyền riêng tư phức tạp                             |
| 15 | Nguyễn Đức Danh    | Hỗ trợ câu hỏi công nghệ lặp lại                                  | Người ít kinh nghiệm và người hỗ trợ | Mô tả thiếu bối cảnh, phải hỏi và hướng dẫn lại            | Dễ pilot; phạm vi câu hỏi cần thu hẹp                                      |
| 16 | Đinh Công Tú       | Dựng khung dự án GitHub mới                                       | Sinh viên/lập trình viên mới         | Chọn stack, cấu trúc và cấu hình lần chạy đầu              | Có baseline; template/script có thể đủ                                     |
| 17 | Đinh Công Tú       | Viết CV phù hợp JD nhưng vẫn có dấu ấn cá nhân                    | Ứng viên mới tốt nghiệp              | Nối tiêu chí JD với bằng chứng dự án và giọng cá nhân      | AI fit; tác động đến tỷ lệ được chọn chưa có bằng chứng                    |
| 18 | Đinh Công Tú       | Tìm lại tài liệu ôn chuyên môn phân tán                           | Ứng viên mới tốt nghiệp              | Tìm và chọn đúng tài liệu theo chủ đề                      | Có số liệu cá nhân; cách tổ chức file có thể giải phần lớn                 |


### 3.2. Gom trùng / cluster


| Cluster                               | Candidates included | Pattern chung                                                                 | Ghi chú                                                                       |
|---------------------------------------|---------------------|-------------------------------------------------------------------------------|-------------------------------------------------------------------------------|
| A — Phương tiện và vận hành vật lý    | 1, 2, 3, 10         | Kết hợp dữ liệu phương tiện với quyết định vận hành hoặc hỗ trợ               | Candidate 10 có actor trực tiếp và có thể giới hạn thành triage trước dịch vụ |
| B — Tìm kiếm và tổng hợp thông tin    | 4, 7, 8, 14, 18     | Tìm nội dung quan trọng trong nhiều nguồn rồi tóm tắt                         | AI fit cao nhưng có rủi ro quyền truy cập và dữ liệu nhạy cảm                 |
| C — Tiếp nhận, phân loại và chuẩn hóa | 5, 9, 11, 12, 15    | Chuyển đầu vào tự nhiên/không đồng nhất thành ticket hoặc dữ liệu có cấu trúc | Nhiều trường hợp có thể giải phần lớn bằng rule/FAQ                           |
| D — Tạo nội dung và hỗ trợ quyết định | 6, 13, 16, 17       | Thu thập tiêu chí rồi tạo hoặc đề xuất phương án                              | Dễ demo, cần chứng minh quality và lợi thế so với template/rule               |


### 3.3. Shortlist


| Candidate                                     | Vì sao vào shortlist                                                                                                                                                  | Rủi ro / điều chưa rõ                                                                                       |
|-----------------------------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------|-------------------------------------------------------------------------------------------------------------|
| Hỗ trợ chủ xe VinFast khi có cảnh báo/lỗi     | Actor và thời điểm kích hoạt rõ; có thể vẽ workflow từ cảnh báo đến tự xử lý/đặt dịch vụ/cứu hộ; so sánh Rule–Workflow–Agent tốt; phù hợp định hướng hệ sinh thái Vin | Chưa có baseline người dùng Việt Nam; giải pháp hiện hữu đã xử lý một phần; sai phân loại có rủi ro an toàn |
| Đối soát và quản lý hồ sơ phạt nguội          | Quy trình OCR → chuẩn hóa → đối chiếu → người duyệt rõ; KPI thời gian, độ chính xác và quá hạn đo được                                                                | Khó tiếp cận dữ liệu tài xế–xe–ca và thông báo vi phạm; MVP thiếu dữ liệu thật có thể chỉ là demo           |
| Nối các ticket sự cố lặp lại trong khu đô thị | Có thể giúp cư dân và ban quản lý nhận ra sự cố tái diễn; workflow ticket dễ mô hình hóa                                                                              | Chưa có ticket mẫu, baseline hoặc quyền truy cập hệ thống vận hành                                          |


### 3.4. Score để đồng thuận


Điểm dưới đây là bản tổng hợp sơ bộ theo dữ liệu nhóm đã cung cấp, cần được các thành viên xác nhận.


| Candidate                                 | Actor rõ | Workflow rõ | Pain có evidence | Impact đo được | Làm trong lab | So sánh R/W/A được | Nhóm hiểu domain |   Tổng |
|-------------------------------------------|---------:|------------:|-----------------:|---------------:|--------------:|-------------------:|-----------------:|-------:|
| Hỗ trợ chủ xe VinFast khi có cảnh báo/lỗi |        5 |           4 |                3 |              4 |             4 |                  5 |                4 | **29** |
| Đối soát hồ sơ phạt nguội                 |        4 |           5 |                2 |              5 |             3 |                  5 |                3 | **27** |
| Nối ticket sự cố lặp lại                  |        4 |           4 |                1 |              3 |             4 |                  5 |                3 | **24** |


**Candidate nhóm chọn:**


```text
Hỗ trợ chủ xe VinFast hiểu cảnh báo/lỗi, xác định hành động an toàn
và chuyển đủ dữ liệu cho kỹ thuật viên khi cần.
```


**Vì sao chọn:**


```text
Candidate có actor và trigger rõ: chủ xe vừa nhận cảnh báo hoặc nhận thấy
xe vận hành bất thường. Workflow có điểm nghẽn cụ thể ở việc biến mã lỗi,
triệu chứng và dữ liệu xe thành một hành động an toàn. Bài toán cho phép
so sánh rule phân loại lỗi, workflow AI có kiểm soát và agent tự hành.
Nhóm cũng có thể pilot bằng log đã ẩn danh và tình huống mô phỏng mà chưa
cần kết nối vào xe thật.
```


**Vì sao không chọn các candidate còn lại:**


```text
Đối soát phạt nguội có workflow và KPI tốt nhưng phụ thuộc dữ liệu nội bộ
về xe, tài xế, ca và bàn giao mà nhóm chưa chắc tiếp cận được.


Nối ticket sự cố lặp lại có thể làm MVP, nhưng nhóm chưa có ticket mẫu,
baseline hay người dùng vận hành để xác nhận pain và đánh giá kết quả.
```


**Disagreement:**


```text
Điểm tranh luận chính là “AI technician on-board” có đang nhảy quá sớm
sang Agent hay không. Nhóm tạm chốt giữ tên ý tưởng nhưng giới hạn thiết kế
thành workflow hỗ trợ: rule an toàn quyết định nhánh, AI giải thích và hỏi
thêm, còn chủ xe/kỹ thuật viên xác nhận hành động. AI không tự điều khiển xe,
xóa mã lỗi hoặc kết luận xe an toàn để tiếp tục di chuyển.
```


---


## Phase 4 — Quick Validation + Research


### 4.1. Quick validation


| Nguồn                           |                                  Số người / mẫu | Tín hiệu xác nhận                                                                                                        | Tín hiệu phản bác                                                                                                | Nhóm sửa problem thế nào                                                                                   |
|---------------------------------|------------------------------------------------:|--------------------------------------------------------------------------------------------------------------------------|------------------------------------------------------------------------------------------------------------------|------------------------------------------------------------------------------------------------------------|
| Quan sát ban đầu của thành viên |                                 Chưa có mẫu đếm | Thành viên đề xuất ghi nhận có phản ánh của người dùng trên mạng xã hội về lỗi phần cứng/phần mềm                        | Chưa có link, số lượng, tiêu chí chọn mẫu hoặc quote nên chưa thể dùng để kết luận “xe gặp nhiều lỗi”            | Bỏ claim về số lượng lỗi; chuyển trọng tâm sang workflow hỗ trợ khi cảnh báo/sự cố đã xuất hiện            |
| Báo cáo điều tra NHTSA PE24025  | 14 báo cáo VOQ về VF 8 đời 2023–2024 tại Hoa Kỳ | NHTSA ghi nhận các phản ánh về hệ thống hỗ trợ giữ làn kích hoạt sai hoặc tạo lực lái khó ghi đè                         | Chỉ là một hệ thống, một mẫu xe và thị trường Hoa Kỳ; không đại diện toàn bộ xe VinFast hoặc người dùng Việt Nam | Dùng như bằng chứng một loại sự cố có thật, không dùng để khái quát “nhiều lỗi”                            |
| Tài liệu/ứng dụng VinFast       |                  1 workflow sản phẩm chính thức | Ứng dụng có cảnh báo lỗi, đặt dịch vụ và hỗ trợ trên đường; cảnh báo được chia thành tự sửa, đặt dịch vụ hoặc cần hỗ trợ | Điều này cho thấy VinFast đã giải quyết đáng kể workflow mà nhóm tưởng còn trống                                 | Thu hẹp khoảng trống sang giải thích theo ngữ cảnh, thu thập thông tin và tạo handoff rõ cho kỹ thuật viên |
| Interview chủ xe                |                              **Chưa thực hiện** | Chưa có quote trực tiếp                                                                                                  | Chưa biết người dùng mất bao lâu, có hiểu cảnh báo không và bước nào đau nhất                                    | Bắt buộc phỏng vấn 2–3 chủ xe trước khi chốt baseline và triển khai trên xe thật                           |


Nguồn kiểm chứng công khai:


- [NHTSA — PE24025, 14 báo cáo về Lane Keep Assist trên VF 8](https://static.nhtsa.gov/odi/inv/2024/INOA-PE24025-19754.pdf)
- [NHTSA — đợt triệu hồi tự nguyện 6.314 VF 8 để cập nhật hiệu chỉnh phần mềm ADAS](https://static.nhtsa.gov/odi/rcl/2025/RCLRPT-25V559-3549.pdf)
- [VinFast — hướng dẫn tiện ích dịch vụ và ba nhóm cảnh báo lỗi](https://vinfastauto.com/vn_vi/huong-dan-su-dung-tien-ich-dich-vu-tren-ung-dung-vinfast)


> Hai nguồn NHTSA áp dụng cho VF 8 tại Hoa Kỳ. Chúng xác nhận các trường hợp cụ thể, không chứng minh tần suất lỗi ở
> Việt Nam.


**Insight sau validation:**


```text
Pain chưa được chứng minh là “xe VinFast có nhiều lỗi”. Pain hợp lý hơn để
kiểm chứng là: khi một cảnh báo hoặc bất thường xuất hiện, chủ xe có hiểu
được mức độ, biết hành động an toàn và chuyển đủ bối cảnh cho kỹ thuật viên
hay không. Tài liệu chính thức cho thấy workflow này đã được hỗ trợ một phần,
vì vậy nhóm phải đo khoảng trống còn lại thay vì xây lại toàn bộ hệ thống.
```


### 4.2. Research giải pháp đã có


| Nguồn / tool / case                        | Link                                                                                                       | Họ giải quyết bước nào?                                                                                          | Điểm mạnh                                                    | Khoảng trống / rủi ro                                                                   | Bài học cho nhóm                                                                          |
|--------------------------------------------|------------------------------------------------------------------------------------------------------------|------------------------------------------------------------------------------------------------------------------|--------------------------------------------------------------|-----------------------------------------------------------------------------------------|-------------------------------------------------------------------------------------------|
| Ứng dụng VinFast — dịch vụ và cảnh báo lỗi | [Nguồn chính thức](https://vinfastauto.com/vn_vi/huong-dan-su-dung-tien-ich-dich-vu-tren-ung-dung-vinfast) | Nhận cảnh báo; phân nhóm tự sửa/đặt dịch vụ/hỗ trợ trên đường; đặt và theo dõi dịch vụ                           | Đã nối cảnh báo với hành động và hệ thống dịch vụ            | Chưa có bằng chứng công khai về mức người dùng hiểu cảnh báo hoặc số lần phải mô tả lại | Không xây app cảnh báo mới; tập trung vào lớp giải thích và handoff có cấu trúc           |
| Chẩn đoán và chăm sóc từ xa VF e34         | [Nguồn chính thức](https://vinfastauto.com/vn_vi/tinh-nang-moi-cham-soc-khach-hang-tu-dong-vf-e34)         | Đọc mã lỗi; sửa lỗi phần mềm từ xa; hướng dẫn lỗi cơ bản; gọi cứu hộ/đặt xưởng                                   | Tận dụng dữ liệu xe và phân nhánh theo mức nghiêm trọng      | Mô tả theo một mẫu xe; cần kiểm tra khả năng áp dụng cho từng model và phiên bản        | Phải tích hợp với hệ thống hiện hữu, không giả định mọi xe có cùng dữ liệu/quyền truy cập |
| Tài liệu hướng dẫn theo dòng xe VinFast    | [Nguồn chính thức](https://vinfastauto.com/vn_vi/tai-lieu-o-to)                                            | Cung cấp nội dung vận hành và xử lý theo mẫu xe                                                                  | Nguồn được hãng kiểm soát, phù hợp để truy xuất có dẫn nguồn | Tài liệu dài; phiên bản/model khác nhau; AI có thể lấy nhầm hướng dẫn                   | Kho tri thức phải version theo model, năm xe và software version                          |
| Tesla Service workflow                     | [Tesla Support](https://www.tesla.com/support/service-visits)                                              | Người dùng chọn chủ đề, mô tả concern, bổ sung ảnh; hệ thống chẩn đoán rồi đưa troubleshooting hoặc lịch dịch vụ | Pattern rõ cho triage → chẩn đoán → hành động → handoff      | Không thể sao chép nguyên trạng; dữ liệu, kiến trúc xe và chính sách khác VinFast       | Mẫu tham khảo tốt cho structured intake và technician handoff                             |


**Research takeaway:**


```text
Không nên xây một Agent tự chủ xử lý toàn bộ xe vì VinFast đã có cảnh báo,
chẩn đoán từ xa và workflow dịch vụ. MVP phù hợp hơn là lớp AI hội thoại
có truy xuất tài liệu đúng phiên bản, nằm sau rule an toàn và trước bước
người dùng/kỹ thuật viên xác nhận. Giá trị cần chứng minh là giảm thời gian
hiểu cảnh báo và giảm số lượt hỏi lại, không phải “AI sửa được mọi lỗi”.
```


---


## Phase 5 — Workflow + Problem Statement


### 5.1. Current workflow bản nhóm


```text
[1 Xe phát cảnh báo/người dùng thấy bất thường]
→ [2 Xem HMI/app]
→ [3 Tự diễn giải mã lỗi hoặc tra manual/web]  <-- bottleneck giả thuyết
→ [4 Thử xử lý hoặc chọn đặt dịch vụ/cứu hộ]
→ [5 Mô tả lại tình trạng cho hỗ trợ]
→ [6 Kỹ thuật viên hỏi thêm, chẩn đoán và quyết định]
```


| Bước | Actor         | Input                                     | Output                                | Thời gian / tần suất | Ghi chú                                                       |
|-----:|---------------|-------------------------------------------|---------------------------------------|----------------------|---------------------------------------------------------------|
|    1 | Xe / chủ xe   | Mã cảnh báo, âm thanh, hành vi bất thường | Tín hiệu sự cố                        | Chưa đo              | Trigger; có thể là lỗi thật hoặc cảnh báo điều kiện           |
|    2 | Chủ xe        | HMI hoặc thông báo ứng dụng               | Thông tin lỗi ban đầu                 | Chưa đo              | Một phần đã được VinFast hỗ trợ                               |
|    3 | Chủ xe        | Mã lỗi, manual, web, kinh nghiệm          | Cách hiểu sơ bộ                       | Chưa đo              | **Bottleneck giả thuyết:** nguồn phân tán, thuật ngữ kỹ thuật |
|    4 | Chủ xe        | Cách hiểu sơ bộ                           | Tự xử lý, đặt dịch vụ hoặc gọi cứu hộ | Chưa đo              | Quyết định có yếu tố an toàn                                  |
|    5 | Chủ xe / CSKH | Triệu chứng, ảnh, vị trí, lịch sử         | Yêu cầu hỗ trợ                        | Chưa đo              | Có thể phải mô tả lại hoặc bổ sung                            |
|    6 | Kỹ thuật viên | Log xe và mô tả người dùng                | Chẩn đoán/hướng xử lý                 | Chưa đo              | Human owner cho quyết định kỹ thuật                           |


**Bottleneck chính:**


```text
Bottleneck giả thuyết nằm giữa lúc nhận cảnh báo và lúc chọn được hành động
an toàn: người dùng phải nối mã lỗi, biểu hiện thực tế, manual và hướng dẫn
dịch vụ. Tuy nhiên nhóm chưa có phỏng vấn/time log để biết bước này mất bao
lâu hoặc liệu app hiện tại đã giải quyết đủ với đa số người dùng hay chưa.
```


### 5.2. Future workflow bản nhóm


```text
[1 Đọc mã lỗi + dữ liệu xe - machine, read-only]
→ [2 Rule an toàn phân nhóm khẩn cấp/dịch vụ/tự kiểm tra]
→ [3 Truy xuất manual đúng model/version]
→ [4 AI giải thích + hỏi thêm dữ kiện không nguy hiểm]
→ [5 Chủ xe xác nhận hành động]  <-- human boundary
→ [6 Tạo gói dữ liệu + chuyển kỹ thuật viên/cứu hộ nếu cần]


Fallback: thiếu dữ liệu, confidence thấp, cảnh báo an toàn hoặc nguồn mâu thuẫn
→ dừng hướng dẫn tự xử lý và chuyển ngay sang CSKH/kỹ thuật viên/cứu hộ.
```


**Before/after impact:**


| Metric                                           |                     Trước |                                                         Sau kỳ vọng | Cách đo                                                 |
|--------------------------------------------------|--------------------------:|--------------------------------------------------------------------:|---------------------------------------------------------|
| Tổng thời gian từ cảnh báo đến hành động phù hợp |          Chưa có baseline |                                     Giảm ≥50% so với baseline pilot | Timestamp cảnh báo → người dùng xác nhận hành động đúng |
| Số bước                                          |                         6 |                               6 bước nhưng giảm tìm kiếm và hỏi lại | Log workflow                                            |
| Số bước chủ xe phải tự tìm/diễn giải             |                Khoảng 3/6 |                                    Tối đa 1/6: kiểm tra và xác nhận | Quan sát task test                                      |
| Số lượt kỹ thuật viên hỏi bổ sung                |          Chưa có baseline |                                                           Giảm ≥50% | Đếm message/call bổ sung trên mỗi case                  |
| Độ chính xác phân luồng                          |                   Chưa đo |        ≥95% trên bộ case; 100% case safety-critical không bị hạ mức | So với nhãn của kỹ thuật viên                           |
| Risk mới                                         | Không có AI sinh nội dung | AI giải thích sai, trấn an sai, lộ dữ liệu xe hoặc gọi nhầm dịch vụ | Red-team, audit log, consent và safety gate             |


### 5.3. Problem Statement v0


| Field              | Nội dung                                                                                                                                                                                    |
|--------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **Actor**          | Chủ xe VinFast vừa nhận cảnh báo trên xe/app hoặc nhận thấy xe vận hành bất thường; kỹ thuật viên tiếp nhận là actor thứ hai.                                                               |
| **Workflow**       | Chủ xe xem cảnh báo, tự tra manual/web, quyết định tự xử lý hay liên hệ hỗ trợ, mô tả tình trạng; kỹ thuật viên hỏi thêm và chẩn đoán.                                                      |
| **Bottleneck**     | Chủ xe khó chuyển mã lỗi và triệu chứng thành cách hiểu đủ rõ để chọn hành động an toàn; thông tin chuyển cho kỹ thuật viên có thể thiếu hoặc lặp lại. Đây vẫn là giả thuyết cần interview. |
| **Impact**         | Làm gián đoạn hành trình và kéo dài thời gian hỗ trợ. Chưa có baseline về phút/case hoặc số lượt hỏi lại nên chưa được phép khẳng định mức tiết kiệm.                                       |
| **Success Metric** | Giảm ≥50% thời gian từ cảnh báo đến hành động đúng; giảm ≥50% lượt hỏi bổ sung; ≥95% phân luồng đúng và không hạ mức bất kỳ case safety-critical nào trong bộ test.                         |
| **Boundary**       | Chỉ giải thích, hướng dẫn kiểm tra ít rủi ro và chuẩn bị handoff. Không điều khiển xe, xóa mã lỗi, sửa phần cứng, tự kết luận xe an toàn hoặc tự gọi dịch vụ khi chưa có xác nhận.          |


**AI phản biện v0:**


- Field mơ hồ: “xe gặp nhiều lỗi”, “mất nhiều thời gian” và “AI technician” ban đầu đều là claim/solution chưa có
 baseline. Phạm vi phần cứng và phần mềm quá rộng.
- Nhóm sửa: đổi problem sang hành trình xử lý cảnh báo; ghi rõ dữ liệu còn thiếu; giới hạn AI vào giải thích và handoff;
 dùng rule an toàn và kỹ thuật viên làm boundary.


---


## Phase 6 — Rule / Workflow / Agent + Decision


### 6.0. Ma trận độ phù hợp


- Độ mơ hồ: [ ] Thấp / [x] Cao — Người dùng có thể mô tả cùng một hiện tượng theo nhiều cách; một triệu chứng có thể đến
 từ nhiều nguyên nhân.
- Độ phức tạp: [ ] Thấp / [x] Cao — Cần kết hợp mã lỗi, sensor/log, model, software version, manual, lịch sử dịch vụ và
 mức độ an toàn.


**Bài toán nhóm nằm ở ô:**


```text
Độ mơ hồ cao × độ phức tạp cao, nhưng thuộc miền safety-critical nên không
suy ra rằng Agent tự chủ là lựa chọn phù hợp. Quyền hành động phải bị giới
hạn bởi rule an toàn và xác nhận của con người.
```


### 6.1. So sánh Rule / Workflow / Agent


| Mức          | Phương án cho bài toán nhóm                                                                                       | Khi nào đủ                                                                        | Rủi ro                                                                | Chọn?                                      |
|--------------|-------------------------------------------------------------------------------------------------------------------|-----------------------------------------------------------------------------------|-----------------------------------------------------------------------|--------------------------------------------|
| **Rule**     | Ánh xạ mã lỗi và severity sang ba nhánh: dừng xe/gọi cứu hộ, đặt dịch vụ, hướng dẫn kiểm tra đơn giản             | Đủ với mã lỗi chuẩn, ngưỡng an toàn rõ và hướng dẫn cố định                       | Không hiểu mô tả tự nhiên hoặc kết hợp nhiều tín hiệu mơ hồ           | Có, làm safety gate và xử lý case xác định |
| **Workflow** | Rule an toàn → truy xuất manual đúng phiên bản → AI giải thích/hỏi thêm → chủ xe xác nhận → handoff kỹ thuật viên | Phù hợp khi đường đi được kiểm soát nhưng cần AI xử lý ngôn ngữ và tổng hợp       | AI có thể lấy sai nguồn hoặc suy diễn nguyên nhân                     | **Chọn cho MVP**                           |
| **Agent**    | Tự đọc dữ liệu xe, lập kế hoạch chẩn đoán, thực hiện thao tác từ xa và tự gọi dịch vụ                             | Chỉ cân nhắc sau khi có quyền truy cập, đánh giá an toàn và cơ chế phê duyệt chặt | Hành động sai có thể ảnh hưởng an toàn, quyền riêng tư và vận hành xe | Chưa chọn                                  |


**5 câu hỏi chốt:**


1. Rule chưa được chứng minh giải 70–80% case; rule có thể xử lý severity và mã lỗi chuẩn nhưng không đủ cho mô tả tự
  nhiên hoặc nhiều tín hiệu kết hợp.
2. Workflow có các nhánh rõ theo mức độ: khẩn cấp, cần dịch vụ hoặc có thể kiểm tra đơn giản; nhánh phải do rule an toàn
  và dữ liệu hãng kiểm soát.
3. MVP chưa cần Agent tự lập kế hoạch hoặc tự điều khiển công cụ trên xe. AI chỉ cần truy xuất, giải thích và chuẩn hóa
  handoff.
4. Chủ xe phát hiện câu trả lời không khớp triệu chứng; kỹ thuật viên là người kiểm tra cuối. Case confidence thấp hoặc
  safety-critical phải chuyển ngay, không chờ AI thử lại.
5. Có thể hạ từ Agent xuống Workflow; bên trong Workflow tiếp tục dùng Rule cho các quyết định an toàn xác định.


**Mức chọn:**


```text
Workflow — rule an toàn + AI giải thích có nguồn + chủ xe/kỹ thuật viên xác nhận.
```


**Vì sao chọn:**


```text
Quy trình có đường đi và nhánh rõ, nên chưa cần Agent tự lập kế hoạch.
Rule phù hợp để khóa các quyết định safety-critical; AI chỉ xử lý phần ngôn
ngữ, liên kết dữ liệu và giải thích theo ngữ cảnh. Chủ xe xác nhận trước khi
gọi hỗ trợ và kỹ thuật viên giữ quyền kết luận kỹ thuật cuối cùng.
```


**Vì sao không chỉ chọn Rule:**


```text
Rule xử lý tốt mã lỗi đã biết nhưng khó hiểu mô tả tự nhiên, triệu chứng
mơ hồ và câu hỏi tiếp nối của người dùng. Tuy vậy, nếu pilot cho thấy rule
và hướng dẫn hiện có đã giải quyết phần lớn case, nhóm sẽ không thêm AI.
```


### 6.2. Problem Statement v1


| Field                            | Nội dung                                                                                                                                                                                                                             |
|----------------------------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **Actor**                        | Chủ xe VinFast nhận cảnh báo trên HMI/app hoặc thấy xe vận hành bất thường; kỹ thuật viên/CSKH tiếp nhận yêu cầu là actor thứ hai.                                                                                                   |
| **Workflow**                     | Nhận cảnh báo → xem app/HMI → tra hướng dẫn → chọn tự kiểm tra/đặt dịch vụ/cứu hộ → mô tả vấn đề → kỹ thuật viên chẩn đoán.                                                                                                          |
| **Bottleneck**                   | Chủ xe khó kết hợp mã lỗi, triệu chứng và hướng dẫn đúng model/version để chọn hành động an toàn; handoff có thể thiếu bối cảnh khiến kỹ thuật viên phải hỏi thêm.                                                                   |
| **Impact**                       | Hành trình bị gián đoạn và thời gian hỗ trợ kéo dài; baseline phút/case và lượt hỏi lại chưa được đo với chủ xe Việt Nam.                                                                                                            |
| **Success Metric**               | Sau khi có baseline: giảm ≥50% thời gian đến hành động đúng; giảm ≥50% lượt hỏi lại; ≥95% routing accuracy; không hạ mức case safety-critical; đo CSAT sau mỗi phiên.                                                                |
| **Boundary**                     | Làm: truy xuất dữ liệu read-only sau consent, giải thích có nguồn, hướng dẫn bước ít rủi ro, tạo handoff. Không làm: điều khiển xe, xóa lỗi, can thiệp hệ thống, tự kết luận an toàn hoặc tự đặt/gọi dịch vụ khi chưa được xác nhận. |
| **AI intervention point**        | Sau khi rule đọc mã lỗi và phân loại severity, trước khi chủ xe chọn hành động hoặc chuyển yêu cầu cho kỹ thuật viên.                                                                                                                |
| **Mức chọn**                     | Workflow: rule khóa an toàn, AI giải thích/hỏi thêm, con người xác nhận.                                                                                                                                                             |
| **Rủi ro & người thật kiểm tra** | Rủi ro lớn nhất là trấn an sai hoặc hướng dẫn sai. Kỹ thuật viên VinFast gán nhãn bộ case, duyệt nội dung và kiểm tra toàn bộ case phức tạp; chủ xe xác nhận trước mọi handoff/action.                                               |


### 6.3. Final decision


| Câu hỏi                               | Yes / Not Yet / No | Ghi chú                                                                                         |
|---------------------------------------|--------------------|-------------------------------------------------------------------------------------------------|
| Actor + workflow rõ chưa?             | Yes                | Chủ xe và kỹ thuật viên, trigger và sáu bước đã được mô tả.                                     |
| Baseline + metric đo được chưa?       | Not Yet            | Metric đã định nghĩa nhưng chưa có thời gian/case, lượt hỏi lại và CSAT hiện tại.               |
| Data/input đủ dùng chưa?              | Not Yet            | Cần log đã ẩn danh, model/software version, manual version và nhãn kỹ thuật viên.               |
| AI sai, hậu quả chấp nhận được không? | Not Yet            | Chỉ chấp nhận khi MVP read-only, rule an toàn chặn case nguy hiểm và có human review.           |
| Có người review/owner không?          | Not Yet            | Đã xác định cần kỹ thuật viên VinFast nhưng chưa có owner cam kết tham gia pilot.               |
| Có cách non-AI đơn giản hơn không?    | Yes                | Cải thiện thông báo, decision tree, FAQ và form tiếp nhận có cấu trúc có thể giải một phần lớn. |


**Decision:**


```text
NOT YET cho triển khai AI Technician trực tiếp trên xe.
GO cho prototype offline, read-only để kiểm chứng pain và routing.
```


**Lý do:**


```text
Problem và workflow đã rõ hơn, nhưng nhóm chưa có interview chủ xe, baseline
thời gian, log được phép sử dụng hoặc kỹ thuật viên chịu trách nhiệm đánh giá.
Research còn cho thấy ứng dụng VinFast đã có cảnh báo, chẩn đoán và phân nhánh
xử lý, nên khoảng trống thực tế phải được kiểm chứng. Prototype offline có
rủi ro thấp và đủ để so Rule với Workflow trước khi đề xuất tích hợp on-board.
```


**Nếu Go — pilot nhỏ nhất:**


```text
1. Phỏng vấn 3 chủ xe và 2 kỹ thuật viên; đo thời gian, số nguồn phải tra,
  số lượt hỏi lại và lỗi hiểu cảnh báo.
2. Chuẩn bị 20 case đã ẩn danh, gồm mã lỗi, model/version, triệu chứng,
  manual tương ứng và nhãn hành động do kỹ thuật viên xác nhận.
3. So ba phương án: manual hiện tại, decision tree bằng rule, và workflow
  rule + AI. Không kết nối điều khiển xe và không dùng dữ liệu trực tiếp.
4. Đo: thời gian đến hành động đúng, routing accuracy, số case safety-critical
  bị hạ mức, số lượt hỏi bổ sung và CSAT.
```


**Nếu Not Yet — cần validate:**


```text
Xác nhận người dùng còn gặp pain sau khi đã dùng chức năng cảnh báo hiện tại;
lấy baseline từ ít nhất 3 chủ xe; xác định phạm vi model/phiên bản; xin quyền
dùng log đã ẩn danh; có kỹ thuật viên gán nhãn và duyệt safety policy.
```


**Nếu No-Go — làm gì thay AI:**


```text
Nếu pilot cho thấy AI không cải thiện thời gian/độ chính xác hoặc tạo thêm
rủi ro an toàn, nhóm đề xuất cải thiện giải pháp không dùng AI: chuẩn hóa
thông báo lỗi bằng ngôn ngữ dễ hiểu; xây decision tree theo mã lỗi và mức độ;
hiển thị checklist thông tin cần cung cấp; tự động đính kèm mã lỗi, model,
software version và log được phép chia sẻ vào yêu cầu dịch vụ; bổ sung nút
đặt dịch vụ/cứu hộ theo rule. Kỹ thuật viên tiếp tục chẩn đoán và quyết định.
```


**Exit / rollback:**


```text
Dừng AI và quay về cảnh báo + decision tree + CSKH nếu có bất kỳ case
safety-critical nào bị hạ mức; routing accuracy dưới 95%; câu trả lời không
có nguồn đúng model/version; AI làm tăng thời gian; hoặc kỹ thuật viên không
chấp nhận chất lượng handoff. Không triển khai on-board khi chưa vượt toàn bộ
safety gate trong môi trường offline.
```


---


### Self-check nộp phần 02


- [x] Có nhật ký hội tụ 18 → 1, gồm cluster, shortlist và score sơ bộ.
- [ ] Có interview 2–3 chủ xe với quote thật; hiện mới có public record và research.
- [x] Có research 3+ giải pháp/pattern và link kiểm được.
- [x] Có workflow trước/sau, handoff, bottleneck, boundary và fallback.
- [x] Có PS v0 → v1, metric trước/sau và cách đo; baseline chưa có được ghi rõ.
- [x] Có so sánh Rule/Workflow/Agent và quyết định Not Yet có lý do.



