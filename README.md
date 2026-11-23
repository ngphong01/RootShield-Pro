# RootShield Pro

Ứng dụng quản lý & thiết lập lá chắn Root cho Android (hỗ trợ **APatch**, **Magisk**, **KernelSU**).

> 📦 **Tải APK bản mới nhất:** Vào mục [**Releases**](https://github.com/ngphong01/RootShield-Pro/releases/latest) để tải file `RootShield_Pro_v2.0.0.apk`.

---

## ✨ Tính năng chính (v2.0.0)
- **Kiểm tra trạng thái theo thời gian thực:** Hiển thị loại Root (`APatch` / `Magisk` / `KernelSU`) và tình trạng 5 module cốt lõi (`ZygiskNext`, `NoHello`, `HMA-OSS`, `TrickyStore`, `PlayIntegrityFork`).
- **Cài Full Bộ 5 Module Lá Chắn (Offline 1-Click):** Tích hợp sẵn bộ 5 module bên trong APK, cài đặt offline không cần tải thủ công từng file.
- **Tự động bọc ẩn Ngân hàng & VNeID:** Hỗ trợ bọc ẩn nhanh hàng loạt ứng dụng ngân hàng / ví điện tử Việt Nam hoặc tìm theo tên gói để thêm/gỡ, kèm nút **Soft Reboot** áp dụng ngay.
- **Mở VNeID An Toàn & Bật lại ADB/Dev:** Tự động xử lý Tùy chọn nhà phát triển / Gỡ lỗi USB khi mở VNeID và khôi phục lại chỉ với 1 chạm.
- **Ẩn `/bin/su` (APatch):** Hỗ trợ ẩn đường dẫn `/system/bin/su` đối với các ứng dụng kiểm tra gắt.
- **Mục `❓ Help` tích hợp sẵn:** Hướng dẫn chi tiết ngay trên giao diện chính trong app.

---

## 📌 Hướng dẫn sử dụng nhanh sau khi tải APK

1. **Cài đặt & Cấp quyền Root:**
   - Cài file APK từ mục [Releases](https://github.com/ngphong01/RootShield-Pro/releases).
   - Mở **APatch / Magisk / KernelSU** → mục **Quyền Root (SuperUser)** → bật cho phép **RootShield Pro**.
   - Mở lại app, góc trên bên phải hiện nhãn xanh **`● APATCH / MAGISK / KSU ROOT`** là thành công.
2. **Cài bộ 5 Module (nếu máy mới Root chưa có module):**
   - Bấm **`📦 Cài Full Bộ 5 Module Lá Chắn (Offline 1-Click)`**.
   - Đợi ~15 giây hoàn tất rồi bấm **Khởi động lại ngay**.
3. **Bọc ẩn App Ngân hàng & VNeID:**
   - Bấm **`🛡️ Tự động bọc toàn bộ App Ngân hàng / Ví VN`** (hoặc tìm app theo tên → bấm **Bọc ẩn**).
   - Bấm **`🔁 Soft Reboot`** (~10 giây) để áp dụng danh sách ẩn mới.
4. **Mở VNeID & App Ngân hàng gắt:**
   - Với **VNeID**: bấm **`🚀 Mở VNeID An Toàn`**. Dùng xong quay lại bấm **`🔌 Bật lại ADB & Dev`** nếu cần kết nối máy tính.
   - Với app kiểm tra gắt trên máy **APatch**: bấm thêm **`🥷 Ẩn /bin/su`** rồi khởi động lại máy 1 lần.

> 💡 **Lưu ý:** Khi tải thêm app ngân hàng mới từ CH Play, hãy vào RootShield Pro bọc ẩn trước khi mở app đó lần đầu tiên.
