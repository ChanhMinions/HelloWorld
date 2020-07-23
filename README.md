## Bài Tập Về Làm quen môi trường Android Studio và ứng dụng Android

-<a href= "https://ngocminhtran.com/2018/06/28/lap-trinh-android-dung-android-studio-3-x/"> Ứng Dụng Từ Bài</a>

### Yêu Cầu
A. MÔ TẢ VỀ Android Studio:
Môi trường
Tải và cài đặt Android Studio
Để kiểm tra các ứng dụng Android chúng ta có thể cài đặt và sử dụng máy ảo AVD (Android Virtual Device) có sẵn trong Android Studio hay cài đặt máy ảo tại Genymotion.
### Tạo ứng dụng đầu tiên
- <a href="https://www.youtube.com/watch?v=AVyxX9WsCVQ&feature=emb_logo">Link Hướng Dẫn nhiều hơn</a>
- Mở Android Studio
- Vào File > New > New Project
- Nhập tên ứng dụng (Hello World) trong mục Application Name, nhập vị trí lưu ứng dụng tại mục Project Location:

![image](android1.png)

-Mặc định Android Studio dùng ngôn ngữ chính là Java

![image](android2.png)



- Nhấn Next. Trong hộp thoại Configure Activity, chúng ta có thể thay đổi các thông tin về tên của activity hay tên của layout. 
- Ở đây tôi để mặc định và nhấn Finish. Một giao diện gồm 3 cửa sổ chính sẽ hiện ra như sau:

- Cửa sổ A chứa cấu trúc thư mục và các tập tin chính của dự án; cửa sổ B chứa các tập tin chúng ta cần làm việc; cửa sổ C chứa các thông báo như lỗi hay cảnh báo.
- Cùng nhìn lại cửa sổ A:

- Thư mục com.ngocminhtran.helloworld (được chọn từ hình trên) trong thư mục java gọi là một gói (package) hiện tại chỉ chứa một lớp là MainActivity.

- Tại cửa sổ B, mặc định chứa hai tập tin là activity_main.xml và MainActivity.java. Tập tin MainActivity.java là nơi chứa mã Java:
