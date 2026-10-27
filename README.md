# İthalat Köprüsü

Çin'den ofis sandalyesi ithalatı için maliyet ve kanal marjı konsolu. Tek dosya (`index.html`), build gerektirmez.

## GitHub → Netlify

1. GitHub'da yeni repo aç (ör. `ithalat-koprusu`), bu klasördeki dosyaları yükle:
   ```bash
   git init
   git add .
   git commit -m "İlk sürüm"
   git branch -M main
   git remote add origin https://github.com/KULLANICI/ithalat-koprusu.git
   git push -u origin main
   ```
2. Netlify → **Add new site → Import an existing project → GitHub** → repoyu seç.
3. Build command: boş bırak. Publish directory: `.` → **Deploy**.

Bundan sonra `main` dalına her push otomatik yayınlanır.

## Notlar

- Veriler kullanıcının tarayıcısında (localStorage) saklanır.
- GV, İGV, KDV ve gözetim eşikleri varsayımdır; güncel TGTC ile teyit edin.
