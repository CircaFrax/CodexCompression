# THIRD PARTY LICENSES - CodexCompression v3.5.4 FINAL CLEAN RELEASE
# Ce fichier doit accompagner toute distribution du binaire CodexCompression
# Date: 25 August 2026

Ce logiciel utilise des composants open-source sous licences permissives.
CodexCompression lui-même reste sous Licence CircaFrax Proprietary Freeware v1.0.
Les licences ci-dessous restent applicables et doivent être conservées.

---

## 1. customtkinter - Interface graphique moderne
- **Usage:** Interface graphique CREAM EDITION (sidebar, cards, boutons)
- **Version utilisée:** 5.x
- **Source:** https://github.com/TomSchimansky/CustomTkinter
- **Licence:** MIT License
- **Copyright:** (c) 2021-2024 Tom Schimansky

```
MIT License

Copyright (c) 2021-2024 Tom Schimansky

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
```

---

## 2. tkinterdnd2 - Drag & Drop natif Windows (FIX v3.5.1 CTkDnD)
- **Usage:** Glisser-déposer sur exe + zone universelle + modules Explorer
- **Fix v3.5.1:** Classe hybride CTkDnD(ctk.CTk, TkinterDnD.DnDWrapper) pour corriger
  '_tkinter.tkapp' object has no attribute 'drop_target_register'
- **Source:** https://github.com/pmgagne/tkinterdnd2
- **Licence:** MIT License
- **Copyright:** (c) 2018 Petru Godja, Michael Lange, et al.

```
MIT License

Copyright (c) 2018 Petru Godja, Michael Lange, et al.

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
```

---

## 3. Pillow (PIL) - Traitement d'icônes PNG
- **Usage:** Chargement de Codex_star_512.png + CodexCompresson.ico (iconphoto)
  Fallback .ico/.png dans _Code/assets/, support PNG 512px -> 32px
- **Source:** https://github.com/python-pillow/Pillow
- **Licence:** HPND - Historical Permission Notice and Disclaimer (MIT-like, permissive)
- **Copyright:** (c) 1997-2011 Secret Labs AB, Fredrik Lundh
  (c) 2010-2026 Alex Clark and contributors

```
The Python Imaging Library (PIL) is

    Copyright (c) 1997-2011 by Secret Labs AB
    Copyright (c) 1995-2011 by Fredrik Lundh

Pillow is the friendly PIL fork. It is

    Copyright (c) 2010-2026 by Alex Clark and contributors

Like PIL, Pillow is licensed under the open source HPND License:

By obtaining, using and/or copying this software and/or its associated
documentation, you agree that you have read, understood, and will comply
with the following terms and conditions:

Permission to use, copy, modify, and distribute this software and its
associated documentation for any purpose and without fee is hereby granted,
provided that the above copyright notice appears in all copies, and that
both that copyright notice and this permission notice appear in supporting
documentation, and that the name of Secret Labs AB or the author not be used
in advertising or publicity pertaining to distribution of the software
without specific, written prior permission.

SECRET LABS AB AND THE AUTHOR DISCLAIMS ALL WARRANTIES WITH REGARD TO THIS
SOFTWARE, INCLUDING ALL IMPLIED WARRANTIES OF MERCHANTABILITY AND FITNESS.
IN NO EVENT SHALL SECRET LABS AB OR THE AUTHOR BE LIABLE FOR ANY SPECIAL,
INDIRECT OR CONSEQUENTIAL DAMAGES OR ANY DAMAGES WHATSOEVER RESULTING FROM
LOSS OF USE, DATA OR PROFITS, WHETHER IN AN ACTION OF CONTRACT, NEGLIGENCE
OR OTHER TORTIOUS ACTION, ARISING OUT OF OR IN CONNECTION WITH THE USE OR
PERFORMANCE OF THIS SOFTWARE.
```

---

## 4. Python Standard Library - Formats natifs
- **Usage:** zipfile, tarfile, gzip, bz2, lzma, pathlib, os, subprocess, tempfile
  21 formats supportés: ZIP, 7Z, TAR, GZ, BZ2, XZ, JAR, ISO, RAR (lecture), CAB, CPIO, etc.
- **Licence:** Python Software Foundation License (PSF) - Permissive, compatible commercial
- **Note:** Inclus avec Python, pas d'obligation de distribution de licence séparée pour un exe
  PyInstaller embarque les modules stdlib nécessaires.

---

## 5. Icônes et Assets CircaFrax
- **Usage:** CodexCompresson.ico, Codex_star_512.png dans _Code/assets/
- **Licence:** Propriétaire CircaFrax - inclus dans la licence principale CodexCompression
- **Source:** Design original CircaFrax

---

## Changements v3.5.4 CLEAN vs v3.3.4

- Suppression du bouton "?" Histoire (histoire_formats.py) pour release propre - module conservé pour future maj
- Fix CTkDnD hybride pour drag & drop (root customtkinter n'était pas DnD)
- Fix icône PNG/ICO avec recherche dans _Code/assets/, assets/, _Assets/icons/
- Essentiels repliés par défaut: "Les plus utilisés (cliquez pour voir)" - plus propre grand public
- Suppression mention "MajorGeeks style + ISO" -> "21 formats • Simple, rapide et compatible"
- Catégories renommées grand public: FORMATS COURANTS, FORMATS SPÉCIAUX, FORMATS ANCIENS
- Badges "Lecture: OUI/NON" -> "Ouvrir: Oui / Créer: Oui/Non"
- Tous les modules Win10-safe, plus de carré 🗜️ - 21/21 chargés

---

## Résumé légal / Obligations pour distribution

1. Vous pouvez distribuer CodexCompression.exe gratuitement, même en entreprise.
2. Vous DEVEZ garder ce fichier THIRD_PARTY_LICENSES.md à côté de l'exe, ou dans un dossier _Doc/ ou Licences/ ou _Code/assets/.
3. Vous ne pouvez pas créer de .rar propriétaire avec unRAR - c'est une restriction de RARLAB, mais en v3.5.4 le module RAR est en lecture seule via stdlib (pas de binaire unrar externe).
4. Toutes ces librairies sont permissives et autorisent l'usage commercial dans un logiciel propriétaire freeware comme CodexCompression, à condition de conserver leurs notices (ce fichier remplit cette obligation).
5. Vous n'avez pas besoin de distribuer leur code source.
6. Pour PyInstaller: --add-data "modules;modules" --add-data "_Code/assets;assets" --icon=_Code/assets/CodexCompresson.ico

Si vous distribuez l'exe : gardez LICENCE.md + THIRD_PARTY_LICENSES.md ensemble.

---

*Généré le 26 août 2026 - CircaFrax - pour CodexCompression v3.5.4 FINAL CLEAN RELEASE*
*Conforme pour distribution binaire freeware propriétaire - 21 formats - Simple et Universel*
*Build: PyInstaller onefile windowed + CTkDnD + Pillow + customtkinter + tkinterdnd2*
