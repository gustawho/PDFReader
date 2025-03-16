# PDFReader
PDF reader extension for Falkon using pdf.js

![Falkon with PDFReader extension](https://github.com/gustawho/PDFReader/blob/master/screenshots/Screenshot_20190118_183803.png)

### Installation
[KDE Store](https://store.kde.org/p/2271803)

[AUR:](https://aur.archlinux.org/packages/falkon-plugin-pdfreader)
```bash
yay falkon-plugin-pdfreader
```

```bash
git clone https://github.com/gustawho/PDFReader
cmake -DCMAKE_INSTALL_PREFIX=/usr -DCMAKE_BUILD_TYPE=Release -B build -S PDFReader
cmake --build build --config Release
sudo cmake --install build --config Release
```
