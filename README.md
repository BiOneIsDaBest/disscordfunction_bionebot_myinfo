# disscordfunction_bionebot_myinfo

# 📋 MyInfo Cog — BiOneBot

Lệnh `myinfo` cung cấp thống kê chấm công cá nhân trong hệ thống chấm công BiOneBot (GTA Roleplay), giúp người dùng dễ dàng theo dõi thời gian làm việc của mình.

---

## 🔧 Mô tả chức năng

- `prefix!myinfo`  
  ➤ Hiển thị thông tin người dùng:
  - Tên, ID, avatar
  - Bộ phận đang thuộc (theo role)
  - Ngày tham gia server (kèm thời gian động `<t:...:R>`)
  - Tổng thời gian làm việc tuần này và tháng này

- `prefix!myinfo <start> <end>`  
  ➤ Ngoài các thông tin trên, sẽ **thêm thống kê chi tiết theo từng ngày** trong khoảng thời gian đã chọn (`dd/mm/yyyy`)

---

## 💡 Cách hoạt động

- Kết nối với cơ sở dữ liệu `data.sqlite`
- Lấy thông tin từ bảng `OFFDUTY`
- Tính tổng thời gian làm việc theo tuần, tháng, và khoảng tùy chọn
- Xác định role theo tên:
  - `Phòng Giáo Dục & Đào Tạo`
  - `Phòng Nhân Sự`
  - `Phòng An Ninh`

---

## 📦 Phụ thuộc

File này sử dụng các thư viện sau (đã có trong `requirements.txt`):
- `discord.py==2.3.0`
- `pytz==2023.3`
- `sqlite3` (tích hợp sẵn với Python)

---

## 🧪 Mục đích sử dụng

- Hỗ trợ cá nhân tự theo dõi lịch sử chấm công
- Không yêu cầu quyền đặc biệt (mọi user đều dùng được)
- Thích hợp cho các server Discord có tổ chức làm việc theo ca/kíp

---

## 🛡️ Bản quyền

Bản quyền thuộc **BiOneIsDaBest**  
📌 Nếu mượn sử dụng hoặc chỉnh sửa, vui lòng **ghi rõ nguồn** hoặc Liên hệ: [Discord: BiOneIsDaBest](https://discord.com/users/1146990393167200276)


