# Sự thức giấc của Tiny - Ngày 20/10

Mã nguồn trang web kỷ niệm ngày Phụ nữ Việt Nam 20/10 ("Sự thức giấc của Tiny").

- **Nguồn gốc**: [https://20-10-vuive.kazvndc-edu.workers.dev/](https://20-10-vuive.kazvndc-edu.workers.dev/)
- **Đặc điểm**:
  - Trang web độc lập (Standalone Single Page Application) tích hợp toàn bộ HTML, CSS, JavaScript, hoạt ảnh SVG, audio/video và hình ảnh dạng base64.
  - Tối ưu hiệu năng trên cả thiết bị di động và máy tính (`window.TINY_PERF`).
  - Font chữ: Courier Prime (Google Fonts).

## Cách chạy

Chỉ cần mở trực tiếp file `index.html` bằng bất kỳ trình duyệt web nào (Chrome, Edge, Firefox, Safari) hoặc chạy thông qua một HTTP server cục bộ:

```bash
# Sử dụng Python
python -m http.server 8000

# Hoặc sử dụng Node.js (npx)
npx serve .
```

Sau đó truy cập `http://localhost:8000` trên trình duyệt.
