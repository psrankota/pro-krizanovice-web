# PRO KŘIŽANOVICE 2026

Statický responzivní web. Hotová stránka je přímo v kořeni repozitáře.

## GitHub Pages
V nastavení repozitáře otevřete **Settings → Pages** a nastavte:
- Source: **Deploy from a branch**
- Branch: **main**
- Folder: **/ (root)**

Soubor `.nojekyll` umožňuje přímé servírování statických souborů.

## Lokální náhled
Otevřete `index.html` nebo z kořene repozitáře spusťte:

```sh
python3 -m http.server 8765 --bind 127.0.0.1
```

Náhled: http://127.0.0.1:8765

## Úpravy a struktura
- `build.py`: obsah a šablona; po úpravě spusťte `python3 build.py`.
- `index.html`: výsledná stránka generovaná přímo do kořene.
- `style.css`: vzhled a mobilní rozložení.
- `assets/`: obrázky a PDF.

Po úpravě obsahu nahrajte i znovu vygenerovaný `index.html`. Není potřeba instalovat žádné závislosti. Web nepoužívá externí služby. PDF jsou nezměněné kopie dodaných podkladů.
