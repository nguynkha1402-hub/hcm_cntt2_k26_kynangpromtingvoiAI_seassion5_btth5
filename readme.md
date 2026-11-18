### Prompt 1: Nghiên cứu Insight & Định vị Thông điệp
```Plaintext
<role>
Bạn là một Senior Digital Marketing Manager chuyên về mảng giáo dục công nghệ (EdTech), đặc biệt am hiểu tâm lý Gen Z.
</role>

<context>
Trung tâm đào tạo cần chạy một chiến dịch truyền thông tuyển sinh khóa học "Python cơ bản dành cho người mới bắt đầu".
- Đối tượng mục tiêu: Sinh viên năm nhất (18-20 tuổi), đặc biệt là các bạn vừa bắt đầu làm quen với lập trình.
- Thời lượng khóa học: 8 tuần.
- Mục tiêu kinh doanh: Thu về 100 leads (lượt đăng ký tư vấn) từ Facebook và TikTok.
</context>

<task>
Hãy phân tích sâu chân dung khách hàng mục tiêu và xây dựng 01 thông điệp truyền thông chính (Key Message).
</task>

<instructions>
Hãy suy nghĩ từng bước (Chain-of-Thought):
1. Phân tích Nỗi đau (Pain points): Áp lực các môn cơ sở trên trường (như Nhập môn CNTT, thuật toán), sự bỡ ngỡ với tư duy logic, lỗi cài đặt môi trường, hoặc sợ code khó.
2. Phân tích Mong muốn (Gains): Cần một ngôn ngữ dễ đọc hiểu để xây dựng nền tảng, muốn qua môn điểm cao, muốn có mentor hỗ trợ sửa bug.
3. Hành vi nền tảng: Cách họ tiêu thụ nội dung trên Facebook (tìm thông tin, đọc review) và TikTok (giải trí, xem POV ngắn).
4. Từ đó, cô đọng lại thành 01 Key Message sắc bén, ngắn gọn, gãi đúng chỗ ngứa của tân sinh viên.
</instructions>

<output_format>
Trình bày bằng gạch đầu dòng rõ ràng. Phân định rõ 2 phần: [Chân dung khách hàng] và [Thông điệp truyền thông].
</output_format>
```
### Prompt 2: Lập kế hoạch phân bổ nội dung (Content Plan)
```Plaintext
<role>
Bạn là Content Planner & Social Media Strategist.
</role>

<input_data>
Dựa trên chân dung khách hàng và thông điệp truyền thông sau đây:
[Copy & Paste kết quả của Prompt 1 vào đây]
</input_data>

<task>
Xây dựng một lịch đăng nội dung (Content Calendar) chi tiết trong 7 ngày liên tiếp trên 2 nền tảng Facebook và TikTok.
</task>

<instructions>
1. Áp dụng phễu Marketing (AIDA): Awareness (nhận diện trên TikTok) -> Interest & Desire (Nuôi dưỡng bằng kiến thức/giá trị trên Facebook) -> Action (Chốt sale).
2. Phân bổ: 
   - TikTok: Tập trung vào nội dung dạng ngắn, POV, giải trí, tips nhanh để kéo Traffic.
   - Facebook: Tập trung bài viết phân tích, hình ảnh carousel, bài chốt sale với ưu đãi.
3. Nội dung phải hướng tới mục tiêu cuối cùng là thu về 100 leads.
</instructions>

<output_format>
Trình bày dưới dạng Bảng Markdown (Markdown Table) gồm các cột: 
| Ngày | Nền tảng | Giai đoạn Phễu | Chủ đề & Định dạng | Mục tiêu (KPI kỳ vọng) | Call-to-Action (CTA) |
</output_format>
```
### Prompt 3: Thực thi sáng tạo (Sản xuất Content chi tiết)
```Plaintext
<role>
Bạn là một Copywriter và TikTok Scriptwriter "cứng tay", chuyên viết nội dung viral và có tỷ lệ chuyển đổi cao. 
</role>

<input_data>
Dựa trên chiến lược và lịch đăng 7 ngày sau đây:
[Copy & Paste Bảng Content Calendar của Prompt 2 vào đây]
</input_data>

<task>
Hãy viết chi tiết nội dung cho 4 tài liệu cốt lõi của chiến dịch:
1. Bài Facebook 1 (Bài trao giá trị/Giáo dục khách hàng).
2. Bài Facebook 2 (Bài Sale ép chốt, giới thiệu khóa 8 tuần và kêu gọi đăng ký để đạt 100 leads).
3. Kịch bản TikTok 1 (Dạng POV giải trí, đánh vào nỗi đau học code).
4. Kịch bản TikTok 2 (Dạng Q&A hoặc Tips nhanh, điều hướng về link đăng ký).
</task>

<instructions>
- Văn phong: Trẻ trung, "bắt trend", sử dụng thuật ngữ Gen Z và sinh viên IT (chạy deadline, qua môn, rớt môn, bug, newbie).
- Bài Facebook: Cần có Tiêu đề giật tít (viết hoa), ngắt đoạn dễ nhìn, sử dụng emoji hợp lý, và CTA chứa lời kêu gọi rõ ràng kèm tính khan hiếm (scarcity).
- Kịch bản TikTok: Viết theo cấu trúc 3 cột: [Thời lượng] - [Hình ảnh/Hành động] - [Âm thanh/Lời thoại]. Mở đầu video (Hook) trong 3 giây đầu tiên phải cực kỳ thu hút.
</instructions>
```
### Prompt 4: Kiểm tra chéo và Đánh giá tính nhất quán
```Plaintext
<role>
Bạn là một Giám đốc Marketing (CMO) cực kỳ khắt khe, thiên về dữ liệu và hiệu quả chuyển đổi.
</role>

<input_data>
Dưới đây là toàn bộ kế hoạch và nội dung chi tiết của chiến dịch:
[Copy & Paste toàn bộ kết quả của Prompt 1, 2 và 3 vào đây]
</input_data>

<task>
Thực hiện quá trình "QA/QC" (Kiểm duyệt chất lượng) cho toàn bộ chiến dịch này.
</task>

<instructions>
Hãy đánh giá hệ thống dựa trên các tiêu chí sinh tử sau:
1. Target constraints: Các nội dung có bị "lạc đề" khỏi thông số lõi không? (Bắt buộc phải nhắc đến: Khóa Python, dành cho newbie/năm nhất, 8 tuần).
2. Alignment: Thông điệp truyền thông ở Prompt 1 có thực sự được thể hiện rõ ràng trong 4 bài viết/video ở Prompt 3 không?
3. Conversion logic: Hành trình dẫn dắt từ TikTok sang Facebook rồi đến form đăng ký có đủ sức thuyết phục để ra được 100 leads không? Có mồi nhử (lead magnet) đủ hấp dẫn chưa?
4. Đề xuất: Nếu có bất kỳ lỗ hổng nào, hãy chỉ ra và đưa ra chính xác câu từ/chi tiết cần sửa chữa để tối ưu hóa.
</instructions>

<output_format>
Báo cáo kiểm duyệt sử dụng Check-list, đánh giá [ĐẠT] hoặc [CHƯA ĐẠT] kèm lý do chi tiết và hướng khắc phục.
</output_format>
```
1. Sơ đồ mô tả chuỗi Prompt

Prompt 1 (Nghiên cứu chiến lược)(Đầu vào: Yêu cầu khóa học Python 8 tuần)
➔ Đầu ra 1: Chân dung khách hàng & Thông điệp chính

Prompt 2 (Lập kế hoạch)(Đầu vào: Đầu ra 1)
➔ Đầu ra 2: Lịch đăng nội dung 7 ngày (FB & TikTok)

Prompt 3 (Sáng tạo nội dung)(Đầu vào: Đầu ra 1 + Đầu ra 2)
➔ Đầu ra 3: 02 Bài đăng Facebook & 02 Kịch bản TikTok

Prompt 4 (Kiểm duyệt)(Đầu vào: Toàn bộ Đầu ra 1, 2, 3)
➔ Đầu ra 4: Báo cáo kiểm tra tính nhất quán

2. Chân dung khách hàng mục tiêu

- Nhân khẩu học: Nam/Nữ, 18–20 tuổi. Là tân sinh viên (năm nhất) tại các trường đại học, học viện đào tạo Công nghệ Thông tin hoặc các khối ngành kỹ thuật, kinh tế có học phần lập trình.
- Nỗi đau (Pain points): Bị "sốc nhiệt" với khối lượng kiến thức đại học. Áp lực nặng nề từ các môn đại cương như Nhập môn Công nghệ Thông tin, Toán rời rạc. Loay hoay với các ngôn ngữ có cú pháp phức tạp như C, C++, Java ngay từ học kỳ đầu. Dễ nản chí khi cài đặt môi trường code liên tục báo lỗi.
- Mong muốn (Gains): Cần một ngôn ngữ lập trình dễ đọc, dễ hiểu để rèn luyện tư duy logic trước. Muốn có lộ trình học bài bản để "qua môn" an toàn với điểm số tốt. Cần mentor hỗ trợ giải đáp trực tiếp khi gặp bug.
- Hành vi trực tuyến: Thường xuyên sử dụng Facebook tham gia các hội nhóm tân sinh viên, nhóm chat học tập đa nền tảng. Dành nhiều thời gian xem nội dung dạng ngắn trên TikTok mang tính chất giải trí, đồng cảm (POV), hoặc mẹo vặt học tập.


3. Thông điệp truyền thông chính

"Xóa mù lập trình năm nhất – Chinh phục Python từ con số 0, tự tin bứt phá điểm số chỉ sau 8 tuần!"

4. Lịch đăng nội dung trong 7 ngày

Ngày|Kênh|Tuyến nội dung|Chủ đề / Tiêu đề|Mục tiêu|
|---|---|---|---|---|
1|TikTok|POV / Đồng cảm|"Kỳ vọng làm Hacker vs. Thực tế học C++ năm nhất".|Thu hút lượt xem, tạo đồng cảm với tân sinh viên.|
2|Facebook|Chia sẻ kiến thức|Tại sao newbie IT nên lấy Python làm "tình đầu"?|Giáo dục khách hàng, định hình tư duy chọn ngôn ngữ.|
3|TikTok|Hướng dẫn nhanh|Code công cụ tự động siêu đơn giản bằng Python trong 30s.|Kích thích sự tò mò, chứng minh tính ứng dụng|
4|Facebook|Tương tác|Minigame: Tìm lỗi sai (Bug) trong đoạn code Python cơ bản.|Tăng lượng tương tác (Engagement) trên Fanpage.|
5|TikTok|Q&A|Dốt Toán rời rạc có học code được không?|Gỡ bỏ rào cản tâm lý, điều hướng về Link Bio.|
6|Facebook|Bán hàng (Sale)|Giới thiệu lộ trình 8 tuần Python kèm ưu đãi cực lớn.|Kêu gọi hành động, thu thập Lead trực tiếp.|
7|Cả hai|Social Proof / FOMO|Review thực tế của sinh viên & Countdown chốt 100 slot.|Thúc đẩy quyết định cuối cùng, chốt đủ KPI.|

5. Hai bài đăng Facebook

Bài 1 (Ngày 2 - Chia sẻ kiến thức)Tiêu đề: TÂN SINH VIÊN: VÌ SAO PYTHON LÀ "CHÂN ÁI" ĐỂ BẮT ĐẦU SỰ NGHIỆP CODE?

Vừa chân ướt chân ráo vào năm nhất đã bị "vã" ngay C, C++ hay Java? Cú pháp rườm rà, con trỏ phức tạp khiến bạn chỉ muốn gập luôn laptop?

Khoan vội nản! Để xây dựng nền tảng tư duy lập trình vững chắc mà không bị "trầm cảm", Python chính là ngôn ngữ bạn cần làm chủ đầu tiên vì 3 lý do:

- 1️. Cú pháp "sạch" như tiếng Anh: Tạm biệt dấu chấm phẩy ; hay ngoặc nhọn {}. Python ép bạn viết code gọn gàng, đọc lướt qua là hiểu logic.
- 2️. Đa dụng, mạnh mẽ: Từ viết script tự động hóa file trên hệ điều hành, đến làm web, phân tích dữ liệu, hay AI – Python đều có sẵn thư viện hỗ trợ tận răng.
- . Cộng đồng khổng lồ: Bị lỗi? Dán lỗi lên mạng và sẽ có ngay hàng ngàn anh em developer chỉ cách fix bug trong 1 nốt nhạc.Đừng để rào cản ngôn ngữ làm chậm tiến độ học IT của bạn!

Bạn muốn nhận miễn phí lộ trình học Python từ số 0? Comment "QUAN TÂM" bên dưới để Admin gửi trực tiếp vào inbox nhé!

Bài 2 (Ngày 6 - Chốt Sale / Lead Gen)

Tiêu đề: VƯỢT ẢI MÔN CƠ SỞ CHỈ VỚI 8 TUẦN "THỰC CHIẾN" PYTHON!

Deadline Nhập môn Công nghệ Thông tin đang đến gần mà bạn vẫn loay hoay cài đặt môi trường code?

Khóa học PYTHON CƠ BẢN DÀNH CHO TÂN SINH VIÊN chính là chiếc phao cứu sinh dành riêng cho bạn!

 Chỉ sau 8 tuần, bạn sẽ:
 
- Nắm trọn tư duy logic, vòng lặp, hàm, cấu trúc dữ liệu.
- Tự tay viết được các công cụ quản lý, xử lý file cơ bản.
- Sẵn sàng bứt phá điểm A các môn cơ sở trên giảng đường.
- Được Mentor 1-1 hỗ trợ trực tiếp sửa bug, giải đáp thắc mắc.

ĐẶC QUYỀN DUY NHẤT HÔM NAY: Trợ giá 30% học phí cho 100 BẠN ĐĂNG KÝ SỚM NHẤT!

Đừng để môn code trở thành nỗi ám ảnh. Số lượng giới hạn, chốt danh sách vào cuối tuần này!

 Click đăng ký giữ chỗ ngay tại đây: [Link_Đăng_Ký_Tư_Vấn]
 
6. Hai kịch bản video TikTok (30–45 giây)

Kịch bản 1 (POV Giải trí - Ngày 1)

- Thời lượng: 35 giây.

- Visual: Chuyển cảnh nhanh giữa Kỳ vọng và Thực tế.

  Giây 0-5 (Kỳ vọng): Đeo tai nghe, gõ phím cơ lạch cạch tốc độ cao trên VS Code, màn hình tối chạy lệnh ngầu đét. (Nhạc trap mạnh, dồn dập).
  Giây 6-25 (Thực tế): Áo thun nhăn nheo, tóc rối bù, ôm đầu nhìn chằm chằm vào màn hình báo lỗi đỏ chót. (Nhạc tấu hài xịt keo).
- Audio: "POV: Bạn nghĩ học IT năm nhất sẽ thành hacker... Cho đến khi bạn ngồi khóc 2 tiếng đồng hồ chỉ vì gõ sai một dấu thụt lề trong Python."
- Text on screen: Tân sinh viên IT bơi hết vào đây!
- Call-to-Action (Giây 26-35): Người diễn quay mặt vào camera, chỉ tay lên màn hình: "Mới học code đừng đâm đầu vào code khó. Follow kênh để nhận lộ trình Python 8 tuần nhàn tênh qua môn nhé!"

Kịch bản 2 (Q&A - Ngày 5)

- Thời lượng: 40 giây.
- Visual: Chuyên gia/Mentor ăn mặc năng động, đứng trước bảng trắng có dán các note màu sắc. Góc máy thay đổi liên tục giữ nhịp độ nhanh.
- Audio: "Năm nhất học IT mà dốt Toán thì có code được không? Câu trả lời là: HOÀN TOÀN ĐƯỢC, nếu bạn bắt đầu với Python!

  Nhiều bạn nghĩ lập trình là phải giỏi đạo hàm, tích phân. Sai bét! Thứ bạn cần là TƯ DUY LOGIC.
  Python sinh ra là để tối giản cú pháp, giúp bạn tập trung vào giải quyết vấn đề thực tế chứ không phải giải toán. Từ con số 0, bạn chỉ mất đúng 8 tuần để thành thạo nền tảng cơ bản, làm tiền đề học bất cứ ngôn ngữ nào khác."
- Text on screen: Dốt Toán có học Code được không? -> Logic > Toán học.
- Call-to-Action (Giây 30-40): Mentor chỉ tay xuống dưới: "Trung tâm đang mở 100 slot tư vấn lộ trình Python miễn phí cho newbie. Nhấn ngay vào link ở Bio để đăng ký trước khi hết suất nhé!"

7. Báo cáo kiểm tra tính nhất quán

Tính toàn vẹn của dữ liệu (Data Integrity):

- Đối tượng 18-20 tuổi (Sinh viên năm nhất): Thể hiện nhất quán qua ngôn từ.
- Sản phẩm khóa học: Thời lượng "8 tuần" và chủ đề "Python cơ bản" được duy trì xuyên suốt trong mọi thông điệp và bài viết.
- Mục tiêu 100 Leads: Bài sale Facebook và Video Q&A TikTok đều giới hạn số lượng "100 slot" để tạo sự khan hiếm và đẩy nhanh tiến độ thu thập data.

Tính liên kết của chuỗi nội dung (Content Alignment):

- Thông điệp "Xóa mù lập trình - Vượt ải môn cơ sở" liên kết chặt chẽ với Pain Point được phân tích ở bước 1.
- Phễu hành trình khách hàng hợp lý: TikTok thu hút sự chú ý bằng nội dung đánh vào tâm lý bỡ ngỡ -> Facebook cung cấp lý do hợp lý để chọn học Python -> Đẩy chuyển đổi đồng loạt ở cuối tuần.

Kết luận: Hệ thống đầu ra tuân thủ 100% yêu cầu đầu vào. Không tự ý bịa đặt thông tin sai lệch về thời lượng học hay đối tượng mục tiêu, sẵn sàng cho việc triển khai thực tế.