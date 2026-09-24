# Loyiha akademiyasi — Netlify to‘liq platformasi

Bu loyiha birinchi privat platformadagi asosiy funksiyalarni Netlify uchun qayta tayyorlaydi:

- talaba va o‘qituvchi email/parol bilan hisob yaratishi va kirishi;
- talabalar mashq hamda yozma amaliy javoblarini yuborishi;
- natijalar kabinetida saqlanishi;
- o‘qituvchi barcha javoblarni ko‘rishi, 2–5 baho va izoh berishi;
- o‘qituvchi yangi matnli material hamda 3 MB gacha bo‘lgan fayl yuklashi;
- 11 mavzu, ma’ruza, asl taqdimotlar, amaliy fayllar, metodlar va o‘yinlar.

## Netlifyga joylash

1. ZIPni ochib, loyiha ildizini GitHub yoki Netlifyga yuklang.
2. Netlify avtomatik ravishda `package.json` dagi kerakli paketni o‘rnatadi.
3. Project configuration → Environment variables bo‘limida `TEACHER_SETUP_KEY` nomli kamida 24 belgili maxfiy kalit yarating.
4. Saytda **O‘qituvchi sozlash** menyusini ochib, o‘z email/parolingiz va shu kalit bilan birinchi o‘qituvchi hisobini yarating.
5. Talabalar keyin **Talaba ro‘yxati** orqali hisob ochishi mumkin.

Netlify Blobs avtomatik saqlashdan foydalanadi; ma’lumotlar keyingi deploylarda saqlanadi. Fayl yuklash uchun bitta fayl hajmi 3 MB bilan cheklangan.
