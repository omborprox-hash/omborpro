# OmborPro

Ulgurji savdo ombori boshqaruvi: mahsulotlar, sotuv, mijozlar, qarzdorlar, xarajatlar, sotuvchilar, mijozlar ilovasi.

- Ma'lumotlar bazasi: Firebase Firestore (`omborprox-554a3`)
- Kirish: Firebase Authentication (Email/Password)
- Hosting: GitHub Pages

## Havolalar

| Kim | Manzil |
|---|---|
| Administrator | `https://omborprox-hash.github.io/omborpro/` |
| Sotuvchilar (telefon) | `https://omborprox-hash.github.io/omborpro/#xodim` |
| Mijozlar ilovasi | `https://omborprox-hash.github.io/omborpro/#ilova` |

## Fayllar

- `index.html` — butun dastur
- `firestore.rules` — xavfsizlik qoidalari (Firebase Console → Firestore → Rules ga nusxalanadi)
- `*.webmanifest`, `icon*` — telefonga ilova sifatida o'rnatish uchun

`firebaseConfig` maxfiy emas — ma'lumotlarni `firestore.rules` himoya qiladi.
Tannarxlar, mijozlar ro'yxati va parollarni bu repoga **qo'ymang**.
