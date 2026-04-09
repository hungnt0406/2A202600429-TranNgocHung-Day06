# Reflection Cá Nhân

## 2A202600429 - Trần Ngọc Hùng - Day06
Repo nhóm: https://github.com/Quyenm/Nhom26-E403-Day06

## Vai trò

Vai trò chính của em trong dự án này là thiết kế giao diện, phát triển frontend và tích hợp frontend với backend cho trợ lý AI Vinmec. Em chịu trách nhiệm biến ý tưởng sản phẩm thành một giao diện có thể sử dụng được, xây dựng phần frontend cho website, và đảm bảo frontend có thể giao tiếp chính xác với backend API.

## Đóng góp

Đóng góp đầu tiên của em là thiết kế giao diện người dùng cho trải nghiệm chatbot. Vì sản phẩm liên quan đến hỗ trợ trong lĩnh vực y tế, em tập trung vào việc làm cho giao diện đơn giản, rõ ràng và dễ hiểu. Em đã làm việc trên bố cục của landing page và chat widget để người dùng có thể nhanh chóng hiểu mục đích chính của hệ thống và tương tác mà không bị nhầm lẫn. Em cũng chú ý đến bố cục, sự nhất quán màu sắc, khả năng đọc và luồng sử dụng tổng thể để sản phẩm tạo cảm giác đáng tin cậy và chuyên nghiệp hơn.

Đóng góp thứ hai của em là xây dựng frontend của dự án. Em đã triển khai giao diện web bằng stack frontend có trong repository group, tổ chức phần giao diện chat và xử lý logic tương tác giữa khu vực nhập liệu, danh sách tin nhắn và phản hồi từ hệ thống. Em cũng cải thiện cách hiển thị phản hồi của chatbot để các nội dung có định dạng như tiêu đề, danh sách và liên kết có thể được hiển thị rõ ràng hơn cho người dùng. Điều này rất quan trọng vì thông tin hỗ trợ y tế sẽ dễ theo dõi hơn khi được trình bày có cấu trúc thay vì chỉ là một khối văn bản dài.

Đóng góp thứ ba của em là tích hợp frontend với backend. Em đã kết nối frontend với backend API đã được triển khai, cấu hình cách xử lý API base URL và đảm bảo các yêu cầu chat được gửi đi cũng như phản hồi được hiển thị đúng cách. Em cũng điều chỉnh cấu hình container của frontend để có thể chạy ổn định bằng Docker trong khi vẫn kết nối trực tiếp đến backend service thay vì phụ thuộc vào một cấu hình proxy riêng. Phần công việc này giúp dự án chuyển từ một giao diện tĩnh thành một sản phẩm hoạt động theo luồng end-to-end hoàn chỉnh.

Ngoài phần triển khai, em cũng đóng góp vào việc cải thiện tính dễ sử dụng của hệ thống. Trong quá trình kiểm thử, em phát hiện một số vấn đề trong cách phản hồi từ backend được hiển thị trên giao diện, ví dụ như Markdown chưa được render đúng, các liên kết chưa thể bấm trực tiếp và prompt injection cases. Em đã sửa các vấn đề này để frontend có thể trình bày câu trả lời một cách tự nhiên và thân thiện hơn với người dùng.

## Tự đánh giá và cảm nhận

Thông qua dự án này, em nhận ra rằng công việc frontend không chỉ là làm cho giao diện đẹp mắt. Một frontend tốt còn cần hỗ trợ sự rõ ràng, độ tin cậy và trải nghiệm tương tác mượt mà, đặc biệt là trong một sản phẩm liên quan đến y tế. Trong dự án này, em nhận thấy rằng ngay cả những chi tiết nhỏ trong cách trình bày như định dạng văn bản, khoảng cách hay liên kết có thể bấm được cũng có ảnh hưởng rất lớn đến trải nghiệm của người dùng.

Em cũng học được tầm quan trọng của việc tích hợp hệ thống. Việc xây dựng các thành phần giao diện thôi là chưa đủ nếu frontend không thể giao tiếp ổn định với backend. Quá trình kết nối giao diện với API, xử lý cấu hình và kiểm tra luồng phản hồi thực tế giúp em hiểu rõ hơn rằng cần phải nhìn sản phẩm như một hệ thống hoàn chỉnh chứ không chỉ là một lớp giao diện bên ngoài.

Một khó khăn mà em gặp phải là làm sao để frontend vẫn đơn giản đối với người dùng nhưng vẫn đáp ứng được các yêu cầu kỹ thuật như cấu hình API, render phản hồi từ backend và triển khai bằng Docker. Việc giải quyết các vấn đề này đã giúp em cải thiện kỹ năng phát triển thực tế và hiểu rõ hơn cách frontend engineering hỗ trợ cho toàn bộ sản phẩm.

Nếu có thêm thời gian, em muốn phát triển dự án tốt hơn bằng cách bổ sung thêm cơ chế phản hồi từ người dùng, cải thiện khả năng hiển thị trên nhiều kích thước màn hình khác nhau và xây dựng một design system hoàn chỉnh hơn để đảm bảo tính nhất quán giữa các trang. Em cũng muốn tăng cường phần kiểm thử frontend để các lỗi hiển thị và lỗi tích hợp có thể được phát hiện sớm hơn.

Nhìn chung, em tin rằng vai trò của mình đã đóng góp trực tiếp vào việc giúp dự án trở nên dễ sử dụng và có tính trình bày tốt hơn. Phần công việc của em giúp định hình cách người dùng tương tác với trợ lý AI Vinmec và đảm bảo frontend có thể hoạt động như một giao diện thực sự được kết nối với backend service. Dự án này mang lại cho em nhiều kinh nghiệm thực tế trong việc kết hợp tư duy thiết kế, phát triển frontend và tích hợp hệ thống trong cùng một sản phẩm.


## UI

![Giao diện dự án Vinmec](./image.png)