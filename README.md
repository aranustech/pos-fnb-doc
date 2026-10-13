# pos-fnb-doc

Halaman legal publik (Privacy Policy dkk) buat Ting POS by Aranus — di-deploy otomatis ke GitHub Pages lewat GitHub Actions tiap push ke `main`.

## Cara aktifin (sekali aja)

1. Buka **Settings → Pages** di repo GitHub ini.
2. Di bagian **Build and deployment → Source**, pilih **GitHub Actions** (bukan "Deploy from a branch").
3. Push apa pun ke `main` — workflow `.github/workflows/deploy-pages.yml` otomatis jalan dan publish.
4. URL publiknya muncul di tab **Actions** (job "deploy") atau di Settings → Pages, formatnya:
   `https://aranustech.github.io/pos-fnb-doc/`

## Isi

- `index.html` — Kebijakan Privasi Ting POS by Aranus.
