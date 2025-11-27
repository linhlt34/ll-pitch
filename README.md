# 🚀 Chiến lược Chuyển đổi số & Tái định vị: Vượt Sóng 2026-2030

**Digital Pitch Deck** - Phiên bản kỹ thuật số trình bày tầm nhìn chiến lược và dữ liệu tài chính theo phong cách hiện đại, trực quan và tương tác cao.

Chào mừng đến với kho lưu trữ chính thức của bộ slide thuyết trình chiến lược. Dự án này thay thế các file PowerPoint tĩnh truyền thống bằng trải nghiệm web mượt mà, tối ưu cho việc trình chiếu trên mọi thiết bị.

---

## 🔗 Truy cập & Trình chiếu

Không cần cài đặt phần mềm. Bạn có thể trình chiếu ngay lập tức.

| Trạng thái | Liên kết | Ghi chú |
|------------|----------|---------|
| 🟢 **Live Demo** | **[👉 BẤM VÀO ĐÂY ĐỂ XEM SLIDE](https://linhlt34.github.io/ll-pitch/)** | Link này luôn cập nhật bản mới nhất |
| 🔄 Cập nhật | `Ctrl + F5` (Win) / `Cmd + Shift + R` (Mac) | Xóa cache nếu chưa thấy nội dung mới |

---

## 🖥️ Hướng dẫn Điều khiển (Dành cho Người thuyết trình)

Giao diện được thiết kế tối giản để bạn tập trung vào nội dung.

### 🎮 Các phím tắt cơ bản

| Thao tác | Phím tắt / Hành động |
|----------|---------------------|
| **Chuyển Slide Tiếp** | Phím Mũi tên **Phải** `→` hoặc Click chuột vào vùng bên phải màn hình |
| **Quay lại Slide** | Phím Mũi tên **Trái** `←` hoặc Click chuột vào vùng bên trái màn hình |
| **Nhảy đến trang** | Nhập số trang vào ô điều hướng bên dưới rồi nhấn `Enter` |
| **Chế độ Toàn màn hình** | Nhấn `F11` (Windows) hoặc `Cmd + Ctrl + F` (Mac) |

> **💡 Mẹo Pro:** Hãy luôn bật chế độ Toàn màn hình (`F11`) để ẩn thanh địa chỉ trình duyệt, mang lại trải nghiệm hình ảnh sắc nét và chuyên nghiệp nhất.

---

## ✍️ Hướng dẫn Chỉnh sửa Trực tiếp trên GitHub (Dành cho mọi người)

Bạn có thể sửa lỗi chính tả hoặc cập nhật số liệu **trực tiếp trên trình duyệt** mà không cần cài đặt bất kỳ công cụ lập trình nào.

### 🔹 Bước 1: Mở trình chỉnh sửa

1. Truy cập vào [**trang chủ của kho lưu trữ này**](https://github.com/linhlt34/ll-pitch) trên GitHub
2. Nhấn phím **dấu chấm** `.` trên bàn phím
3. Trình duyệt sẽ chuyển sang giao diện **github.dev** (giống VS Code)

> **Hoặc:** Thay `github.com` thành `github.dev` trong thanh địa chỉ

### 🔹 Bước 2: Tìm và sửa nội dung

1. Ở cột bên trái, tìm và bấm vào file `index.html` (hoặc file `.html` tương ứng)
2. Sử dụng tổ hợp phím `Ctrl + F` (hoặc `Cmd + F`) để tìm đoạn văn bản cần sửa
3. Sửa lại nội dung nằm giữa các dấu ngoặc nhọn `>...<`
   - **Ví dụ:** Đổi `>12.000 tỷ<` thành `>15.000 tỷ<`

### 🔹 Bước 3: Lưu và Xuất bản (Quan trọng!)

1. Nhìn sang thanh công cụ dọc bên trái cùng
2. Bấm vào biểu tượng **thứ 3 từ trên xuống** (Source Control - hình cây thư mục có chấm tròn)
3. Gõ một dòng ghi chú ngắn gọn vào ô **Message**
   - Ví dụ: *"Cập nhật số liệu doanh thu Q3"*
4. Bấm nút **Commit & Push** (hoặc dấu tích ✔️)

✅ **Xong!** Hệ thống sẽ tự động cập nhật. Bạn chờ khoảng **1-2 phút** rồi vào [link trình chiếu](https://linhlt34.github.io/ll-pitch/) để kiểm tra.

---

## 🛠️ Dành cho Đội ngũ Kỹ thuật (Developer Guide)

Thông tin chi tiết cho việc bảo trì, nâng cấp code và triển khai.

### 📂 Cấu trúc Dự án

project-root/ ├── index.html # Source code chính (HTML/CSS/JS logic) ├── assets/ # Thư mục chứa tài nguyên │ ├── images/ # Hình ảnh, icon, logo │ └── data/ # Dữ liệu biểu đồ (nếu tách riêng) └── README.md # Tài liệu hướng dẫn này

### 💻 Stack Công nghệ

- **Core:** HTML5 Semantic, Vanilla JavaScript (ES6+)
- **Styling:** Tailwind CSS (sử dụng CDN cho tốc độ triển khai nhanh)
- **Visualization:** Chart.js (Biểu đồ động), FontAwesome 6 (Icon set)

### ⚙️ Quy trình Cập nhật (Local Dev)

**Clone repository:**
```bash
git clone https://github.com/linhlt34/ll-pitch.git
Chạy thử: Sử dụng Extension Live Server trên VS Code để xem trước. Deploy:
git add .
git commit -m "Update slides content"
git push origin main