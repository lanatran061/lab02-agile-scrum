# Lab 02 – Agile Scrum (Hotel Booking System)

Mini Project: **Hệ thống quản lý đặt phòng khách sạn**

### Entity (6 bảng dữ liệu chính)
- Guest (Khách hàng)  
- RoomType (Loại phòng)  
- Room (Phòng cụ thể)  
- Reservation (Đặt phòng)  
- Payment (Thanh toán)  
- Staff (Nhân viên/Lễ tân/Quản lý)  

### Use Case chính
- Tìm phòng & Xem chi tiết phòng  
- Đặt phòng online (Booking)  
- Thanh toán online  
- Check-in / Check-out (Lễ tân)  
- Quản lý phòng & giá (Manager)  
- Quản lý đặt phòng (Receptionist)  
- Công việc buồng phòng (Housekeeping)  
- Báo cáo doanh thu (Manager)  

---

## Artefacts
- **Use Case Diagram**: `diagrams/usecase-diagram.png`  
- **Sequence Diagrams**:  
  - Online Booking: `diagrams/sequence-onlinebooking.png`  
  - Check-in/Check-out: `diagrams/sequence-checkin-checkout.png`  
- **ERD**: `diagrams/erd-hotel-booking.png`  
- Các file `.puml` đi kèm để chỉnh sửa lại bằng PlantUML.

---

## Jira (Agile Scrum)
- Project: Hotel Booking System  
- Backlog: 9 User Stories theo format *As a [role], I want [function], so that [benefit]*  
- Sprint Plan:  
  - Sprint 1: Auth + Search + View room  
  - Sprint 2: Booking & Hold  
  - Sprint 3: Payment, Check-in/Check-out  
  - Sprint 4: Report, Housekeeping, Release  
- Board Workflow: **To Do → In Progress → Code Review → Testing → Done**

---

## 🔗 GitHub ↔ Jira Integration
- Repo name: **lab02-agile-scrum**  
- Jira connected with GitHub via *GitHub for Jira App*  
- Smart Commit example:  

## Notes
- Repo này chỉ chứa artefacts UML/ERD.
- Các file `.puml` có thể mở bằng PlantUML hoặc draw.io.