# Ứng dụng Luyện Toán Lớp 4

Ứng dụng web đơn giản giúp các em học sinh lớp 4 luyện tập các phép tính cơ bản.

## Tính năng

✅ **Phép tính:**
- Cộng (+)
- Trừ (-)
- Nhân (×)
- Chia hết (÷)
- Chia có dư

✅ **Cài đặt linh hoạt:**
- Chọn loại phép tính muốn luyện
- Tùy chỉnh phạm vi số (ví dụ: từ 1 đến 100)

✅ **Theo dõi tiến độ:**
- Lịch sử chi tiết các bài đã làm
- Hiển thị thời gian làm từng bài
- Đánh dấu đúng/sai
- Thống kê theo ngày (tổng số bài, số bài đúng, tỷ lệ đúng, thời gian trung bình)

✅ **Lưu trữ:**
- Dữ liệu được lưu trong trình duyệt (localStorage)
- Không cần đăng nhập hay kết nối internet

## Cách sử dụng

1. Mở file `index.html` trong trình duyệt
2. Chọn các phép tính muốn luyện
3. Nhập phạm vi số (ví dụ: từ 1 đến 100)
4. Nhấn "Bắt đầu bài mới"
5. Nhập đáp án và nhấn "Kiểm tra" hoặc Enter
6. Xem lịch sử và thống kê ở bảng bên phải

## Deploy lên Cloudflare Pages

### Cách 1: Sử dụng GitHub

1. Push code lên GitHub repository
2. Đăng nhập vào [Cloudflare Dashboard](https://dash.cloudflare.com/)
3. Vào **Pages** → **Create a project** → **Connect to Git**
4. Chọn repository
5. Build settings:
   - Build command: (để trống)
   - Build output directory: `/phep-tinh`
6. Deploy!

### Cách 2: Deploy trực tiếp (Drag & Drop)

1. Đăng nhập vào [Cloudflare Dashboard](https://dash.cloudflare.com/)
2. Vào **Pages** → **Create a project** → **Upload assets**
3. Kéo thả folder `phep-tinh` vào
4. Deploy!

## Deploy lên các nền tảng khác

### Netlify
- Kéo thả folder `phep-tinh` vào [Netlify Drop](https://app.netlify.com/drop)

### Vercel
- Import repository hoặc kéo thả folder vào [Vercel](https://vercel.com/new)

### GitHub Pages
1. Push code lên GitHub
2. Vào **Settings** → **Pages**
3. Chọn branch và folder `/phep-tinh`
4. Save

## Công nghệ sử dụng

- HTML5
- CSS3 (Responsive design)
- Vanilla JavaScript (không cần framework)
- LocalStorage API

## Tương thích

- Hoạt động trên mọi trình duyệt hiện đại (Chrome, Firefox, Safari, Edge)
- Responsive trên cả desktop và tablet
- Không cần internet sau khi tải trang

## License

Free to use for educational purposes.
