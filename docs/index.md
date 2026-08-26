# qr.ol.uz hujjatlari

**qr.ol.uz** — kompaniyalar o'z xodimlarining xarajatlarini boshqarishi va xodimlar hamkor do'konlarda QR kod orqali to'lov qilishi uchun mo'ljallangan to'lov platformasi.

Platformada uch turdagi akkaunt mavjud. Bitta telefon raqami bilan bir nechta akkauntga ega bo'lishingiz va ular o'rtasida bemalol almashishingiz mumkin:

<div class="grid cards" markdown>

- :material-office-building:{ .lg .middle } **Kompaniya**

    ---

    Kompaniya balansini to'ldiring, xodimlarga mablag' taqsimlang va xarajat toifalarini boshqaring.

    [:octicons-arrow-right-24: Kompaniya qo'llanmasi](kompaniya.md)

- :material-briefcase:{ .lg .middle } **Xodim**

    ---

    Sizga ajratilgan mablag' hisobidan hamkor do'konlarda QR kod orqali to'lov qiling.

    [:octicons-arrow-right-24: Xodim qo'llanmasi](xodim.md)

- :material-qrcode:{ .lg .middle } **Merchant**

    ---

    QR to'lovlarni qabul qiling, kassalar va tushumingizni kuzatib boring.

    [:octicons-arrow-right-24: Merchant qo'llanmasi](merchant.md)

</div>

## Qanday ishlaydi?

1. **Kompaniya** [inbiz.uz](https://inbiz.uz/uz/) orqali ro'yxatdan o'tadi, balansini bank o'tkazmasi bilan to'ldiradi va xodimlariga mablag' taqsimlaydi.
2. **Xodim** telefon raqami va SMS kod (OTP) bilan tizimga kiradi — parol kerak emas. Ajratilgan mablag' hisobidan ruxsat etilgan toifalar bo'yicha xarajat qiladi.
3. **Merchant** (do'kon) kassasidagi QR kodni ko'rsatadi. Xodim uni skaner qiladi, summani PIN kod bilan tasdiqlaydi — to'lov shu zahoti amalga oshadi.

!!! info "Kirish parolsiz"
    Platformada parol ishlatilmaydi. Kompaniya va merchant akkauntlari inbiz orqali (e-imzo yoki OTP bilan), xodimlar esa telefon raqamiga yuboriladigan SMS kod bilan kiradi. To'lov va boshqa muhim amallar esa 5 xonali **PIN kod** bilan tasdiqlanadi.
