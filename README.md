# WMTA
Windows Malware Tools Analysis


WMTA adalah sebuah aplikasi yang di buat untuk memudahkan analisa Malware Windows<br>
WMTA terdiri dari beberapa kumpulan Tools Analisa Malware WIndows 
<br><br>

<h1><a id="user-content-wmta" class="anchor" href="#wmta" aria-hidden="true"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>WMTA Kategori</h1>

<b> DOWNLOAD : <a href="https://drive.google.com/file/d/0B0NUJSUNzKWoWTQxai1ZYUp3M2M/">WMTA</a></b>

WMTA sendiri berisi kategori analisa Malware Windows : <br>


- <b>Analisa Kode </b> <br>
Analisa Kode Adalah pendeteksian malware dengan mengamati sekilas ciri khas sebuah file program tanpa harus mengeksekusinya.

*BINTEXT<br>
Teks extractor perangkat lunak yang  digunakan untuk mengambil teks dari aplikasi atau file apapun. 

*CFF EXPLORER<br>
CFF Explorer adalah tool untuk deskripsi, utilitas, hex editor, dan mendukung struktur NET.

*IDA PRO<br>
IDA PRO adalah tool untuk melakukan debug dengan melihat kode program dalam bentuk assembler

- <b>Analisa Dokumen</b> <br>
Analisa Dokumen Adalah untuk mempelajari “source code” program yang bersangkutan untuk mempelajari algoritma maupun struktur data sebuah file Dokumen.

*OFFICE MALSCANNER<br>
Office MalScanner Tools analisa Malware dokumen dengan ekstensi .doc .excel , dll

*PDF MALSCANNER<br>
PDF MalScanner Tools analisa Malware dokumen dengan ekstensi .pdf

*PDF STREAMDUMPER<br>
PDF StreamDumper Tools Reverse dan Debug File Malware dengan ekstensi .pdf

- <b>Analisa Sistem</b> <br>
Analisa Sistem Adalah sebuah prosedur dan lingkungan untuk mengeksekusi atau menjalankan program yang dicurigai mengandung atau sebagai malware tersebut.

*PROCESS EXPLORER<br>
Memonitor proses apa saja yang sedang berlangsung di windows. Baik proses yang visible atau hidden.

*REGSHOT<br>
Regshot tool registri untuk membandingkan perubahan yang telah dilakukan malware di registry Windows.

*PROCESS MONITOR<br>
Process Monitor adalah tool monitoring Windows untuk monitor file system, Registry dan proses yang berjalan

- <b>Analisa File</b> <br>
Analisa File Adalah Program yang dikaji tidak akan dijalankan, hanya akan dilihat “bagian luarnya” saja.Dari sini akan dicoba ditemukan hal-hal yang patut untuk dicurigai karena berbeda dengan ciri khas program kebanyakan yang serupa dengannya

*PEID<br>
PEiD adalah Tool untuk mendeteksi packers, cryptors and compilers.

*PEVIEW<br>
PEView adalah tool untuk melihat struktur dan Component File

*QUICK UNPACK<br>
Quick Unpack adalah unpacker all in 1 dimana dapat mendeteksi PE header dan membuka proteksi packer 

- <b>Analisa Trafik</b> <br>
Analisa Trafik  Adalah melihat trafik alur service data dari malware. Dan juga melihat IP dan Port Serangan malware

*WIRESHAARK<br>
Wireshark adalah tool yang ditujukan untuk melakukan analisa paket data jaringan. 

*CAPTURE BAT<br>
Capture BAT adalah aplikasi pememantauan keadaan sistem berlajalan selama service berjalan.

*FAKE NET<br>
FakeNet alat untuk mensimulasikan jaringan sehingga service malware host remote malware dianalisa.

<h1><a id="user-content-requirements" class="anchor" href="#requirements" aria-hidden="true"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Requirements</h1>

<b>Tambahan instalasi WMTA :</b> <br>

- Install Net Framework 4.0
- Install Python 2.7
- Install WinPcap

<h1><a id="user-content-screenshots" class="anchor" href="#screenshots" aria-hidden="true"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Screenshots</h1>


<b>Tampilan Login</b>
<p><a href="https://raw.githubusercontent.com/0xc1r3ng/WMTA/master/login.PNG" target="_blank"><img src="https://raw.githubusercontent.com/0xc1r3ng/WMTA/master/login.PNG" alt="Login"></a></p>
<br>

<b>Tampilan Dashboard</b>
<p><a href="https://raw.githubusercontent.com/0xc1r3ng/WMTA/master/Dashboard.PNG" target="_blank"><img src="https://raw.githubusercontent.com/0xc1r3ng/WMTA/master/Dashboard.PNG" alt="Dashboard"></a></p>
<br><br>

Catatan :<br>
Hanya Tools Sederhana yang digunakan untuk Dasar Analisa Malware Windows
