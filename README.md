# Emma – Trợ lý tiếng Anh AI

Gia sư tiếng Anh chạy trên web: trò chuyện, **gọi thoại live với robot Emma** (miệng mấp máy theo lời, phụ đề tô từng từ), sửa lỗi, sổ từ vựng, theo dõi tiến độ.

## Bộ não AI
- **AI local trong trình duyệt** (mặc định): Qwen2.5 1.5B chạy bằng WebGPU qua [WebLLM](https://github.com/mlc-ai/web-llm). Lần đầu tải ~1 GB, sau đó chạy offline. Cần Chrome hoặc Edge.
- **Ollama** trên máy (đặt `OLLAMA_ORIGINS=*` khi dùng bản online).
- **Claude** (cloud): mỗi người tự nhập Anthropic API key của mình; key chỉ lưu trong trình duyệt của họ.

Mọi dữ liệu (lịch sử, sổ từ, cài đặt) chỉ lưu trong trình duyệt của người dùng.

## Chạy trên máy
```
node server.js
```
rồi mở http://localhost:5173

## Đăng lên GitHub Pages
Settings → Pages → Build and deployment → Deploy from a branch → `main` / `/docs`.
