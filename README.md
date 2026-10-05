# Social QA Video

Skill biến một bài hỏi-đáp trên Threads hoặc Facebook thành video dọc 9:16 kiểu TikTok.

## Cài qua Claude Code (plugin)

```
/plugin marketplace add Annie-246/social-qa-video-skill
/plugin install social-qa-video@social-qa-video
```

Sau khi cài, khởi động lại Claude Code để skill được nạp.

## Sau khi cài

Trong thư mục plugin (`skills/social-qa-video`) chạy một lần:

```
npm install
python scripts/fetch_assets.py   # tải clip nền Mixkit vào assets/bg (không lưu trong git)
```

## License

MIT
