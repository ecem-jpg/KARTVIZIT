# Ecem Yay — Dijital Kartvizit

## İçerik
- `index.html` — kartvizit sayfası
- `ecem-yay.vcf` — "Rehbere Ekle" butonunun indirdiği vCard dosyası
- `assets/ecem.jpg` — profil görseli

## Bilgi güncelleme
Telefon, e‑posta, website ve LinkedIn bağlantılarını değiştirmek için **iki yeri** güncellemeniz gerekir:
1. `index.html` içindeki ilgili `href` değerleri (tel:, mailto:, wa.me, https://…)
2. `ecem-yay.vcf` içindeki `TEL`, `EMAIL`, `URL` satırları

İsim/unvan gibi görünen metinleri değiştirmek için sadece `index.html` yeterlidir.

## Yayınlama (Vercel)
1. Bu klasörü bir GitHub reposuna yükleyin (veya doğrudan Vercel CLI ile: `vercel` komutunu klasör içinde çalıştırın).
2. Vercel'de "New Project" → repoyu seçin → Framework: **Other** → Deploy.
3. Build ayarı gerekmez, statik dosyalar olduğu gibi servis edilir.

## Yayınlama (GitHub Pages)
1. Bu klasörü bir repoya `main` dalına yükleyin.
2. Repo → Settings → Pages → Source: `main` / `root` seçin.
3. Birkaç dakika içinde `https://kullaniciadi.github.io/repo-adi/` adresinden yayında olur.

## QR kod
Site yayına alındıktan sonra elinizdeki canlı bağlantıyı (ör. `https://ecemyay.vercel.app`) herhangi bir QR kod üreticisine (örn. qr-code-generator.com) yapıştırarak QR kodunuzu oluşturabilir, telefon kilit ekranınıza veya akıllı saatinize ekleyebilirsiniz.
