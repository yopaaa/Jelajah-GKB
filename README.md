# Jelajah-GKB

Contoh menampilkan gambar di README.

## Cara cepat (menggunakan raw GitHub URL)
Jika file gambar ada di repository pada commit/branch yang sama, Anda bisa menampilkan langsung dengan URL raw.  
Contoh (menggunakan file dengan nama asli yang ada spasi — URL di-encode):

![Preview image](https://github.com/yopaaa/Jelajah-GKB/blob/main/WhatsApp%20Image%202026-01-06%20at%2011.20.23%20AM.jpeg)
![Preview image](https://github.com/yopaaa/Jelajah-GKB/blob/main/WhatsApp%20Image%202026-01-06%20at%2011.20.24%20AM(1).jpeg)
![Preview image](https://github.com/yopaaa/Jelajah-GKB/blob/main/WhatsApp%20Image%202026-01-06%20at%2011.20.24%20AM.jpeg)

> Catatan: Gambar di atas akan tampil bila file tersebut benar-benar ada di repo pada commit `ab3f0a93...`. Jika tidak tampil, periksa nama dan lokasi file.

## Cara yang disarankan (relative path)
Letakkan gambar di folder `images/` (atau `assets/`) dan berikan nama tanpa spasi, mis. `whatsapp-2026-01-06-112023.jpg`. Struktur:
```
images/
  whatsapp-2026-01-06-112023.jpg
README.md
```

Di README.md:
```markdown
![Deskripsi gambar](images/whatsapp-2026-01-06-112023.jpg)
```

Atau jika ingin mengatur lebar menggunakan HTML:
```html
<img src="images/whatsapp-2026-01-06-112023.jpg" alt="Deskripsi gambar" width="600" />
```

## Tips
- Hindari spasi dan karakter spesial pada nama file; gunakan huruf kecil dan `-` atau `_`.
- Jika nama berisi spasi, gunakan URL-encoding (`%20`) saat memakai raw GitHub URL, atau lebih baik ubah nama file.
- Pastikan Anda men-commit file gambar ke repo agar tampil di GitHub.

Jika mau, saya bisa:
- Menghasilkan README yang langsung mengganti nama file dan menaruh contoh relatif, atau
- Membuat struktur `images/` dan contoh commit message (perlu akses push jika ingin saya yang melakukan).
