# Khám phá Claude Code — Tiếng Việt

Hướng dẫn Claude Code bằng tiếng Việt, dạng HTML tĩnh **không có JavaScript**. Mỗi file và thư mục ở thanh bên là một khái niệm thật của Claude Code, bám theo cấu trúc trong [Claude Code docs](https://code.claude.com/docs/en/claude-directory). Mở thẳng `index.html` là xem được, không cần web server.

## Cấu trúc thư mục

```
index.html          Trang chào mừng
assets/             style.css, favicon.png
project/            File ở gốc dự án: CLAUDE.md, CLAUDE.local.md, AGENTS.md,
                    .mcp.json, .worktreeinclude, src/index.ts
claude/             Hệ sinh thái .claude/ của dự án
  settings.html, settings-local.html, agent-memory.html
  rules/ skills/ agents/ commands/ hooks/ output-styles/ workflows/ plugins/ mods/
built-in/           Tính năng có sẵn của Claude Code
  auto-memory.html
  modes/ context/ keyboard/ cli/ bundled-skills/ commands/
global/             Máy của bạn: ~/.claude, ~/.claude.json, managed settings,
                    keybindings, theme, dữ liệu ứng dụng
```

Quy ước:

- Mỗi chủ đề là một thư mục; trang tổng quan của chủ đề là `index.html` trong thư mục đó.
- Trang con là file `.html` cùng cấp, đặt tên theo thuật ngữ trong Claude Code docs (`plan-mode.html`, `code-review.html`…).
- Mọi liên kết đều tương đối, nên site chạy được ở bất kỳ đường dẫn nào.

## Cập nhật nội dung

Menu bên trái được nhúng sẵn trong mọi trang. Sửa nội dung một trang chỉ cần sửa file đó; khi **thêm, xoá hoặc đổi tên** trang, menu ở các trang khác cũng phải cập nhật theo.

## Đưa lên GitHub Pages

1. Đẩy toàn bộ file và thư mục này lên gốc repo (giữ nguyên cấu trúc).
2. Settings → Pages → *Deploy from a branch* → `main` / `(root)`.

## Giấy phép

Phát triển từ dự án mã nguồn mở Explore Claude Code (MIT). Xem `LICENSE`.
