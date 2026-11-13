BÀI TẬP: PHÂN TÍCH NGUYÊN TẮC HUMAN-IN-THE-LOOP TRONG QUẢN TRỊ NHÂN SỰ TẠI MARTX

Thưa giảng viên, dưới đây là bài làm của em cho tình huống ứng dụng AI trong việc đánh giá và ra quyết định nhân sự tại công ty MartX.

Trước khi đi vào phân tích chi tiết, em xin giải thích ngắn gọn một số thuật ngữ cơ bản được sử dụng trong bài:
- Human-in-the-loop (Con người trong quy trình): Là nguyên tắc bắt buộc phải có con người tham gia giám sát, kiểm tra và phê duyệt kết quả của AI trước khi áp dụng vào thực tế, đặc biệt là với những quyết định ảnh hưởng trực tiếp đến quyền lợi của con người.
- Decision Support (Hỗ trợ ra quyết định): Là vai trò đúng đắn của AI trong công việc, tức là AI chỉ làm trợ lý tổng hợp số liệu và đưa ra gợi ý tham khảo, còn người ra quyết định cuối cùng phải là con người.
- Bias (Định kiến hoặc thiên vị trong AI): Là tình trạng kết quả của AI bị lệch lạc, thiếu công bằng do dữ liệu đầu vào không đầy đủ ngữ cảnh hoặc do câu lệnh của người dùng mang tính áp đặt.

PHẦN 1: PHÂN TÍCH 2 VI PHẠM NGHIÊM TRỌNG CỦA TRƯỞNG PHÒNG NHÂN SỰ

Trong tình huống tại công ty MartX, hành động của Trưởng phòng Nhân sự đã mắc phải 2 vi phạm nghiêm trọng về chính sách sử dụng AI (AI Policy) và đạo đức nghề nghiệp như sau:

1. Vi phạm chính sách AI Policy và trách nhiệm pháp lý: Giao quyền phán quyết cho AI và trốn tránh trách nhiệm cá nhân

- Sai lầm về bản chất và thẩm quyền pháp lý: AI chỉ là một công cụ phần mềm đóng vai trò trợ lý đề xuất (Decision Support), hoàn toàn không có tư cách pháp nhân và không có thẩm quyền pháp lý để quyết định sa thải người lao động. Việc Trưởng phòng Nhân sự lấy danh sách 3 người từ AI rồi ký quyết định sa thải ngay lập tức mà không kiểm tra lại là hành vi bỏ qua nguyên tắc bắt buộc "Human-in-the-loop" (con người kiểm duyệt).
- Trốn tránh trách nhiệm giải trình: Khi có khiếu nại, Trưởng phòng trả lời rằng "Do AI phân tích khách quan từ số liệu, tôi không can thiệp nên hoàn toàn công bằng". Đây là cách hiểu sai hoàn toàn. Chữ ký trên quyết định sa thải là của Trưởng phòng, nên trách nhiệm pháp lý thuộc về Trưởng phòng chứ không thể đổ lỗi cho máy móc.
- Rủi ro bảo mật dữ liệu nội bộ: Hành động dán trực tiếp dữ liệu KPI và lịch sử chấm công của 50 nhân viên vào công cụ AI mà chưa qua bước ẩn danh (xóa tên thật, thông tin cá nhân) cũng vi phạm quy tắc bảo mật dữ liệu nhân sự của doanh nghiệp.

2. Vi phạm đạo đức nghề nghiệp và gây ra định kiến (Bias): Đánh giá con người máy móc, thiếu bối cảnh và thiếu công bằng

- Bẫy khách quan giả tạo và định kiến dữ liệu (Bias): Trưởng phòng cho rằng AI chỉ nhìn vào con số nên hoàn toàn công bằng. Tuy nhiên, các con số KPI và lịch sử chấm công thô không phản ánh được toàn bộ hoàn cảnh thực tế của nhân viên. Ví dụ: một nhân viên có ngày công thấp hoặc KPI tháng đó giảm có thể do nghỉ ốm dài ngày có giấy xác nhận của bệnh viện, nghỉ thai sản, gặp tai nạn lao động, vừa mới chuyển sang bộ phận mới đang trong thời gian thử việc, hoặc đang làm một dự án dài hạn chưa đến kỳ nghiệm thu kết quả. AI không biết những lý do chính đáng này nên sẽ xếp họ vào nhóm "kém nhất".
- Định kiến từ chính câu lệnh (Prompt Bias): Câu lệnh của Trưởng phòng yêu cầu "lập danh sách 3 nhân viên kém nhất để sa thải ngay lập tức" đã ép AI bắt buộc phải chỉ ra đủ 3 người, ngay cả khi cả 50 nhân viên đều đang hoàn thành định mức công việc.
- Thiếu tôn trọng và đối thoại với người lao động: Quyết định sa thải ảnh hưởng trực tiếp đến thu nhập, danh dự và cuộc sống của nhân viên. Việc sa thải đột ngột chỉ dựa vào kết quả trả về từ AI mà không có bước tìm hiểu nguyên nhân, nhắc nhở hay cho nhân viên cơ hội giải trình là vi phạm nghiêm trọng đạo đức nghề nghiệp của người làm công tác nhân sự.


PHẦN 2: SƠ ĐỒ LUỒNG QUY TRÌNH PHỐI HỢP 3 BƯỚC AN TOÀN CHO MARTX

Để sử dụng AI hỗ trợ công việc một cách hiệu quả mà vẫn đảm bảo an toàn pháp lý, đúng đạo đức và tuân thủ nguyên tắc "Human-in-the-loop", em xin thiết kế sơ đồ luồng quy trình phối hợp 3 bước cho công ty MartX như sau:

Sơ đồ tổng quát:

[Nhập dữ liệu (Đã ẩn danh)] ---> [Bước 1: AI phân tích & đề xuất] ---> [Bước 2: Human-in-the-loop thẩm định] ---> [Bước 3: Con người ký quyết định]

Chi tiết nội dung và cách thực hiện trong 3 bước:

Bước 1: Chuẩn bị dữ liệu an toàn và để AI phân tích đề xuất (Nhập dữ liệu -> AI đề xuất)
- Người thực hiện: Nhân viên hoặc Trưởng phòng Nhân sự kết hợp với công cụ AI.
- Cách thực hiện:
  + Trước khi đưa dữ liệu vào AI, phòng Nhân sự cần ẩn danh thông tin cá nhân của 50 nhân viên (ví dụ: đổi họ tên thật thành mã số NV01, NV02,... đến NV50) để bảo mật thông tin.
  + Sửa lại câu lệnh (prompt) đúng mục đích hỗ trợ: Yêu cầu AI thống kê, phân nhóm hiệu suất làm việc và chỉ ra những mã nhân viên có chỉ số KPI hoặc chuyên cần giảm sút bất thường cần được quản lý lưu ý, thay vì yêu cầu AI lập danh sách sa thải.
- Kết quả đầu ra của Bước 1: Bản báo cáo tổng hợp số liệu và danh sách đề xuất các trường hợp cần xem xét lại (AI dừng đúng ở vai trò Decision Support).

Bước 2: Con người kiểm duyệt và thẩm định thực tế (Human-in-the-loop thẩm định)
- Người thực hiện: Trưởng phòng Nhân sự phối hợp cùng Quản lý trực tiếp của nhân viên.
- Cách thực hiện:
  + Kiểm tra chéo số liệu: Đối chiếu kết quả AI gợi ý với bảng chấm công gốc và hồ sơ nhân sự để đảm bảo AI không tính toán nhầm (tránh lỗi ảo giác của AI).
  + Xác minh bối cảnh thực tế (loại bỏ Bias): Kiểm tra xem các nhân viên trong danh sách cảnh báo có thuộc trường hợp đặc biệt hay không (nghỉ phép hợp lệ, ốm đau, thai sản, mới nhận việc, hoặc gặp khó khăn khách quan từ phía dự án).
  + Đối thoại trực tiếp: Mời nhân viên và quản lý bộ phận trao đổi trực tiếp để lắng nghe lý do, đánh giá thái độ làm việc và tìm hướng khắc phục trước.
- Kết quả đầu ra của Bước 2: Biên bản thẩm định toàn diện (gồm cả số liệu lẫn hoàn cảnh thực tế) và đề xuất phương án xử lý công bằng cho từng cá nhân.

Bước 3: Phê duyệt phương án và ký quyết định chính thức (Ký quyết định)
- Người thực hiện: Trưởng phòng Nhân sự và Ban Giám đốc MartX.
- Cách thực hiện:
  + Dựa trên biên bản thẩm định thực tế ở Bước 2 (chứ không dựa trực tiếp vào câu trả lời của AI), lãnh đạo công ty đưa ra quyết định phù hợp với quy định của công ty và Luật Lao động (như hỗ trợ đào tạo lại, điều chuyển công việc, gia hạn thời gian thử thách, hoặc chấm dứt hợp đồng nếu nhân viên thực sự vi phạm quy chế).
  + Trưởng phòng Nhân sự hoặc Giám đốc ký tên vào văn bản quyết định chính thức, thông báo rõ ràng lý do cho nhân viên và chịu hoàn toàn trách nhiệm pháp lý cũng như trách nhiệm giải trình về quyết định của mình.
- Kết quả đầu ra của Bước 3: Quyết định nhân sự hợp pháp, minh bạch, đảm bảo công bằng cho người lao động và an toàn pháp lý cho công ty MartX.
