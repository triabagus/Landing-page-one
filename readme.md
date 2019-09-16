# Landing Page One
    Landing page with sass praprocessor.
# Installation Sass 
1. Linux
```bash
    [sudo] npm install -g sass 
    sass --version // cek sass version
```
>Catatan: jika kamu menginstal nodejs di root, maka gunakan sudo. Tapi kalau menginstal di home, tidak perlu pakai sudo.
# Compile Sass
1. File
example:
```bash 
    sass style.scss style.css
    sass --watch style.scss style.css
```
2. Folder
example:
```bash
    sass src/sass:dist/css 
    sass --watch src/sass:dist/css
```
>SASS Watch adalah fitur yang diberikan SASS untuk memantau perubahan pada file.

>Cara menggunakannya dengan memberikan flag --watch pada perintah kompilasi SASS.
# Author
&copy; [triabagus](https://github.com/triabagus/).