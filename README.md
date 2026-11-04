# Eldorjon & Bonuxon — to'y taklifnomasi

Statik sayt: bitta `index.html`, musiqa `music.m4a`, ulashish rasmi `og.png`.
Hech qanday build kerak emas.

## Vercel'ga joylash

1. https://vercel.com saytida ro'yxatdan o'ting (GitHub orqali bo'lsa ham bo'ladi).
2. Terminalda shu papkada:

```bash
npx vercel
```

   Savollarga `Enter` bilan javob bering (Framework: Other, Output: `.`).
   Birinchi marta brauzer orqali login so'raydi.

3. Ishlab chiqarish (production) uchun:

```bash
npx vercel --prod
```

Yoki vercel.com → "Add New Project" → papkani drag-and-drop qiling.

## Mehmonga shaxsiy havola

Havola oxiriga `?mehmon=Ism` qo'shing:

```
https://sizning-domen.vercel.app/?mehmon=Sardorbek%20va%20oilasi
```

Sahifaning "Taklifnomani ulashing" bo'limi buni avtomatik yaratadi va Telegram orqali yuboradi.

## Fayllar

- `index.html` — butun sahifa (CSS va JS ichida)
- `music.m4a` — 10 soniyalik fon musiqasi, takrorlanadi (166 KB)
- `og.png` / `og.svg` — Telegram/WhatsApp'da havola ko'rinishi uchun rasm
- `img/oqsaroy-night.jpg`, `img/oqsaroy-day.jpg` — to'yxona rasmlari (Google Maps)
- `vercel.json` — kesh va xavfsizlik sarlavhalari
- `_old/index.old.html` — eski versiya (deploy qilinmaydi)
- `music.mp4` — asl video (deploy qilinmaydi, `.vercelignore` ga kiritilgan)
