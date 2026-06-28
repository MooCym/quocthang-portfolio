# quocthang-portfolio
Cách cài đặt và cấu hình pfSense
1. Giới thiệu
  - Đây là dự án Home Lab được xây dựng trên VMware Workstation nhằm mô phỏng hệ thống mạng của một doanh nghiệp nhỏ. Mục tiêu là thực hành cấu hình firewall, VLAN, DHCP, DNS, NAT và VPN bằng pfSense.
2. Mục tiêu
  - Xây dựng mô hình mạng doanh nghiệp trên môi trường máy ảo.
  - Cấu hình pfSense làm Firewall và Gateway.
  - Phân chia mạng bằng VLAN.
  - Cấu hình DHCP, DNS và NAT.
  - Thiết lập VPN để truy cập từ xa.
  - Kiểm thử khả năng kết nối và tính bảo mật của hệ thống.
3. Môi trường triển khai
Phần mềm
  - VMware WorkStation
  - pfSense CE
  - Windows Server
  - Windows 11
Thiết bị
  - Laptop cá nhân
  - Ram 16gb
4. Kiến trúc hệ thống
Internet -> Firewall -> Virtual Switch -> VLAN 10 - Quản trị/ VLAN 20 - Phòng làm việc/ VLAN 30 - Khách
