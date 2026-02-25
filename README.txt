Mục Tiêu : Thiết kế mô hình mạng 3 lớp gồm Core layer , Distribution layer , Access layer 
-đảm bảo tính ổn định, khả năng mở rộng, tính sẵn sàng cao và hiệu quả trong quản lý vận hành.

2. Mục tiêu cụ thể :

-Xây dựng mô hình mạng theo kiến trúc Core – Distribution – Access.

-Triển khai phân chia VLAN cho từng phòng ban.

-Cấu hình định tuyến động OSPF giữa các lớp mạng.

-Triển khai cơ chế dự phòng gateway bằng HSRP.

-Cấu hình EtherChannel (LACP) tăng băng thông và dự phòng đường truyền.

-Thiết lập DHCP cấp phát IP tự động cho các VLAN.

-Cấu hình NAT cho phép truy cập Internet.

-Đảm bảo tính ổn định và khả năng chịu lỗi khi xảy ra sự cố link hoặc thiết bị.

3 .Thiết bị và công nghệ sử dụng
Thiết bị mạng :

-Router (kết nối ISP, NAT)

-Core Switch Layer 3

-Distribution Switch

-Access Switch

-Server (DHCP)

4.Giao thức và công nghệ

-VLAN – Phân chia mạng nội bộ

-Inter-VLAN Routing (SVI)

-OSPF – Định tuyến động nội bộ

-HSRP – Dự phòng Gateway

-EtherChannel (LACP) – Gộp link

-NAT Overload – Truy cập Internet

-DHCP – Cấp phát IP tự động

-ACL cơ bản 

Phần mềm mô phỏng:

Cisco Packet Tracer