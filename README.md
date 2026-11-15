# Khám phá Claude Code — Bản tiếng Việt (HTML tĩnh)

Bản dịch tiếng Việt của [Explore Claude Code](https://github.com/LukeRenton/explore-claude-code) (Luke Renton, MIT), dựng thành HTML tĩnh hoàn toàn, **không có JavaScript**. Mở thẳng `index.html` là xem được, không cần web server.

## Cấu trúc thư mục

```
index.html          Trang chào mừng
assets/             style.css, favicon.png
project/            Các file ở gốc dự án: CLAUDE.md, .mcp.json, src/index.ts
claude/             Hệ sinh thái .claude/ (thứ bạn tự tạo)
  settings.html
  rules/ skills/ agents/ commands/ hooks/ plugins/ mods/
built-in/           Tính năng có sẵn của Claude Code
  auto-memory.html
  modes/ context/ keyboard/ cli/ bundled-skills/ commands/
```

Quy ước:

- Mỗi chủ đề là một thư mục; trang tổng quan của chủ đề là `index.html` trong thư mục đó.
- Trang con là file `.html` cùng cấp, đặt tên theo thuật ngữ trong Claude Code docs (`plan-mode.html`, `code-review.html`…).
- Mọi liên kết đều tương đối, nên site chạy được ở bất kỳ đường dẫn nào (gốc domain, thư mục con, hay mở file trực tiếp).

## Cập nhật nội dung

Menu bên trái được nhúng sẵn trong mọi trang. Sửa nội dung một trang chỉ cần sửa file đó; nhưng khi **thêm, xoá hoặc đổi tên** trang, menu ở các trang khác cũng phải cập nhật theo.

## Đưa lên GitHub Pages

1. Đẩy toàn bộ các file và thư mục này lên gốc repo (giữ nguyên cấu trúc).
2. Settings → Pages → *Deploy from a branch* → `main` / `(root)`.

Giấy phép MIT — xem `LICENSE`.
