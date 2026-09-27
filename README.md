# PRO KŘIŽANOVICE 2026
Lokální statický web. Otevřete dist/index.html nebo spusťte z této složky:

python3 -m http.server 8765 --bind 127.0.0.1 --directory dist

Náhled: http://127.0.0.1:8765

Obsah: build.py; po úpravě spusťte python3 build.py. Vzhled: dist/style.css.
Fotografie a návrhové vizualizace pocházejí z dodaného programu. PDF jsou nezměněné kopie podkladů. Web nevyžaduje externí služby ani připojení k internetu. Nebyl publikován.

## Struktura
- `build.py`: obsah a generování HTML
- `dist/index.html`: hotová stránka
- `dist/style.css`: vzhled a responzivní rozložení
- `dist/assets/`: obrázky a PDF

Po úpravě obsahu spusťte `python3 build.py`. Statický web pro hosting je ve složce `dist`. Automatické publikování není nastavené.
