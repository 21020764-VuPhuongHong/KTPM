# KTPM
### Bài tập tết
I - Tìm hiểu
1. Docker, docker-composer
  - Docker là nền tảng phần mềm cho phép bạn dựng, kiểm thử và triển khai ứng dụng một cách nhanh chóng. Docker đóng gói phần mềm vào các đơn vị tiêu chuẩn hóa được gọi là container có mọi thứ mà phần mềm cần để chạy, trong đó có thư viện, công cụ hệ thống, mã và thời gian chạy. Bằng cách sử dụng Docker, bạn có thể nhanh chóng triển khai và thay đổi quy mô ứng dụng vào bất kỳ môi trường nào và biết chắc rằng mã của bạn sẽ chạy được. 
  - Docker Compose là một công cụ hỗ trợ định nghĩa và chạy các ứng dụng multi-container. Docker Compose có thể xử lý đồng thời multi-container trong sản xuất, staging, phát triển, thử nghiệm và CI. Nó cho phép bạn mô tả các dịch vụ (services) cấu thành ứng dụng của bạn, cũng như mối quan hệ giữa chúng, trong một tệp YAML duy nhất.
2. Linux, Unix, BSD, *nix
  - Linux là một họ các hệ điều hành mã nguồn mở dựa trên Linux kernel - một hạt nhân hệ điều hành được phát hành lần đầu tiên vào ngày 17 tháng 9 năm 1991. Linux được phát triển dựa trên hệ điều hành Unix và viết bằng ngôn ngữ C. Giao diện hoàn toàn tách rời với hệ thống.
  - Unix là một họ hệ điều hành máy tính đa nhiệm, đa người dùng được viết vào những năm 1960 và 1970. Unix là một trong những hệ điều hành 64-bit đầu tiên, cho đến nay, hệ điều hành này rất được ưa chuộng bởi các tập đoàn lớn vì có tính bảo mật cao, an toàn và đa năng. Từ mục đích ban đầu, hệ điều hành Unix được tạo ra cho các lập trình viên chứ không phải người dùng bình thường. Vì vậy, thiết kế giao diện Unix khá kém thân thiện. Hầu hết công việc trong Unix còn được thực hiện qua các tệp lệnh trong CLI. Các lệnh Unix khá khó hiểu và phức tạp.
  - Berkeley Software Distribution (BSD) là một hệ điều hành phát triển từ Unix được phát hành vào thập niên 1970 từ trường Đại học California tại Berkeley.
  - Hệ điều hành *nix là một thuật ngữ chung dùng để chỉ các hệ điều hành tương tự Unix, bao gồm:
    - Unix: Hệ điều hành gốc được phát triển vào những năm 1960 tại Bell Labs.
    - Linux: Hệ điều hành mã nguồn mở được phát triển từ đầu những năm 1990 bởi Linus Torvalds.
    - BSD: Một họ hệ điều hành mã nguồn mở được phát triển từ đầu những năm 1970 tại Đại học         California, Berkeley.
  - macOS thuộc loại hệ điều hành Unix, cụ thể là dựa trên Darwin, một hệ điều hành mã nguồn mở được phát triển bởi Apple.
3. Alpine vs Ubuntu
  - Alpine Linux là một bản phân phối Linux độc lập, nhẹ và bảo mật, được thiết kế cho các thiết bị nhúng và máy chủ. Nó dựa trên musl libc và BusyBox, và sử dụng OpenRC cho hệ thống init. Alpine nổi lên sau khi Docker được phát triển bởi vì nó nhỏ và nhẹ, thường được sử dụng để làm docker image. Alpine Repository Giống như các distro Linux khác, Alpine sử dụng repo để cài đặt và cập nhật gói theo các phiên bản của Alpine.
  - Ubuntu là một hệ điều hành miễn phí và mã nguồn mở dựa trên Debian GNU/Linux - một bản phân phối Linux thông dụng, nổi tiếng với giao diện thân thiện với người dùng, hiệu suất tốt và hệ sinh thái phần mềm phong phú.
4. VNC
 - VNC, viết tắt của "Virtual Network Computing", là một hệ thống được sử dụng để chia sẻ màn hình giữa các thiết bị khác nhau với mục đích điều khiển từ xa. Điều này cho phép người dùng từ xa có thể xem và điều khiển màn hình, bàn phím và chuột của một máy tính khác như thể họ đang ngồi trước máy tính đó.
 - VNC hoạt động dựa trên mô hình client/server. Máy tính cần được cài đặt thành một máy chủ VNC, trong khi máy tính khác muốn điều khiển từ xa cần cài đặt một trình xem VNC, hoặc còn gọi là client. Khi hai thành phần này được kết nối, máy chủ VNC sẽ chuyển gửi hình ảnh màn hình từ xa đến trình xem VNC.
 - Ngoài việc xem màn hình từ xa, VNC cũng cho phép người dùng điều khiển máy tính từ xa bằng cách sử dụng bàn phím và chuột của thiết bị điều khiển. Điều này mang lại khả năng kiểm soát đầy đủ các hoạt động trên máy tính từ xa sau khi được cấp phép từ máy tính đó.
