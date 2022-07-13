# Understand differnt OS concepts
 OS(Operating System) : là hệ thống phần mềm quản lý tất cả bao gồm phần cứng và phần mềm.
## Threads and Concurrency
### Thread 
-  được gọi là luồng. Luồng là một chuỗi các lệnh được lập trình một cách nhỏ nhất để có thể được quản lí độc lập trong một bộ định thời. Luồng là một thành phần của tiến trình.
-  Luồng là một hoạt động.
-  Là đơn vị thực thi thực thể trong tiến trình.
-  Hoạt động đồng đồng thời, nhiều luồng được thực thi cùng nhau.
-  Chia sẻ thiết bị I/O, CPUs, bộ nhớ.
![](https://giaingo.info/wp-content/uploads/2021/08/4-3-768x725.jpg)


### Concurrency(xử lý đông thời) :
- có thể xử lý nhiều vấn đề cùng một lúc , những vấn đề đó không nhất thiết phải xảy ra cùng một lúc.
Ví dụ: Một cậu bạn đang chạy bộ buổi sáng. Trong quá trình chạy bộ anh ta phát hiện mình đã quên chưa thắt dây giày, lúc này anh ta sẽ phải dừng công việc chạy bộ lại và bắt đầu công việc thắt lại dây rồi mới có thể tiếp tục chạy được.
 
## Process Mamagement
-  đề cập đến việc điều chỉnh các quy trình với các mục tiêu đưa ra
- Thiết kế và thực hiện các kiến trúc mô hình

## Sockets
 - Socket là điểm cuối end-point trong liên kết truyền thông hai chiều (two-way communication) biểu diễn kết nối giữa Client – Server. Các lớp Socket được ràng buộc với một cổng port (thể hiện là một con số cụ thể) để các tầng TCP (TCP Layer) có thể định danh ứng dụng mà dữ liệu sẽ được gửi tới. 
 - Socket là giao diện lập trình ứng dụng mạng được dùng để truyền và nhận dữ liệu trên internet. Giữa hai chương trình chạy trên mạng cần có một liên kết giao tiếp hai chiều, hay còn gọi là two-way communication để kết nối 2 process trò chuyện với nhau. Điểm cuối (endpoint) của liên kết này được gọi là socket.
 ![](https://wiki.matbao.net/wp-content/uploads/2019/12/socket-la-gi-2.png)
- Chức năng của socket là kết nối giữa client và server thông qua TCP/IP và UDP để truyền và nhận giữ liệu qua Internet.
![](https://wiki.matbao.net/wp-content/uploads/2019/12/socket-la-gi-3.jpg)
 ## Virtualization
- là việc tạo ra phiên bản ảo - chứ không phải thực - của một thứ gì đó, chẳng hạn như hệ điều hành (OS), máy chủ, thiết bị lưu trữ hoặc tài nguyên mạng.
- sử dụng phần mềm mô phỏng chức năng phần cứng để tạo ra một hệ thống ảo.
(https://www.techtarget.com/searchitoperations/definition/virtualization#:~:text=Virtualization%20is%20the%20creation%20of,to%20create%20a%20virtual%20system.)
## I/O Management _ quản lý đầu vào ra
- để nhận các yêu cầu vào / ra dữ liệu của ứng dụng và gửi nó đến thiết bị vật lý, sau đó nhận lại các phản hồi từ thiết bị và gửi đến ứng dụng xử lý tiếp
- Thiết bị I / O có thể được chia thành hai loại:
1. Block devices (thiết bị khối): loại thiết bị mà trình điều khiển giao tiếp bằng cách gửi toàn bộ khối dữ liệu. Ví dụ: Ổ đĩa cứng, thiết bị USB Flash, máy ảnh USB 
2. Character devices (thiết bị ký tự): Loại thiết bị mà trình điều khiển giao tiếp bằng cách gửi và nhận các ký tự đơn (byte hoặc mã 8 - octa). Ví dụ: các loại card màn hình, card âm thanh 

## Memory Storage
- là một thiết bị công nghệ bao gồm các phần tử máy tính và lưu trữ dữ liệu, được dùng để duy trì dữ liệu số.
## File System
- là các phương pháp và các cấu trúc dữ liệu mà một hệ điều hành sử dụng để theo dõi các tập tin trên ổ đĩa hoặc phân vùng
- cách các tập tin được tổ chức trên ổ đĩa.

