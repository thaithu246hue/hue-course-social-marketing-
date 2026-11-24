# Hue Course Social Content — Claude Skill

Skill cho Claude giúp **viết content mạng xã hội bán khóa học marketing** dành cho **chủ doanh nghiệp tại Huế** (quán ăn, cà phê, homestay, du lịch, đặc sản, spa, bán lẻ…).

## Skill làm được gì
- Bài đăng Facebook (fanpage, group, trang cá nhân), caption Instagram.
- Kịch bản video ngắn TikTok / Reels / YouTube Shorts.
- Tin nhắn Zalo OA, bình luận chốt đơn.
- Mẫu quảng cáo Facebook kèm biến thể A/B.
- Lịch nội dung và chuỗi bài cho chiến dịch tuyển sinh.
- Giọng văn "chất Huế": nhẹ nhàng, chân thành, có chi tiết địa phương; không bịa số liệu, không hứa hẹn quá đà.

## Cấu trúc
```
hue-course-social-content/
├── SKILL.md                     # Quy trình, giọng văn, quy tắc, checklist
└── references/
    ├── hue-audience.md          # Chân dung khách hàng, nỗi đau theo ngành, mùa vụ Huế
    ├── copy-frameworks.md       # PAS, AIDA, BAB, 4U, storytelling, xử lý phản đối
    ├── platform-guides.md       # Quy tắc từng nền tảng, hashtag, lịch nội dung
    └── templates.md             # Mẫu bài và ví dụ hoàn chỉnh
```

## Cài đặt

**Claude Code** — sao chép thư mục skill vào thư mục skills:
```bash
git clone https://github.com/thaithu246hue/hue-course-social-marketing-.git
cp -r hue-course-social-marketing-/hue-course-social-content ~/.claude/skills/
```

**Claude.ai** — nén thư mục `hue-course-social-content` thành file `.zip` rồi tải lên tại *Settings → Capabilities → Skills*.

## Ví dụ yêu cầu
- "Viết 3 bài Facebook tuyển sinh khóa Marketing Thực Chiến cho chủ homestay ở Huế, khai giảng 15/12."
- "Làm kịch bản TikTok 45 giây về mẹo giữ khách mùa mưa cho quán ăn Huế."
- "Lên lịch nội dung 4 tuần cho chiến dịch tuyển sinh tháng 1."

## Giấy phép
MIT
