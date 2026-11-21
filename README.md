# 🪷 Tâm Thoại & Chuyển Hóa Tà Niệm (2026)

Ứng dụng web đơn tệp (`index.html`) theo phong cách Thiền định tối giản, hỗ trợ nhận diện và chuyển hóa các niệm bất thiện xen ngang khi tâm đang đối thoại — chạy mượt mà **offline**, không cần cài đặt thư viện hay backend, tương thích tốt trên **Acode**, **TrebEdit** và **GitHub Pages**.

---

## ✨ Tính năng chính

- **🌿 Soi Niệm & Chuyển Hóa:** Ghi lại hoặc chọn nhanh các niệm thường gặp (sân hận, ganh tị, tham ái, hoài nghi/chán nản, tán loạn) để quán chiếu qua 3 bước: *Tỉnh giác (Biết rõ)* → *Vô thường (Không đồng nhất)* → *Chuyển hóa (Nuôi thiện niệm)* và lưu vào nhật ký.
- **🌬️ Neo Tâm Vào Hơi Thở:** Bài tập quán thở nhịp nhàng (`4s` hít vào — `2s` giữ nhẹ — `4s` thở ra) giúp giảm căng thẳng và kéo tâm về hiện tại.
- **📿 Tràng Hạt 108:** Lần hạt chánh niệm theo từng câu nhiếp tâm tùy chọn, tự động tính số vòng hoàn thành (`108` hạt/vòng).
- **📖 Nhật Ký Chuyển Hóa:** Lưu trữ cục bộ (`localStorage`) ngay trên thiết bị, không gửi dữ liệu ra ngoài.
- **🔔 Chuông Chánh Niệm (Web Audio API):** Tạo âm thanh chuông nhẹ nhàng hoàn toàn ngoại tuyến khi bật.

---

## 📱 Hướng dẫn chạy trên điện thoại (Acode & TrebEdit)

1. Mở **Acode** hoặc **TrebEdit** trên điện thoại.
2. Tạo tệp mới đặt tên chính xác là `index.html` (và `README.md` nếu muốn lưu tài liệu).
3. Dán toàn bộ mã nguồn vào tệp và lưu lại (`Ctrl + S` hoặc biểu tượng Lưu).
4. Nhấn nút **Play / Preview (Chạy)** để mở trang web trực tiếp trên trình duyệt hoặc khung xem trước của trình soạn thảo.

---

## 🌐 Xuất bản trực tuyến với GitHub Pages

1. Tạo một **Repository** mới trên **GitHub** (ví dụ: `tam-thoai-chuyen-hoa`).
2. Tải tệp `index.html` (và `README.md`) lên nhánh `main`.
3. Vào **Settings → Pages**.
4. Tại mục **Build and deployment / Branch**, chọn nhánh **`main`** và thư mục **`/(root)`**, sau đó nhấn **Save**.
5. Chờ vài giây để GitHub cấp liên kết dạng `https://<ten-nguoi-dung>.github.io/<ten-repo>/` và truy cập.

---

## 📂 Cấu trúc dự án

```text
.
├── index.html   # Toàn bộ giao diện, logic quán chiếu, quán thở, tràng hạt & nhật ký
└── README.md    # Tài liệu hướng dẫn sử dụng
