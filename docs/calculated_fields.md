# Calculated Fields Documentation: Kimia Farma Analytics

Dokumen ini menjelaskan metrik kustom (Calculated Fields) yang dibuat di dalam Looker Studio untuk menganalisis performa cabang.

---

### 1. Customer Satisfaction Score
**Field Name:** `Customer Satisfaction`
**Description:** Menghitung skor kepuasan pelanggan rata-rata dengan menggabungkan rating cabang (operasional) dan rating transaksi spesifik.
**Formula:**
```sql
(Branch Rating + Transaction Rating) / 2

### 2. Target Sales
**Field Name:** `Target Sales`
**Description:** Menghitung target sales sebesar 15% dari target sales sebelumnya.
**Formula:**
```sql
SUM(Sales) * 1.15