# Stokastik_02_RB

# Analisis Kinerja Sistem Antrian SPBU ITERA – Model M/M/1

Repositori ini berisi hasil analisis kinerja sistem antrian kendaraan roda dua pada jalur pengisian BBM **Pertamax** di **SPBU 24.353.162 ITERA** menggunakan pendekatan **model antrian M/M/1**.

---

Penelitian ini menganalisis performa antrian dengan memodelkan:

- Kedatangan pelanggan → **Distribusi Poisson**
- Waktu pelayanan → **Distribusi Eksponensial**
- Jumlah server → **1 (single channel – single phase)**

Metode yang digunakan adalah **M/M/1 Queueing Model**, dengan perhitungan:

- Tingkat kedatangan (λ)
- Tingkat pelayanan (μ)
- Utilitas server (ρ)
- Panjang antrian (Lq)
- Jumlah pelanggan dalam sistem (Ls)
- Waktu tunggu (Wq dan Ws)

---

## Hasil Utama

| Parameter | Nilai |
|----------|-------|
| λ (laju kedatangan) | 0.581 pelanggan/menit |
| μ (laju pelayanan) | 0.989 pelanggan/menit |
| ρ (utilitas server) | **0.587 — stabil** |
| Lq | 0.84 pelanggan |
| Ls | 1.42 pelanggan |
| Wq | 1.44 menit |
| Ws | 2.45 menit |

**Interpretasi:**  
Sistem berada dalam kondisi stabil dan efisien. Satu dispenser Pertamax dinilai cukup untuk menangani beban kedatangan dengan waktu tunggu relatif singkat.

---
