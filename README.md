# NexaVault

Landing page + dashboard web3 (satu file `index.html`, tanpa build step).

## Fitur
- Hero dinamis: jaringan partikel interaktif, parallax, kursor bercahaya, tombol magnetik
- Harga live (CoinGecko) dengan sparkline, fallback otomatis ke mode demo
- Koneksi wallet via ethers.js v6: saldo, jaringan, pindah chain, tanda tangan pesan
- Simulator imbal hasil, command palette (Ctrl/Cmd + K), mode gelap/terang
- Responsif desktop dan ponsel, mendukung `prefers-reduced-motion`

## Deploy ke GitHub Pages
```bash
git init && git add . && git commit -m "NexaVault"
git branch -M main
git remote add origin https://github.com/USERNAME/nexavault.git
git push -u origin main
```
Lalu di GitHub: **Settings > Pages > Source: GitHub Actions**. Situs akan terbit otomatis di `https://USERNAME.github.io/nexavault/`.

> Catatan: ini antarmuka demo, bukan nasihat keuangan. Tidak ada smart contract di dalamnya.
