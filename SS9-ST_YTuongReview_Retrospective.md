# SS9 - ST: Theo dõi góp ý và cải tiến qua ba Sprint

Em đóng vai Thu Hà, Scrum Master của RikkeiAssist. Em đề xuất một bảng tính có hai trang: “Góp ý sản phẩm” và “Cải tiến cách làm việc”. Mỗi dòng có mã riêng và giữ lịch sử theo Sprint để dễ tra lại, không cần thêm cuộc họp riêng.

## Phần 1. Chu trình theo dõi

### 1. Góp ý sản phẩm

**Sprint Review: ghi góp ý và nguồn (Minh Anh hoặc người ghi chép được thống nhất)** → **đánh dấu điều chưa rõ, hỏi lại người góp ý (Minh Anh phối hợp Developers/CSKH)** → **kiểm tra trùng, xác nhận mã PBI liên quan (Minh Anh)** → **xem xét Product Backlog: bổ sung, điều chỉnh, để chờ hoặc chưa chọn và ghi lý do (Minh Anh, trao đổi cùng nhóm)** → **Sprint Planning: nhóm lựa chọn công việc theo mục tiêu và khả năng, không mặc định nhận mọi góp ý (Scrum Team)** → **Review Sprint sau: kiểm tra kết quả và lấy phản hồi tiếp (Developers trình bày, Minh Anh cập nhật bảng)**.

Nếu chưa đủ thông tin thì giữ trạng thái “Chờ làm rõ”, không ghi thành “đã đưa vào Product Backlog”. “Đã ghi nhận” chỉ nói rằng đã lưu góp ý, không có nghĩa là đã hiểu rõ hay đã cam kết làm.

### 2. Cải tiến cách làm việc

**Sprint Retrospective: kiểm tra cải tiến cũ bằng dữ liệu (người theo dõi cập nhật, Thu Hà điều phối)** → **nhóm chọn cải tiến ít và cụ thể, ghi người theo dõi, mốc kiểm tra và bằng chứng cần có (Scrum Team)** → **thực hiện trong Sprint sau (Developers/người nhận theo dõi cập nhật khi có kết quả)** → **Retrospective Sprint sau: đối chiếu bằng chứng và quyết định tiếp tục, điều chỉnh, hoàn tất hoặc dừng có lý do (Scrum Team)** → **giữ lại lịch sử quyết định (người theo dõi cập nhật)**.

Hai sự kiện vẫn họp riêng, đúng thành phần và thời lượng đã thống nhất theo Sprint. Review có các bên liên quan để kiểm tra sản phẩm; Retrospective là phần trao đổi nội bộ Scrum Team, có cách góp ý ẩn danh, không dùng bảng làm chỉ tiêu cá nhân. Nếu ý kiến nội bộ vô tình gửi sang bảng góp ý sản phẩm thì chỉ chuyển nội dung cần thiết sau khi nhóm thống nhất, không công khai tên người phản ánh.

## Phần 2. Hai bảng theo dõi mẫu qua Sprint 11–13

Đề chỉ cho một số dữ liệu tổng hợp và trạng thái hiện có, không cho ngày cập nhật chi tiết từng mã. Các ô chưa biết được ghi rõ, không tự suy ra rằng một góp ý đã nằm trong các lượt “đã hỏi rõ”.

### 1. Góp ý F-11-04

| Sprint | Mã và nguồn | Góp ý | Tình trạng làm rõ | Liên kết PBI | Người cập nhật / bước tiếp theo |
|---|---|---|---|---|---|
| 11 | F-11-04; trưởng nhóm CSKH | Chuyển người sớm hơn khi AI không chắc chắn. | Chưa có ngưỡng cụ thể; đề không cho lịch sử hỏi rõ ở Sprint này. | Chưa có mã được xác nhận. | Minh Anh lưu yêu cầu, cần hỏi rõ trường hợp nào phải chuyển người. |
| 12 | Giữ F-11-04 | Theo dõi tiếp cùng góp ý. | Chưa có bằng chứng cập nhật riêng trong đề; không tự đánh dấu đã làm rõ. | Chưa có mã được xác nhận. | Minh Anh kiểm tra lại trao đổi với CSKH, giữ lịch sử thay vì tạo mã mới. |
| 13 | F-11-04 liên quan F-13-05 | F-13-05 nói chuyển ngay khi AI trả lời “tôi không chắc”. | Hiện vẫn chưa rõ ngưỡng; hai câu có thể cùng nhu cầu nhưng cần xác nhận. | Chưa có mã được xác nhận. | Minh Anh hỏi trưởng nhóm và CSKH ca tối về phạm vi/ngưỡng; liên kết hai mã để tránh xử lý lặp, chưa tự gộp xóa. |

### 2. Improvement IM-11-02

| Sprint | Nội dung theo dõi | Bằng chứng đã có | Kết luận | Theo dõi và bước tiếp theo |
|---|---|---|---|---|
| 11 | Quyền môi trường từ Ngày 1, Integration Test khi PBI đầu tiên sẵn sàng. | Integration Test đầu tiên Ngày 8; chưa có dữ liệu quyền và ngày PBI sẵn sàng. | Mở; chưa đủ bằng chứng để biết có chạy ngay khi PBI sẵn sàng hay không. | Developers ghi thêm checklist quyền và thời điểm PBI sẵn sàng. |
| 12 | Tiếp tục cùng IM-11-02. | Integration Test đầu tiên Ngày 7; thiếu hai dữ liệu trên. | Mở; sớm hơn một ngày chưa đủ chứng minh đạt mục tiêu. | Developers cập nhật trở ngại; nhóm xem xét lại ở Retrospective. |
| 13 | Tiếp tục cùng IM-11-02. | Integration Test đầu tiên Ngày 8; vẫn thiếu dữ liệu đối chiếu. | Mở; chưa có bằng chứng tiến bộ bền vững qua ba Sprint. | Developers và Thu Hà đề xuất bổ sung phép đo cho Sprint 14, không đóng chỉ vì đã tồn tại lâu. |

### 3. Nhìn vào dữ liệu chung

Góp ý tăng từ 12 lên 15 rồi 18; số đã hỏi rõ là 5, 7, 10 và số được đưa vào xem xét Product Backlog là 3, 6, 5. Các số này không chứng minh mọi góp ý đã được xử lý. Improvement còn mở tăng từ 2 lên 3 rồi 4, nên cần xem từng việc và bằng chứng trước khi tạo thêm việc mới; không cộng các số mở này thành số việc khác nhau vì có thể có việc chuyển tiếp.

## Phần 3. Quy tắc xử lý tình huống

### 1. Muốn tự động hóa 90% nhưng cũng muốn chuyển người sớm

Minh Anh hỏi rõ hai bên về tình huống sử dụng, mức AI không chắc chắn, rủi ro trả lời sai và tác động đến CSKH. Ghi hai nhu cầu cùng rủi ro, không hứa đạt 90% ngay. Product Owner xem xét ưu tiên và lựa chọn thử nghiệm phù hợp, chẳng hạn tự động hóa ca đơn giản và chuyển người ở ca chưa chắc chắn. Đây là đề xuất để thảo luận, chưa phải quy tắc đã được khách hàng chấp thuận; ngưỡng phải được làm rõ trước khi viết PBI và tiêu chí chấp nhận.

### 2. Góp ý trùng và PBI có dấu hỏi

Đối chiếu F-11-04 với F-13-05 bằng ví dụ thực tế và xác nhận của CSKH. Nếu cùng nhu cầu thì đặt một mục theo dõi chính, liên kết cả hai mã nguồn, giữ câu chữ và lịch sử cũ. Nếu phạm vi khác nhau thì giữ riêng và ghi điểm khác. Với F-12-07, mã “PBI-52?” chỉ là liên kết nghi ngờ: Minh Anh kiểm tra nội dung PBI-52 rồi mới xác nhận; trong lúc chờ vẫn ghi “chưa xác nhận”, đồng thời hỏi rõ chính sách đổi trả còn thiếu.

### 3. Muốn báo cáo đẹp hoặc đóng mọi Improvement quá một Sprint

Không đổi tất cả góp ý thành đã xử lý. Bảng dùng các trạng thái riêng: Đã ghi nhận → Chờ làm rõ → Đã làm rõ → Đã xem xét Product Backlog → Theo dõi kết quả; mỗi chuyển bước có lý do hoặc bằng chứng. Không xóa lịch sử để bảng gọn và không đóng cải tiến theo tuổi của nó.

| Mã Improvement | Quyết định đề xuất để Scrum Team thống nhất | Căn cứ / lần kiểm tra tiếp |
|---|---|---|
| IM-11-02 | Giữ mở và điều chỉnh cách theo dõi: kiểm tra quyền Ngày 1, ghi thời điểm PBI đầu tiên sẵn sàng và lần chạy test. | Test đầu tiên là Ngày 8, 7, 8; thiếu dữ liệu để chứng minh đạt mục tiêu. Developers cập nhật, xem lại ở Retrospective Sprint 14. |
| IM-12-04 | Đề xuất dừng vì kênh không còn dùng; chỉ ghi “Đã dừng” sau quyết định minh bạch của Scrum Team, kèm Sprint và lý do. | Xác nhận kênh đã ngừng thí điểm; giữ dòng lịch sử. Gia Huy cập nhật quyết định, không ghi thành “Hoàn tất đạt mục tiêu”. |
| IM-13-03 | Tiếp tục kiểm tra tác động trước khi kết luận thành công lâu dài. | Hai phiên Pairing có thời gian tái hiện giảm, mới kiểm tra một lần. Developers ghi thời gian tái hiện ở các ca tiếp theo và xem lại Sprint 14. Không bịa ca lỗi nếu Sprint đó không phát sinh. |

### 4. Một tiêu chí đo thay đổi thật sau ba Sprint tới

**Đến hết Sprint 16, cả ba Sprint 14–16 đều chạy Integration Test đầu tiên trong cùng ngày PBI đầu tiên sẵn sàng tích hợp, với quyền môi trường đã được xác nhận từ Ngày 1.**

Developers lưu checklist quyền, thời điểm PBI sẵn sàng và log test cho từng Sprint; nhóm đối chiếu ở Retrospective. Nếu không có PBI phù hợp hoặc thiếu bằng chứng thì ghi rõ chưa đo được, không tính là đạt. Tiêu chí này đo thay đổi thực tế trong cách kiểm thử thay vì chỉ đếm số cuộc họp.
