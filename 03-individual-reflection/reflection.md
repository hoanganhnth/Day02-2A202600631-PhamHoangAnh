# 03 — Individual Reflection
**Mã Học Viên:** 2A202600631  
**Họ Và Tên:** Phạm Hoàng Anh  

---


## 1. Đóng Góp Và Vai Trò Của Tôi Trong Nhóm

| Hoạt động nhóm | Tôi đã trực tiếp làm những gì? | Kết quả & Ảnh hưởng đối với bài làm nhóm |
|---|---|---|
| Scan cá nhân | Đưa ra các problem về AI learning material finder, AI tutor 24/7 và gym plan cá nhân hóa | Nhóm có thêm candidate về personalization |
| Challenge | Hỏi nhóm liệu deadline tracker có cần agent tự đọc Discord/Zalo không | Nhóm nhận ra scope agent quá rộng và có rủi ro permission |
| Rule / Workflow / Agent | Lập bảng so sánh Rule, Workflow, Agent | Nhóm thống nhất chọn Workflow |
| Boundary | Xác định AI không được tự thêm deadline nếu user chưa xác nhận | Nhóm có boundary rõ ràng |
| Risk | Phân tích hallucination, sai ngày giờ, hiểu sai ngữ cảnh | Nhóm có kế hoạch review và rollback |

## 2. Nhật Ký Sử Dụng AI Trong Quá Trình Làm Lab

| Phase làm bài | Tôi dùng AI để làm gì? | AI mang lại sự hữu ích gì? | AI hời hợt hoặc sai sót ở chỗ nào? | Tôi đã tự nhận định và chỉnh sửa lại như thế nào? |
|---|---|---|---|---|
| R/W/A | Nhờ AI so sánh Rule, Workflow và Agent | Giúp chia rõ mức độ tự động hóa | AI ban đầu có xu hướng chọn Agent vì nghe mạnh hơn | Chỉnh lại: MVP chỉ cần Workflow |
| Risk | Nhờ AI liệt kê rủi ro khi extract deadline | Gợi ý các lỗi như hallucination, sai ngày, bỏ sót yêu cầu phụ | Một số risk quá chung | Gắn risk với ví dụ cụ thể như “thứ sáu tuần này” |
| Boundary | Nhờ AI viết boundary | Giúp câu chữ rõ ràng | AI viết hơi dài và trùng ý | Rút gọn thành không tự lưu, không bịa, không thay user quyết định |
| Decision | Nhờ AI phản biện việc chọn Agent | Giúp nhóm có lý do không chọn Agent | AI chưa biết constraint lab của nhóm | Thêm lý do: permission, privacy, demo khó |

## 3. Bài Học Rút Ra Cho Bản Thân

Agent không phải lúc nào cũng là lựa chọn tốt nhất. Với bài này, workflow đã đủ vì đường đi khá tuyến tính: user đưa input, hệ thống trích xuất, user review, rồi mới export. Rule vẫn hữu ích cho bước tách block và xuất file, AI hữu ích ở bước hiểu ngôn ngữ tự nhiên, còn human review là điểm kiểm soát chất lượng.




## 4. Nếu Được Làm Lại Từ Đầu, Tôi Sẽ Thay Đổi Điều Gì?
Nếu làm lại, tôi sẽ đưa thêm ví dụ cụ thể về khi nào rule fail, ví dụ deadline viết mơ hồ như “trước buổi lab sau”.