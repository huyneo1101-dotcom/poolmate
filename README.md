# PoolMate — Kết nối & ghép cặp cơ thủ bi-a 🎱

Web app tìm đối bi-a (Hà Nội): ghép theo **trình / khu vực / mục đích**, chat, xếp hạng **ELO**, **giải đấu** (bracket, giới hạn hạng, nhà tài trợ), **chợ gậy**, **check-in CLB (định vị)**, **kết quả billiards** (Việt Nam + Matchroom World Nineball Tour)…

- **Mở app:** trang **GitHub Pages** của repo này (Settings → Pages).
- Bản **web tĩnh 1 file** (`index.html`, React + Leaflet + Supabase qua CDN) — không cần build.
- Là **PWA**: mở trên điện thoại có thể **cài như app** + chạy offline.

## File
`index.html` · `manifest.json` · `sw.js` · `icon.svg`

> Backend dùng Supabase (đăng nhập Email OTP, dữ liệu dùng chung realtime). Đăng nhập cần làm bước email-template trong Supabase.
