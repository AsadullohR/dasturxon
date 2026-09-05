# Bir Oylik Dasturxon

Bir oylik o'zbek dasturxoni — 4 haftalik ovqat rejasi (ertalab, tushlik, kechki),
har yakshanba maxsus tantanali taom bilan.

**Live:** https://asadullohr.github.io/dasturxon/

## Nima bor

- 4 hafta x 7 kun x 3 mahal ovqat jadvali
- "Yangilash" — bir hafta yoki butun oyni tasodifiy qayta tuzish
- "PDF yuklash" — brauzer chop etish oynasi orqali A4 landshaft PDF (har hafta alohida sahifa)
- Yorug'/qorong'i rejim, mobil uchun gorizontal skroll

## Ishga tushirish

Bu bitta statik HTML fayl. Hech qanday build yoki bogliqlik yoq:

```bash
python -m http.server 8000
# keyin http://localhost:8000
```

Yoki `index.html` faylni brauzerda ochish kifoya.

## Deploy

`main` ga push qilinganda GitHub Pages avtomatik yangilanadi.
