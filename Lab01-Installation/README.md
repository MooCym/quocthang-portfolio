#Lab01-Installation
## 1. Giới thiệu
Đây là bài Lab đầu tiên trong dự án *pfSense Home Lab*. Mục tiêu của bài Lab là cài đặt thành công pfSense trên VMware Workstation, cấu hình các interface WAN/LAN và kiểm tra khả năng kết nối Internet của máy khách.

## 2. Mục tiêu
- Cài đặt pfSense CE trên VMware Workstation.
- Cấu hình Interface WAN và LAN.
- Thiết lập địa chỉ IP cho mạng LAN.
- Truy cập giao diện WebConfigurator.
- Kiểm tra kết nối Internet từ máy Client.

## 3. Môi trường thực hiện
- VMware Stations - 17Pro
- pfSense - 2.8.0
- Windows 11 - Clients
- Host OS - Windows 11

## 4. Sơ đồ mạng
<img width="974" height="295" alt="Topology Lab 01" src="https://github.com/user-attachments/assets/6766a4c5-ac6d-4584-b1e1-bfb26a6bbbec" />

## 5. Cấu hình mạng
WAN - Kết nối Internet - DHCP
LAN - Mạng nội bộ - 192.168.100.1/24

## 6. Các bước thực hiện
### Bước 1:
Tạo máy ảo pfSense trên VMware Workstation.
### Bước 2
Gắn file ISO và tiến hành cài đặt.
### Bước 3
Gán Interface WAN và LAN.
### Bước 4
Cấu hình địa chỉ IP cho LAN.
### Bước 5
Truy cập WebConfigurator thông qua trình duyệt.
### Bước 6
Hoàn tất Wizard cấu hình ban đầu.

## 7. Kết quả
Sau khi hoàn thành:
- pfSense khởi động thành công.
- WAN nhận địa chỉ IP từ DHCP.
- LAN hoạt động với mạng 192.168.100.0/24.
- Máy Client truy cập được Internet.
- Có thể đăng nhập WebConfigurator để quản trị.
## 8. Hình ảnh minh họa
### Cài đặt pfSense
![Install](install.png)
### Gán Interface
![Interface](interface.png)
### Dashboard
![Dashboard](dashboard.png)
### Kiểm tra kết nối Internet
![Ping](ping-test.png)

## 9. Kiến thức và kỹ năng đạt được
- Cài đặt pfSense CE.
- Cấu hình WAN và LAN.
- Quản lý Virtual Network trong VMware.
- Kiểm tra kết nối mạng.
- Làm quen với giao diện quản trị WebConfigurator.
