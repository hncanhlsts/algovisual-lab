# AlgoVisual Lab - Phòng Thí Nghiệm Trực Quan Thuật Toán & Lập Trình

> **Nền tảng học liệu điện tử tương tác trực quan dành cho học sinh THCS & THPT.**  
> Xây dựng cây cầu tư duy chuyển tiếp mượt mà: **Scratch (Kéo thả) ➔ Python (Tự nhiên) ➔ C++ (Tận sâu bộ nhớ)**.

---

## 🎯 Mục Tiêu Sư Phạm

Đối với học sinh mới học lập trình, rào cản lớn nhất là **tính trừu tượng** của máy tính: không nhìn thấy được biến thay đổi thế nào, con trỏ chạy ra sao và mảng lưu trữ ở đâu trong RAM. 

**AlgoVisual Lab** giải quyết triệt để vấn đề này bằng các mô hình tư duy thực tế (Mental Models):
1. **Biến & Ô nhớ (Variable & Memory):** Ẩn dụ *Chiếc hộp dán nhãn*. Làm rõ sự khác biệt giữa phép gán `=` và phép so sánh `==`. Mô phỏng thanh ghi 4-bytes và địa chỉ ô nhớ RAM trong C++.
2. **Mảng & Hoán đổi (Array & Swap):** Ẩn dụ *Dãy ngăn tủ* và *Cốc nước trung gian (temp)*. Giải thích lý do Scratch đánh số từ `1` còn Python/C++ đánh số từ `0` (offset).
3. **Tìm kiếm Nhị phân (Binary Search):** Ẩn dụ *Chặt đôi cuốn sách / Đoán số kẹp giữa*. Minh họa trực quan độ phức tạp $O(\log_2 N)$.
4. **Sắp xếp Nổi bọt (Bubble Sort):** Ẩn dụ *Bong bóng khí nổi lên mặt nước*. Mô phỏng so găng cặp phần tử liền kề và trượt đổi chỗ.

---

## 🚀 Tính Năng Nổi Bật

- **Rosetta Stone 3 Ngôn Ngữ:** Chuyển đổi linh hoạt giữa khối Scratch chuẩn màu, Python ngắn gọn và C++ định kiểu tĩnh.
- **Dòng Code Sáng Đèn (Active Highlight):** Khi hoạt họa chạy, dòng mã nguồn tương ứng sẽ sáng lên theo thời gian thực.
- **Bộ Điều Khiển Sư Phạm (Step Controller):** Tới từng bước, lùi lại, tạm dừng, điều chỉnh tốc độ từ 0.3s đến 2.0s.
- **Âm Thanh Phản Hồi (Web Audio API):** Âm bíp, pop khi swap, chuông ngân khi tìm thấy phần tử giúp tăng hứng thú học tập.
- **100% Chạy Offline & Độc Lập:** Không cần cài đặt node_modules hay server backend, tương thích mọi trình duyệt hiện đại.

---

## 🌐 Triển Khai GitHub Pages (Để Học Sinh Truy Cập Online)

1. Đẩy mã nguồn lên kho lưu trữ GitHub của bạn:
   ```bash
   git init
   git add .
   git commit -m "Phát hành AlgoVisual Lab v1.0"
   git branch -M main
   git remote add origin https://github.com/<tai-khoan-cua-ban>/algovisual-lab.git
   git push -u origin main
   ```
2. Bật **GitHub Pages**:
   - Vào repository trên GitHub: **Settings** ➔ **Pages**.
   - Tại mục **Build and deployment** > **Branch**, chọn nhánh `main` và thư mục `/ (root)`.
   - Nhấn **Save**.
3. Đường link website trực tuyến của bạn sẽ có dạng:  
   `https://<tai-khoan-cua-ban>.github.io/algovisual-lab/`  
   *(Chia sẻ link này cho học sinh để các em mở trên điện thoại, máy tính bảng hoặc máy tính phòng Tin học)*.

---

## 👨‍🏫 Dành Cho Giáo Viên Tin Học

- Hãy dùng nút **`[⏩ Tới 1 bước]`** để kích hoạt phương pháp **"Predict First" (Dự đoán trước khi bấm)**: hỏi học sinh kết quả trước khi cho máy tính hiển thị.
- Bấm nút **"Góc Giáo Viên"** trên giao diện để xem các mẹo sư phạm chi tiết.
