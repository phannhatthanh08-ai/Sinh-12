# Hệ Thống Ôn Tập Điểm 10 Sinh Học 12 (Kết Nối Tri Thức) - Vercel Deployment

Bộ tài liệu ôn tập trọn bộ 8 chương (20 chuyên đề & 7 file đề cương Word). Dự án đã được đóng gói chuẩn cấu hình để đưa lên **Vercel** hoạt động ngay lập tức 100%.

> **Đảm bảo tính toàn vẹn dữ liệu:** Toàn bộ nội dung file HTML gốc được giữ nguyên 100% (mã băm SHA-256 đối chiếu hoàn toàn trùng khớp từng byte).

---

## 📁 Cấu trúc thư mục

```text
sinh_hoc_12_vercel/
├── index.html                                                                                           # File chính để Vercel tự động nhận diện trang chủ (bản sao chính xác 100% của file gốc)
├── h_th_ng_n_t_p_i_m_10_sinh_h_c_12_k_t_n_i_tri_th_c_tr_n_b_8_ch_ng_20_chuy_n_7_file_c_ng_word.html  # File gốc giữ nguyên tên và nội dung
├── vercel.json                                                                                          # Cấu hình định tuyến, Clean URLs và Security Headers chuẩn Vercel
├── package.json                                                                                         # Khai báo thông tin dự án phục vụ Vercel build
├── .gitignore                                                                                           # Bỏ qua các file rác khi đẩy lên Git
└── README.md                                                                                            # Hướng dẫn chi tiết
```

---

## 🚀 Hướng dẫn triển khai lên Vercel

### Cách 1: Đẩy lên GitHub rồi kết nối Vercel (Khuyên dùng - Nhanh & Miễn phí vĩnh viễn)

1. **Tạo repository mới trên GitHub:**
   - Truy cập [github.com/new](https://github.com/new) và tạo 1 repo mới (ví dụ: `sinh-hoc-12-on-tap`).
2. **Tải các file lên repository:**
   - Chọn **Add file** -> **Upload files**.
   - Kéo toàn bộ các file trong thư mục này vào trình duyệt rồi bấm **Commit changes**.
3. **Kết nối và triển khai với Vercel:**
   - Truy cập [vercel.com](https://vercel.com) và đăng nhập bằng tài khoản GitHub.
   - Nhấn **Add New...** -> **Project**.
   - Chọn repository `sinh-hoc-12-on-tap` vừa tạo -> Nhấn **Import**.
   - Giữ nguyên toàn bộ cấu hình mặc định (Framework: **Other**) -> Nhấn **Deploy**.
   - Sau 10–20 giây, website của bạn sẽ hoạt động với đường dẫn miễn phí dạng:  
     `https://sinh-hoc-12-on-tap.vercel.app`

---

### Cách 2: Triển khai trực tiếp qua Vercel CLI (Nếu máy có cài Node.js / Vercel CLI)

Mở PowerShell tại thư mục này và chạy lệnh:

```bash
# Đăng nhập Vercel (nếu chưa đăng nhập)
npx vercel login

# Triển khai dự án lên môi trường Production
npx vercel --prod
```

Hệ thống sẽ tự động xuất bản website và cung cấp URL truy cập ngay lập tức!
