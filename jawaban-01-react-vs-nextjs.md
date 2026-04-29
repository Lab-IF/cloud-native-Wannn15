# 📝 Jawaban — 01. React vs Next.js

| Info        | Detail               |
| ----------- | -------------------- |
| **Nama**    | ASWAN ALAUDDIN       |
| **NIM**     | 105841112123         |
| **Halaman** | 01. React vs Next.js |
| **Tanggal** | 29 April 2026, 16.27 |

---

## 📝 Kuis Singkat

### 1. Next.js adalah...

**Jawaban:**
Next.js adalah framework yang membungkus React. Dibuat oleh Vercel. Dia menambahkan semua yang React tidak punya:

Routing otomatis — buat file = buat halaman
API backend — bisa buat endpoint langsung
Build system — next build langsung jalan
SSR & SSG — rendering di server, SEO lebih bagus
Deployment mudah — deploy ke Vercel dengan 1 klik

### 2. Mana yang TIDAK perlu di-install manual di Next.js?

**Jawaban:**
Routing karena sudah built-in di next.js

### 3. Saat install Next.js, agar menggunakan JavaScript (bukan TypeScript), kita harus pilih...

**Jawaban:**
memilih "NO" saat program bertanya appakah ingin menggunakan Typescript atau tidak

### 4. Apakah komponen React bisa dipakai di Next.js?

**Jawaban:** '
YA, Semua komponen react bisa digunakan oleh next.js karena next.js dibangun diatas react

### 5. Sebutkan minimal 3 fitur yang Next.js berikan di atas React biasa!

**Jawaban:**

1. Routing
2. backend API
3. Build
4. SSR
5. CSS Support
6. Deployment

---

## ✏️ Jawaban Latihan

### Latihan 1 — Halaman Utama

import Image from "next/image";
import styles from "./page.module.css";

export default function Home() {
return (

  <main>
      <h1>🎓 Halo Mahasiswa!</h1>
      <p>Ini proyek Next.js pertama saya.</p>
      <p>Menggunakan <strong>JavaScript</strong>, bukan TypeScript.</p>
    </main>
  );
}

### Latihan 2 — Halaman About

export default function Home() {
return <h1>Selamat Datang, ini adalah about</h1>;
}

### Latihan 3 — Tantangan: Bandingkan Routing

**React (tanpa Next.js):**  
 Routing harus diatur secara manual menggunakan library seperti `react-router-dom`.

- **Next.js:**  
  Routing berjalan otomatis berdasarkan struktur file di dalam folder `app/` atau `pages/`.

---

## 📊 Ringkasan

| Metrik         | Nilai      |
| -------------- | ---------- |
| Total dijawab  | 0 / 8      |
| Skor kuis      | 0 / 4 (0%) |
| Latihan terisi | 0 / 3      |

---

_Dibuat otomatis oleh Sistem Kuis Pertemuan 00_
