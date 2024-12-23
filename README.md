# Web Toeic

Web Toeic là một ứng dụng web dành cho người học TOEIC, cung cấp các tài liệu học tập và bài kiểm tra để nâng cao kỹ năng tiếng Anh của bạn.

## Mô tả

Ứng dụng này bao gồm các tính năng sau:

- **Luyện tập ngữ pháp**: Cung cấp các bài tập ngữ pháp theo dạng bài kiểm tra.
- **Luyện nghe**: Bao gồm các bài luyện nghe với các đoạn hội thoại và câu chuyện.
- **Luyện đọc**: Cung cấp các đoạn văn và bài đọc với các câu hỏi kiểm tra.
- **Luyện viết**: Hướng dẫn và bài tập để cải thiện kỹ năng viết.
- **Thi thử TOEIC**: Cung cấp các đề thi thử TOEIC để bạn có thể luyện tập và đánh giá trình độ của mình.

## Cài đặt

Để cài đặt và chạy dự án này trên máy của bạn, làm theo các bước sau:


1. Download ZIP xong giải nén file đó 


2. [Download IDE Spring Tool Suit 4 và giải nén để dung phần mềm IDE này](https://spring.io/tools)

Vào Spring Tool Suit 4 , Vào File -> Open Projects from File System -> Ở phần Import source, chọn Directory -> Chọn project vừa tải -> Finish


3. Chuột phải vào file vừa thêm vào -> Run as -> Spring Boot App 

## Sử dụng
Sau khi đã cài đặt và chạy ứng dụng, bạn có thể truy cập vào trình duyệt và mở địa chỉ `http://localhost:8080/webtoeic` để sử dụng ứng dụng.

4.Note: Một số lỗi có thể xảy ra khi chạy
Lỗi 1 : Cổng 8080 đang bị App khác dùng
Mở Command Prompt và chạy lệnh:
'''bash
netstat -ano | findstr :8080
'''
Lệnh này sẽ hiển thị danh sách các tiến trình sử dụng cổng 8080. Kết quả trông như sau:
'''bash
TCP    127.0.0.1:8080      0.0.0.0:0      LISTENING      <PID>
'''
Ghi lại PID (Process ID) của tiến trình đang sử dụng cổng 8080.
Chạy tiếp lệnh sau để mở lại cổng 8080
'''bash
tasklist | findstr <PID>
'''
Thay số <PID> bằng số PID tìm được


## Database
![Mô Hình](https://github.com/user-attachments/assets/d53b22e6-b4b1-44fe-9510-3987d66cffce)



## Thành viên trong nhóm
- Vũ Hoàng Ân
- Dương Tiến Đạt
- Trần Tuấn Đạt
- Đinh Minh Vũ

## Tài khoản sử dụng admin
tk : acizindahouse@gmail.com
mk : 123456789
