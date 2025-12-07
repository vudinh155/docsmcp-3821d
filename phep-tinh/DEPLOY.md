# 📱 Hướng dẫn Deploy từ Điện thoại

## Cách nhanh nhất: Netlify (1 click)

**Bước 1:** Click vào nút này từ điện thoại:

👉 [DEPLOY TO NETLIFY](https://app.netlify.com/start/deploy?repository=https://github.com/vudinh155/docsmcp&base=phep-tinh)

**Bước 2:**
- Đăng nhập Netlify (có thể dùng GitHub account)
- Click "Connect to GitHub"
- Authorize Netlify
- Click "Save & Deploy"

**Xong!** App sẽ live trong vài giây tại URL kiểu: `https://your-app-name.netlify.app`

---

## Cách 2: GitHub Pages (Tự động)

Tôi đã setup GitHub Actions để tự động deploy!

**Bước để enable (chỉ cần làm 1 lần):**

1. Mở trình duyệt trên điện thoại
2. Vào: https://github.com/vudinh155/docsmcp/settings/pages
3. Ở phần "Source", chọn: **GitHub Actions**
4. Save

**Xong!** Mỗi khi push code mới, app sẽ tự động deploy lên:
`https://vudinh155.github.io/docsmcp/`

---

## Cách 3: Cloudflare Pages (Miễn phí, nhanh)

1. Vào: https://dash.cloudflare.com/pages (từ điện thoại)
2. Click "Create a project"
3. Click "Connect to Git"
4. Chọn repo: `vudinh155/docsmcp`
5. Branch: `claude/math-practice-app-017eX2bwZPrfb1ekjM749C2g`
6. Build output directory: `phep-tinh`
7. Click "Save and Deploy"

**Xong!** App sẽ live tại `https://your-project.pages.dev`

---

## So sánh

| Platform | Tốc độ | Dễ dùng | Free |
|----------|--------|---------|------|
| **Netlify** | ⚡⚡⚡ Nhanh nhất | ⭐⭐⭐ Dễ nhất | ✅ Có |
| **GitHub Pages** | ⚡⚡ Nhanh | ⭐⭐ Trung bình | ✅ Có |
| **Cloudflare** | ⚡⚡⚡ Rất nhanh | ⭐⭐ Trung bình | ✅ Có |

**Khuyên dùng:** Netlify - click 1 cái là xong!
