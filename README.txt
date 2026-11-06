PET GALAXY SIMULATOR
====================

Cara menjalankan:
1. Extract ZIP.
2. Buka folder pet_galaxy_simulator.
3. Jalankan index.html menggunakan browser Chrome/Edge.
   Jika modul Three.js diblokir saat dibuka langsung, gunakan VS Code Live Server:
   - Buka folder di VS Code
   - Install extension Live Server
   - Klik kanan index.html > Open with Live Server

Fitur:
- Dunia 3D procedural (Three.js), pulau dapat dijelajahi dengan drag mouse/touch.
- 9 pulau, telur berbeda, unlock menggunakan Coins.
- Hatch x1, x3, x8.
- 30 Secret pets dan rarity tiers.
- Pity 250 (jaminan Secret pada tarikan setelah mencapai 250).
- Inventory, Equip, Equip Best, Fusion, Rebirth, Income Upgrade.
- Autosave melalui localStorage browser.

Catatan:
- Aset visual 3D dibuat secara procedural dari geometri Three.js dan emoji sebagai ikon pet, sehingga tidak membutuhkan file gambar eksternal.
- Three.js dan font dimuat dari CDN, jadi koneksi internet diperlukan.
- Ini adalah prototype single-player lokal; belum ada login, multiplayer, server, atau leaderboard online.
