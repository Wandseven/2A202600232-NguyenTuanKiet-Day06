# Individual reflection — Nguyễn Tuấn Kiệt (AI20K001 - 2A202600232)

## 1. Role
Phụ trách thiết vẽ Sketch work flow và viết tools.

## 2. Đóng góp cụ thể
- Vẽ Sketch work flow của product (User nhập thông tin -> AI reasoning chọn tool -> gọi tool và xử lý yêu cầu)
- Viết và test 3 tools cho Agent.
- Hoàn thành phần AI canvas trong SPEC.

## 3. SPEC mạnh/yếu
- Điểm mạnh nhất ở spec là nhóm xác định khá rõ user chính là bệnh nhân, nên toàn bộ flow đều xoay quanh việc giúp họ hiểu thông tin và biết bước tiếp theo cần làm gì. Nhờ vậy các phần như giải thích kết quả, hỗ trợ đặt lịch và tư vấn quy trình không bị rời rạc.
- Điểm còn yếu là spec chưa mô tả kỹ cách kiểm thử trong thực tế. Nhóm đã có metric và threshold, nhưng nếu có thêm bộ câu hỏi mẫu, tiêu chí chấm và nguồn dữ liệu kiểm tra thì phần này sẽ thuyết phục hơn nhiều.

## 4. Đóng góp khác
- Hỗ trợ test final product theo nhiều path khác nhau cho mỗi feature.

## 5. Điều học được
Điều mình học được là khi làm AI product, phần khó không chỉ nằm ở model mà nằm ở cách biến nhu cầu mơ hồ của người dùng thành flow rõ ràng. Với bài này, bệnh nhân không chỉ cần câu trả lời đúng mà còn cần được hướng dẫn dễ hiểu, đúng lúc và đúng mức. Điều đó làm mình hiểu rõ hơn vai trò của product thinking khi làm sản phẩm có AI.

## 6. Nếu làm lại
Nếu làm lại, mình sẽ dành nhiều thời gian hơn cho việc chuẩn hóa test case ngay từ đầu. Khi có sẵn danh sách câu hỏi theo từng nhóm tình huống, cả nhóm sẽ dễ kiểm tra prompt, tool và flow hơn, đồng thời cũng phát hiện sớm những chỗ chatbot trả lời dài dòng hoặc chưa đúng trọng tâm.

## 7. AI giúp gì / AI sai gì
- **Giúp:** AI hỗ trợ mình khá tốt trong giai đoạn khởi tạo ý tưởng, đặc biệt là lúc tách pain point, trust issue và các trường hợp ngoại lệ. Ngoài ra AI cũng giúp tạo nhanh nhiều ví dụ câu hỏi để thử phản hồi của chatbot.
- **Sai/mislead:** AI đôi khi gợi ý các câu trả lời nghe rất hợp lý nhưng lại quá chung chung, thiếu bối cảnh cụ thể của Vinmec và phạm vi bài làm. Nếu không kiểm tra lại bằng spec của nhóm thì rất dễ viết ra nội dung đúng về mặt ngôn ngữ nhưng không sát với sản phẩm mình đang xây.
