<a href="https://aceh.bps.go.id/">
    <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/2/28/Lambang_Badan_Pusat_Statistik_%28BPS%29_Indonesia.svg/773px-Lambang_Badan_Pusat_Statistik_%28BPS%29_Indonesia.svg.png" alt="logo" title="logo" align="right" height="140" />
</a>

# Pengumpulan dan Klasifikasi Data Berita di BPS Provinsi Aceh menggunakan Web Scraping dan Model Machine Learning

:star: Project Magang di BPS Provinsi Aceh

Ini adalah project atau pekerjaan yang saya lakukan selama magang di Badan Pusat Statistik (BPS) Provinsi Aceh.

![aimeos-frontend](https://as1.ftcdn.net/v2/jpg/01/45/68/18/1000_F_145681874_RbPDrZBa5Z5z7PVifHCrCPnBufdgnPA5.jpg)

# Table Of Content

- [Setup](#setup)
    - [VsCode](#vscode)
    - [Anaconda atau Miniconda](#anaconda-atau-miniconda)
- [TYPO3 setup](#typo3-setup)
    - [Database setup](#database-setup)
    - [Security](#security)
- [Page setup](#page-setup)
    - [Download the Aimeos Page Tree t3d file](#download-the-aimeos-page-tree-t3d-file)
    - [Go to the Import View](#go-to-the-import-view)
    - [Upload the page tree file](#upload-the-page-tree-file)
    - [Go to the import view](#go-to-the-import-view)
    - [Import the page tree](#import-the-page-tree)
    - [SEO-friendly URLs](#seo-friendly-urls)
- [License](#license)
- [Links](#links)

# Setup
***Note***: `Python`, `VsCode` dan `Anaconda` atau `Miniconda` sudah terinstall

Clone Repositori ini ke Lokal :
```bash
git clone https://github.com/zlkhyr/ScrapingSerambi.git
```
Masuk ke Direktori Project :
```bash
cd ScrapingSerambi
```
## VsCode

Setelah masuk ke direktori yang telah di clone sebelumnya, Buat `Python Environment` :

```bash
python -m venv nama_venv
```

Aktifkan Environment yang baru saja dibuat:

```bash
#Windows
nama_venv\scripts\activat

#macOS dan Linux
source lingkungan_ml/bin/activate
```

Install `requirements.txt` untuk menginstal library yang diperlukan untuk project:

```bash
pip install -r requirements.txt
```

Buka VsCode, gunakan perintah berikut:

```bash
code .
```
Setelah membuka VsCode pastikan memilih Environment atau kernel yang telah diinstall sebelumnya, Pilihan ada di pojok kanan atas VsCode. Jalankan sel-sel di notebook untuk menjalankan proyek machine learning.

## Anaconda atau Miniconda

Setelah masuk ke direktori yang telah di clone sebelumnya, Buat `Python Environment` :

```bash
conda create --name nama_venv
```

Aktifkan Environment yang baru saja dibuat:

```bash
conda activate nama_venv
```

Install `requirements.txt` untuk menginstal library yang diperlukan untuk project:

```bash
#Dengan Conda
conda install --yes --file requirements.txt

#Dengan Pip
pip install -r requirements.txt
```

Jalankan Jupyter Notebook:
```
jupyter notebook
```
Buka file proyek_machine_learning.ipynb di antarmuka Jupyter Notebook, Jalankan sel-sel di notebook untuk menjalankan proyek machine learning.

# Links

* [Laporan](https://docs.google.com/document/d/14NRzYf_ItsfcX_gsvu0QpReglbGvtiqsjSfx_2-CuWk/edit?usp=sharing)

