# Hotel Booking System

## Giới thiệu
Dự án **Hotel Booking System** là một hệ thống quản lý đặt phòng khách sạn trực tuyến, được xây dựng nhằm hỗ trợ khách hàng tìm phòng, đặt phòng, thanh toán online, đồng thời giúp lễ tân và quản lý quản lý phòng, đặt phòng, check-in/check-out và báo cáo doanh thu. Hệ thống được thiết kế theo mô hình UML, cơ sở dữ liệu quan hệ và triển khai theo quy trình **Agile-Scrum**.

## Chức năng chính
- **Khách hàng (Guest)**:
  - Tìm kiếm và xem chi tiết các loại phòng.
  - Đặt phòng trực tuyến.
  - Thanh toán online và nhận xác nhận đặt phòng.
  
- **Lễ tân (Receptionist)**:
  - Tra cứu và quản lý đặt phòng.
  - Thực hiện check-in và check-out cho khách.
  - Cập nhật trạng thái phòng và tổng hợp chi phí.
  
- **Quản lý (Manager)**:
  - Quản lý thông tin phòng và giá phòng.
  - Xem báo cáo doanh thu.
  
- **Buồng phòng (Housekeeping)**:
  - Theo dõi công việc dọn phòng, tình trạng phòng.

## Thiết kế hệ thống
- **Use Case Diagram**: mô tả các tác nhân và chức năng chính của hệ thống.  
- **Sequence Diagram**: bao gồm luồng **Đặt phòng online** và luồng **Check-in/Check-out**.  
- **ERD (Entity-Relationship Diagram)**: mô tả 6 bảng dữ liệu chính: Guest, RoomType, Room, Reservation, Payment, Staff với các quan hệ PK-FK rõ ràng.

## Công nghệ
- **Thiết kế UML**: PlantUML 
- **Cơ sở dữ liệu**: MySQL 
- **Quản lý dự án**: Jira theo quy trình Agile-Scrum  
- **Quản lý mã nguồn**: GitHub (public repo)
