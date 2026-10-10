PRAKTIK PYTHON DASAR - SESUAI MATERI PDF

Persiapan:
1. Instal Python 3 dan VS Code.
2. Buka folder ini di VS Code.
3. Buka Terminal > New Terminal (PowerShell).
4. Buat environment: python -m venv .venv
5. Aktifkan: .\.venv\Scripts\Activate.ps1
   Jika diblokir PowerShell, lihat panduan di bawah.
6. Instal library: python -m pip install -r requirements.txt
7. Jalankan file dari folder proyek, contoh:
   python bab01_pengenalan/hello.py

Catatan:
- Jalankan perintah dari folder utama Python_Dasar_Praktik.
- Bab 1-10 umumnya hanya memakai fitur bawaan Python.
- pandas pada bab 11 perlu diinstal melalui requirements.txt.
- file tuple_error.py memang menghasilkan TypeError sebagai demonstrasi error pada materi.
- baca_data.py, olah_data.py, rekap.py, dan pakai_pandas.py membaca file nilai.csv dari folder bab11_pengolahan_data; jalankan file tersebut saat terminal berada di folder bab11_pengolahan_data, atau gunakan perintah:
  cd bab11_pengolahan_data
  python baca_data.py

Jika aktivasi PowerShell diblokir:
Set-ExecutionPolicy RemoteSigned -Scope Process
Lalu ulangi:
.\.venv\Scripts\Activate.ps1

Jika perintah python tidak dikenali, coba gunakan py sebagai pengganti python untuk membuat venv:
py -m venv .venv
