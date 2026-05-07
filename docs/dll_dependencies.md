For normal operation in Windows Auto Screenshot requires several third party libraries (DLLs). They should be located in the same dir where executable file `autoscreenshot.exe`. Provided links for manually download required files. You should used correct 32 or 64 bit version depending on your the architecture.

# SQLite

Used for storing filenames of created screenshots in `journal.dat` database file. It used for old screenshot cleaner tool to prevent accidental deletion of other people's files.

https://sqlite.org/download.html

Files:
- sqlite3.dll

# OpenSSL

Used for update checking and several other https requests. Version 1.0.2j or 1.0.2u should be ok.

https://github.com/IndySockets/OpenSSL-Binaries

Files:
- libeay32.dll
- ssleay32.dll

# WebP

One of supported image format.

https://github.com/bgrabitmap/webp/blob/master/bgrawebp/

Files:
- libwebp32.dll or libwebp64.dll

# AVIF

Another one supported image format.

<!--https://github.com/bgrabitmap/bgrabitmap/files/12566323/libavif_windows_dlls_ver_1_0_1-1.zip-->
https://github.com/bgrabitmap/bgrabitmap/files/8793166/libavifDlls_0.10.1-1.zip

At least these files:
- rav1e.dll
- libwinpthread-1.dll
- libgcc_s_dw2-1.dll
- libdav1d.dll
- libavif.dll
- libaom.dll
