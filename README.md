# Yıldız&Şahin — Hukuk Bürosu (statik site)

GitHub Pages'te doğrudan yayınlanabilir statik site.

## Klasör yapısı
```
site/
├── index.html
└── img/
    ├── yasin_sahin_hukuk_amblemi1.jpeg   (logo)
    ├── 1.jpg  2.jpg  3.jpg                (slider)
    ├── anaekran1.jpg  anaekran2.jpg       (hakkımızda)
    ├── yasin.jpg  berkant.jpg  ozge.jpg  ceren.jpg   (ekip)
```

## GitHub Pages'te yayınlama
1. Yeni bir GitHub deposu oluşturun.
2. `index.html` ve `img/` klasörünü deponun köküne yükleyin.
3. Depo → **Settings → Pages** → Source: **main** / **/(root)** seçin, kaydedin.
4. Birkaç dakika sonra `https://KULLANICIADI.github.io/DEPOADI/` adresinde yayında.

## Gemini (Avukata Sor)
- `index.html` en üstteki `GEMINI_API_KEY` değerine anahtarınızı yazın.
- Anahtar: https://aistudio.google.com/apikey
- ÖNEMLİ: Site herkese açık olduğu için anahtar görünür. Google AI Studio'da
  anahtara **HTTP referrer (site) kısıtlaması** ekleyin; sadece kendi
  github.io adresinizden çalışsın.

## Özgeçmiş
Ekip kartlarına tıklanınca açılan pencere, `index.html` içindeki gizli
`<div id="cv-yasin">` vb. bloklardan içerik çeker. İçerikleri (eğitim,
deneyim vb.) o bloklarda düzenleyin.
