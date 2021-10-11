  
# Hacktoday 2021 - JAV

### Forensic: Hide n Seek
Diberi file hideme.pdf, ketika di dalamnya terdapat string hex yang jika didecode menghasilkan file pdf baru. File pdf baru tersebut jika dibuka akan meminta password, jadi kami menggunakan pdf2john untuk melakukan bruteforce, hasilnya password HIDEandSEEK27. Buka filenya dapat flag.

![](images/hacktoday-hidenseek.png)

**Flag: hacktoday{embedded_files_in_pdf's_with_passwword}**