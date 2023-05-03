# Bravo Six

Bravo Six adalah modul Deno yang memungkinkan Anda mengganti tema warna elemen HTML dengan mudah.

## Instalasi

Untuk mengimpor modul Bravo Six, tambahkan baris berikut ke file Deno Anda:

```ts
import BravoSix from "https://deno.land/x/bravo_six/mod.ts";
```

Gantilah mod.ts dengan nama file yang sesuai (misalnya bravo_six.ts atau bravo_six.js) jika Anda tidak memiliki file mod.ts dalam repositori Anda.

## Penggunaan

```ts
// main.ts
import BravoSix from "https://deno.land/x/bravo_six/mod.ts";

// Inisialisasi BravoSix dengan elemen target (opsional)
const myTheme = new BravoSix(document.body);

// Terapkan tema warna ke elemen target
myTheme.applyColors("dark");
```

### Tema Warna

- `"dark"`: latar belakang hitam dan teks putih
- `"light"`: latar belakang putih dan teks hitam
- `"night-vision"`: latar belakang _teal_ (#367978, terinspirasi dari Call of Duty©) dan teks putih

Lisensi: MIT
