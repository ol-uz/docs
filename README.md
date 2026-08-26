# qr.ol.uz hujjatlari

[qr.ol.uz](https://qr.ol.uz) platformasining foydalanuvchi hujjatlari. [MkDocs](https://www.mkdocs.org/) + [Material for MkDocs](https://squidfunk.github.io/mkdocs-material/) asosida qurilgan va GitHub Pages orqali chop etiladi.

**Sayt:** https://ol-uz.github.io/docs/

## Tuzilma

```
mkdocs.yml            # Sayt konfiguratsiyasi
docs/
  index.md            # Bosh sahifa
  kompaniya.md        # Kompaniya qo'llanmasi
  xodim.md            # Xodim qo'llanmasi
  merchant.md         # Merchant qo'llanmasi
  images/             # Skrinshotlar
```

## Lokal ishga tushirish

```bash
python3 -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt
mkdocs serve
```

Sayt http://127.0.0.1:8000 manzilida ochiladi va fayllar o'zgarganda avtomatik yangilanadi.

## Chop etish (GitHub Pages)

`main` branchiga push qilinganda [.github/workflows/deploy.yml](.github/workflows/deploy.yml) workflow'i saytni qurib, `gh-pages` branchiga joylaydi.

Birinchi marta yoqish uchun: repo **Settings → Pages** bo'limida *Source* sifatida `gh-pages` branchini tanlang (birinchi workflow muvaffaqiyatli o'tgandan keyin paydo bo'ladi).
