<div align="center">

[![English](https://img.shields.io/badge/README-English-blue)](README.md)
[![Русский](https://img.shields.io/badge/README-Русский-red)](README.ru.md)
[![Oʻzbekcha](https://img.shields.io/badge/README-Oʻzbekcha-green)](README.uz.md)

</div>

# ArcherSec — Open-source klonlash va tasvirlash majmuasi

Bepul open-source yechim: kompyuterlarni klonlash, disk tasvirlarini yaratish va tiklash. Windows PXE orqali joylashtiriladi, tasvirlar PartClone bilan yaratiladi, barcha mashinalar veb-interface orqali boshqariladi. Qoʻshimcha imkoniyatlar: xotira va disk testlari, diskni tozalash (wipe), antivirus tekshiruvi, vazifalarni rejalashtirish, inventarizatsiya va dasturlarni masofadan oʻrnatish.

## ℹ️ Legacy loyiha

Bu — PHP asosidagi ilk xavfsizlik va tasvirlash vositalari toʻplami, havola va tarix uchun saqlanadi. Faol qoʻllab-quvvatlanmaydi. Avtomatlashtirishning zamonaviy, ishonchli yondashuvlari yangi repozitoriyalarda (OpsPlaybook va boshqalar).

## Imkoniyatlar

| Funksiya | Tavsif |
|----------|--------|
| PXE Boot | Kompyuter tarmoqdan yuklanadi va joylashtiriladi |
| Disk tasvirlari | Tasvirlar PartClone asosida yaratiladi va tiklanadi |
| Veb-interface | Barcha mashinalar bir joydan boshqariladi |
| Xotira/disk testlari | Jihozlar diagnostika qilinadi |
| Diskni tozalash | Maʼlumotlar qaytarib boʻlmas darajada oʻchiriladi (wipe) |
| Antivirus | Viruslar tekshiriladi |
| Inventarizatsiya | Uskuna va dasturlar roʻyxati yuritiladi |
| Masofadan oʻrnatish | Roʻyxatdagi mashinalarga dasturlar joylashtiriladi |
| Vazifa rejalashtirish | Tasvirlash va texnik xizmat reja boʻyicha bajariladi |

## Qoʻllab-quvvatlanadigan OS
Windows XP, Vista, 7, 8, 10 (PXE orqali joylashtirish)

## Tarkibiy qismlar
- `src/` — Asosiy manba kod (iPXE)
- `bin/` — Oʻrnatuvchi va binar fayllar
- `lib/` — Platforma kutubxonalari (Arch, Red Hat, Ubuntu)
- `utils/` — Yordamchi skriptlar (backup, iPXE, updater)
- `packages/` — Paket tavsiflari, servislar, veb-interface
- `SELinux/` — Xavfsizlik siyosatlari

## Skrinshot

![Namoyish](screenshots/demo.svg)

## Foydalanish

```bash
# Oʻrnatish (root huquqi bilan; Arch, Red Hat, Ubuntu qoʻllanadi)
cd bin && sudo ./installarcher.sh

# Olib tashlash
sudo ./installarcher.sh --uninstall
```

Oʻrnatilgach, veb-interface Apache document root orqali xizmat qiladi (standart: `/archer/`).

## Litsenziya
GPL-3.0 — batafsil [LICENSE](LICENSE) faylida

## 📬 Aloqa
📧 **[allumaxmail@gmail.com](mailto:allumaxmail@gmail.com)**

---

<div align="center">

[![English](https://img.shields.io/badge/README-English-blue)](README.md)
[![Русский](https://img.shields.io/badge/README-Русский-red)](README.ru.md)
[![Oʻzbekcha](https://img.shields.io/badge/README-Oʻzbekcha-green)](README.uz.md)

</div>
