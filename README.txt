DX Bridge, siap upload ke Netlify

1. Buka https://app.netlify.com/drop lalu drag folder "dx-bridge" ini (atau file zip-nya) ke halaman tersebut.
2. Setelah site aktif: Site configuration > Forms > aktifkan "Form detection", lalu deploy ulang (drag folder yang sama sekali lagi).
   Tanpa langkah ini, jawaban user TIDAK tersimpan.
3. Jawaban masuk di menu Forms > "dx-bridge". Bisa diekspor ke CSV, atau atur email notifikasi di Forms > Form notifications.
4. Bahasa: default Indonesia. Link langsung versi Inggris: tambahkan ?lang=en di akhir URL.

Yang perlu diisi sebelum dibagikan (di index.html, bagian "// ===== Config"):
- CTA_URL     : link booking diskusi 30 menit. Kosong = tombol tidak tampil.
- PRIVACY_URL : link Kebijakan Privasi ABeam Indonesia. Kosong = teks biasa tanpa link.

Catatan: halaman diberi <meta name="robots" content="noindex"> supaya tidak muncul di Google. Hapus baris itu kalau ingin diindeks.
