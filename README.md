# Sổ tay Claude Code

Hướng dẫn Claude Code bằng tiếng Việt, dạng HTML tĩnh **không có JavaScript**. Mở thẳng `index.html` là xem được, không cần web server.

- **Hướng dẫn**: bài viết theo danh mục: Bắt đầu, Kiến trúc, Tư duy, Mẹo & thủ thuật, và nhật ký Có gì mới
- **Tham chiếu**: mô phỏng một dự án thật; mỗi file và thư mục là một khái niệm của Claude Code, bám theo [Claude Code docs](https://code.claude.com/docs/en/claude-directory)

> Trang chia sẻ cá nhân, không phải tài liệu chính thức của Anthropic.

## Cấu trúc thư mục

```
index.html          Trang chủ
changelog.html      Nhật ký cập nhật (Có gì mới)
assets/             style.css, favicon (svg, png), apple-touch-icon
getting-started/    Hướng dẫn: Bắt đầu        (index.html = tổng quan danh mục)
architecture/       Hướng dẫn: Kiến trúc
mindset/            Hướng dẫn: Tư duy
tips/               Hướng dẫn: Mẹo & thủ thuật
project/            Tham chiếu: file ở gốc dự án (CLAUDE.md, AGENTS.md, .mcp.json…)
claude/             Tham chiếu: hệ sinh thái .claude/ của dự án
built-in/           Tham chiếu: tính năng có sẵn của Claude Code
global/             Tham chiếu: máy của bạn (~/.claude, managed settings…)
```

Quy ước: mỗi chủ đề là một thư mục, trang tổng quan là `index.html` trong thư mục đó; tên file và thư mục bằng tiếng Anh; mọi liên kết đều tương đối.

## Cập nhật nội dung

Menu bên trái được nhúng sẵn trong mọi trang, nên khi **thêm, xoá hoặc đổi tên** trang, cả bộ cần được dựng lại để menu khớp.

## Đưa lên GitHub Pages

1. Đẩy toàn bộ file và thư mục này lên gốc repo (giữ nguyên cấu trúc).
2. Settings → Pages → *Deploy from a branch* → `main` / `(root)`.

## Giấy phép

Phần Tham chiếu phát triển từ dự án mã nguồn mở Explore Claude Code (MIT). Xem `LICENSE`.
