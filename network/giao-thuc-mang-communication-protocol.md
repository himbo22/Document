# Internet Protocol Suite

Internet Protocol Suite (bộ giao thức liên mạng) là tập hợp các giao thức thực thi protocol stack (chồng giao thức) mà Internet chạy trên đó. Internet Protocol Suite đôi khi được gọi là bộ giao thức TCP/IP. TCP và IP là những giao thức quan trọng trong Internet Protocol Suite - Transmission Control Protocol (TCP) và Internet Protocol (IP). Internet Protocol Suite tương tự như mô hình OSI, nhưng có một số khác biệt. Ngoài ra không phải tất cả các lớp (layer) đều tương ứng tốt.

# Protocol Stack

Protocol Stack (Chồng giao thức) là hình thức cài đặt phần mềm cho một bộ giao thức mạng máy tính. Chúng là là tập hợp đầy đủ các lớp giao thức và chúng hoạt động cùng nhau để cung cấp khả năng kết nối mạng đến các thiết bị khác.

# Transmission Control Protocol (TCP)

Transmission Control Protocol (TCP) là giao thức cốt lõi của Internet Protocol Suite. TCP bắt nguồn từ việc thực thi mạng, bổ sung cho Internet Protocol. Do đó, Internet Protocol Suite thường được gọi là TCP/IP. TCP cung cấp một phương thức phân phối đáng tin cậy một luồng octet (khối dữ liệu có kích thước 8 bit) qua mạng IP. Đặc điểm chính của TCP là khả năng đưa ra lệnh và kiểm tra lỗi. Tất cả các ứng dụng Internet lớn như World Wide Web, email và truyền file đều dựa vào TCP.

# Internet Protocol (IP)

IP còn được gọi là giao thức Internet và chúng là giao thức chính trong Internet protocol suite. Với khả năng chuyển tiếp dữ liệu qua mạng và giúp thiết lập internet thông qua việc định tuyến của Internet Protocol.

IP cung cấp một dịch vụ gửi dữ liệu không đảm bảo nên gói dữ liệu có thể đến nơi mà không còn nguyên vẹn, nó có thể đến không theo thứ tự. IP rất thông dụng trong mạng internet  ngày nay. Giao thức tầng mạng thông dụng nhất ngày nay là Ipv4 hoặc Ipv6.

# Hypertext Transfer Protocol (HTTP)

HTTP là nền tảng giao tiếp dữ liệu cho World Wide Web. Siêu văn bản (hypertext) là văn bản có cấu trúc sử dụng các siêu liên kết giữa các node chứa văn bản. HTTP là giao thức ứng dụng cho hệ thống thông tin hypermedia (siêu phương tiện) phân tán và kết hợp.

Cổng mặc định của HTTP là 80 và 443. Hai cổng này đều được bảo mật.

# File Transfer Protocol (FTP)

FPT (File Transfer Protocol) giao thức truyền tin ,thường được dùng để trao đổi tập tin qua mạng lưới truyền thông nằm trong tầng ứng dụng trong bộ giao thức TCP/IP. FTP hoạt động cần có ít nhất hai máy tính, một máy chủ  gọi là FTP server và một máy FTP Client

FTP Server dùng để chạy phần mềm cung cấp dịch vụ FTP và lắng nghe yêu cầu về dịch vụ của các máy tính khác trên mạng ở windows server Và FTP Client là máy khách chạy phần mềm FTP dành cho người dùng dịch vụ để kết nối đến FTP Server. Khi hai máy kết nối với nhau, FTP Client có thể xử lý một số thao tác về tập tin, như tải tập tin lên FTP Server, tải tập tin từ FTP Server xuống máy của  mình, đổi tên tập tin, ngay cả xóa tập tin ở FTP Server. FTP Client kết nối với FTP Server thông qua cổng mặc định 21 trên nền TCP

# Secured Shell (SSH)

Secured Shell (SSH) là một giao thức mạng dùng để thiết lập kết nối mạng một cách bảo mật. SSH hoạt động ở lớp trên trong mô hình phân lớp TCP/IP. Có thể nói SSH là phương thức chính được sử dụng để quản lý các thiết bị mạng một cách an toàn ở cấp lệnh. Nó được thay thế cho Telnet vì tính bảo mật an toàn hơn.

Cổng mặc định của SSH là 22.

# Telnet

Telnet là phương thức chính được sử dụng để quản lý các thiết bị mạng ở cấp lệnh. Không giống như SSH, Telnet không cung cấp kết nối an toàn, mà chỉ cung cấp kết nối không bảo mật cơ bản.

Cổng mặc định của Telnet là 23.

# Simple Mail Transfer Protocol (SMTP)

SMTP (Simple Mail Transfer Protocol) giao thức truyền thư đơn giản, được sử dụng để truyền nội dung thư điện tử từ Mail Server này đến Mail Server khác. Nó thực hiện nhiệm vụ truyền thư giữa các Mail Server thông qua cổng mặc định 25.

# Domain Name System (DNS)

Domain Name System (DNS)- hệ thống phân giải tên miền. Hệ thống này là một hệ thống cho phép thiết lập tương ứng giữa địa chỉ IP và tên miền trên internet. Nhờ giao thức này nên có thể chuyển đổi tên miền thành địa chỉ IP. Cổng mặc định của DNS là 53.

# Internet Message Access Protocol (IMAP)

Internet Message Access Protocol (IMAP) là giao thức chuẩn mạng Internet được sử dụng bởi các ứng dụng email để truy xuất thư email từ máy chủ thư qua kết nối TCP/IP. IMAP không xóa nội dung khỏi hộp thư của máy chủ.

Cổng mặc định của IMAP là 143 và cổng IMAP bảo mật là 993.

# Giao thức POP3

POP3 ( Post Office Protocol Version 3): là một giao thức dùng để tải thư điện tử từ Mail Server về máy tính, thông qua kết nối TCP/IP. Trình duyệt mail Client sẽ kết nối đến Mail Server để nhận thư thông qua  cổng mặc định 110 của giao thức POP3

# Simple Network Management Protocol (SNMP)

Simple Network Management Protocol được sử dụng để quản lý mạng. SNMP có khả năng giám sát, cấu hình và điều khiển các thiết bị mạng. SNMP trap cũng có thể được cấu hình trên các thiết bị mạng, để thông báo cho máy chủ trung tâm khi xảy ra hành động cụ thể.

Cổng mặc định của SNMP là 161/162.

# Hypertext Transfer Protocol over SSL/TLS (HTTPS)

HTTPS được sử dụng với HTTP để cung cấp các dịch vụ tương tự, nhưng với kết nối bảo mật được cung cấp bởi SSL hoặc TLS.

Cổng mặc định của HTTPS là 443.