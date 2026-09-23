# Simple Study Exam Site

Bu loyiha Vercel uchun ataylab juda sodda qilindi. Hech qanday `npm install` talab qilinmaydi.

## Fayllar

Loyiha ildiziga shu 3 ta faylni qo'ying:

- `slayd.pptx` — `/slayd` sahifasida PowerPoint Online orqali ochiladi.
- `site.pdf` — `/site` sahifasida brauzer PDF viewer'i orqali ochiladi.
- `kitob.pdf` — `/kitob` sahifasida 3D varaqlanadigan kitob sifatida ochiladi.

## Muhim

`site.pdf` ichidagi istalgan matnga `https://SIZNING-DOMENINGIZ.vercel.app/slayd` linkini qo'ysangiz, telefon yoki kompyuterda PDF'dagi link bosilganda `/slayd` ochiladi.

Kitob uchun `kitob.pdf` kerak. `kitob` sahifasi PDF.js CDN'dan foydalanadi, shuning uchun internet kerak.

## Vercel

GitHub'ga barcha fayllarni yuklang va Vercel'da repo'ni import qiling. Build command kerak emas, framework ham kerak emas (Static).

## URL'lar

- `/` — bosh sahifa
- `/slayd` — PPTX
- `/site` — PDF
- `/kitob` — kitob
