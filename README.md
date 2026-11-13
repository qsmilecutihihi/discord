discord bot

Ứng dụng quản lý và tự động hóa server Discord tích hợp giao diện **GUI Desktop (HUD Style)** hiện đại, sang trọng với tông màu tối mờ chuyên nghiệp. Giúp bạn dễ dàng khởi động bot, kiểm soát cấu trúc kênh, phân quyền và vận hành các tính năng nâng cao trực tiếp mà không cần dùng lệnh thủ công liên tục.

---

## ✨ Tính năng nổi bật

* 🖥️ **Giao diện HUD Desktop trực quan**: Quản lý toàn bộ cấu trúc kênh, danh mục của server dạng cây (`Treeview`) mượt mà.
* ⚡ **Dựng lại Server tự động**: Xóa cấu trúc cũ và thiết lập lại toàn bộ hệ thống kênh, role chuẩn chỉ trong 1 cú click.
* 🔒 **Bảo mật & Kiểm soát**: 
  * Khóa/Mở khóa nhanh các kênh chat.
  * Hỗ trợ tính năng gỡ ban toàn bộ (`unbanall`) an toàn.
* 🎫 **Hệ thống Ticket tự động**: Tạo phòng hỗ trợ riêng tư giữa người dùng và đội ngũ Staff.
* 🎙️ **Phòng thoại tạm thời (Temp Voice)**: Tự động tạo phòng voice riêng khi người dùng truy cập kênh chỉ định và tự xóa khi trống.
* 📊 **Thống kê tự động**: Cập nhật liên tục số lượng thành viên, trạng thái online qua kênh Voice.
* 🛡️ **Khay hệ thống (System Tray)**: Chạy ẩn dưới khay hệ thống, không chiếm diện tích thanh taskbar.

---

## ⚙️ Yêu cầu hệ thống

* **Python**: Phiên bản `3.10` trở lên.
* **Hệ điều hành**: Windows 10 / 11.

---

## 📦 Hướng dẫn cài đặt

1. **Clone hoặc tải mã nguồn** về máy tính của bạn.
2. Cài đặt các thư viện phụ thuộc bằng lệnh PowerShell / Command Prompt:
   ```bash
   py -m pip install -U discord.py pystray pillow
