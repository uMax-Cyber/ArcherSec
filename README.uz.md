<div align="center">

[![English](https://img.shields.io/badge/README-English-blue)](README.md)
[![Русский](https://img.shields.io/badge/README-Русский-red)](README.ru.md)
[![Oʻzbekcha](https://img.shields.io/badge/README-Oʻzbekcha-green)](README.uz.md)

</div>

# ArcherSec — Open-source klonlash va tasvirlash majmuasi

Bepul open-source klonlash, disk tasvirlarini yaratish va tiklash yechimi. PXE orqali Windows joylashtirish, PartClone asosida disk tasvirlarini yaratish, mashinalarni veb-interface orqali boshqarish. Imkoniyatlar: xotira va disk testlari, diskni tozalash, antivirus tekshiruvi, vazifalarni rejalashtirish, inventarizatsiya, dasturlarni masofadan oʻrnatish.

## ℹ️ Legacy loyiha

Bu — havola va tarix uchun saqlanib qolgan erta davrdagi PHP asosidagi xavfsizlik va tasvirlash vositalari toʻplami. Faol ravishda qoʻllab-quvvatlanmaydi. Avtomatlashtirish uchun mahsulot darajasidagi voris yondashuvlar yangi repozitoriyalarda joylashgan (OpsPlaybook va boshqalar).

## Imkoniyatlar

| Funksiya | Tavsif |
|----------|--------|
| PXE Boot | Joylashtirish uchun tarmoq orqali yuklash |
| Disk tasvirlari | PartClone asosida tasvir yaratish/tiklash |
| Veb-interface | Markazlashgan boshqaruv |
| Temur testlar | Xotira va disk diagnostikasi |
| Diskni tozalash | Maʼlumotlarni xavfsiz oʻchirish |
| Antivirus | Viruslarni tekshirish |
| Inventarizatsiya | Uskunalar va dasturlarni hisobga olish |
| Masofadan oʻrnatish | Roʻyxatga olingan mashinalarga dasturlar joylashtirish |
| Vazifa rejalashtirish | Rejalashtirilgan tasvirlash va texnik xizmat vazifalari |

## Qoʻllab-quvvatlanadigan OS
Windows XP, Vista, 7, 8, 10 (PXE orqali joylashtirish)

## Tarkibiy qismlar
- `src/` — Asosiy manba kodi (iPXE)
- `bin/` — Oʻrnatuvchi va binar fayllar
- `lib/` — Platforma kutubxonalari (Arch, Red Hat, Ubuntu)
- `utils/` — Yordamchi skriptlar (zaxiralash, iPXE, yangilash)
- `packages/` — Paket tavsiflari, xizmatlar, veb-interface
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

Oʻrnatilgandan soʻng veb-interface Apache document rootidan xizmat koʻrsatadi (standart boʻyicha `/archer/`).

## Litsenziya
GPL-3.0 — [LICENSE](LICENSE) faylini qarang

## 📬 Aloqa
📧 **[allumaxmail@gmail.com](mailto:allumaxmail@gmail.com)**

---

<div align="center">

[![English](https://img.shields.io/badge/README-English-blue)](README.md)
[![Русский](https://img.shields.io/badge/README-Русский-red)](README.ru.md)
[![Oʻzbekcha](https://img.shields.io/badge/README-Oʻzbekcha-green)](README.uz.md)

</div>
