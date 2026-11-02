# PANDUAN KERJA AI - PROYEK SAAS SIM

## Tujuan Proyek
Membangun aplikasi SaaS berbasis website yang mengintegrasikan ERP (keuangan/internal), SCM (stok/pemasok), dan CRM (pelanggan).

## Aturan Utama AI
1. Semua modul (ERP, SCM, CRM) wajib terhubung dalam 1 database terpusat.
2. DILARANG menggunakan data asli pelanggan (nama, HP, email). Wajib gunakan 100% data simulasi/dummy.
3. DILARANG menuliskan API Key atau password langsung di dalam kode. Gunakan file .env.
4. AI wajib meminta konfirmasi pengguna sebelum mengubah atau menghapus berkas yang ada.