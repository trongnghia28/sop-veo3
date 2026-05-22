# SOP Workflow Video AI — VEO 3 + Nano Banana

Quy trình 7 bước build Custom GPT cho kênh video AI dùng Google Flow (Nano Banana tạo ảnh + VEO 3 image-to-video native audio).

## 📄 2 trang

| Trang | Mô tả |
|-------|-------|
| **`index.html`** | SOP 7 bước build Custom GPT cho kênh video AI |
| **`prompt-thoi-trang.html`** | Cheat sheet prompt thời trang (tách/ghép trang phục · tạo người mẫu · tăng nét) |

## 🚀 Workflow tổng

1. **DNA kênh** — lock 10 yếu tố nhận diện
2. **Nhân vật chính** — gen 6 ảnh ref đa góc trong Flow (Nano Banana)
3. **Test cảnh** — pipeline (A) Image Nano Banana → (B) MOTION/Voice VEO 3
4. **Đóng gói Custom GPT** — output kịch bản 2 BLOCK
5. **Test GPT structure** — verify output đúng format
6. **Test gen thực tế** — gen ảnh + video trong Flow
7. **Dùng luôn** — mỗi clip mới ~10 phút

## 💻 Chạy local

Mở `index.html` trực tiếp bằng browser. Không cần build, không cần server.

## 🌐 Deploy Vercel

Vercel tự serve static HTML. Connect repo này, Vercel sẽ auto-deploy.

- Trang chính: `index.html` (default route `/`)
- Trang phụ: `prompt-thoi-trang.html` (`/prompt-thoi-trang.html`)

## 🛠 Tech

- HTML/CSS/JS thuần, không framework
- LocalStorage cho progress checkbox + scroll position
- Mobile responsive
- Print-friendly
