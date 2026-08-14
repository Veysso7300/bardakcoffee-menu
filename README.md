# Bardak Coffee — QR Menü

Bardak Coffee için mobil uyumlu QR menü sitesi. İçerik Decap CMS admin paneli (/admin) üzerinden yönetilir.

## Yapı
- `index.html` — Ana sayfa (menü, Instagram, konum, admin linkleri)
- `menu.html` — Kategorilere göre filtrelenebilir menü
- `admin/` — Decap CMS admin paneli (Netlify Identity + Git Gateway gerekir)
- `data/menu/*.json` — Her kategori için ürün verisi
- `uploads/` — Ürün fotoğrafları (admin panelinden yüklenir)

## Netlify kurulumu
1. Bu repoyu Netlify'a bağlayın (Build command boş, Publish directory: `.`)
2. Site Settings → Identity → Enable Identity
3. Identity → Registration: **Invite only** yapın
4. Identity → Services → Git Gateway → Enable Git Gateway
5. Identity sekmesinden kendinize (veya işletme sahibine) davet gönderin
6. `/admin/` adresinden giriş yapıp menüyü düzenleyin
