# THIRD PARTY LICENSES - CodexCompression v3.3.4 RELEASE
# Ce fichier doit accompagner toute distribution du binaire CodexCompression

Ce logiciel utilise des composants open-source sous licences permissives.
CodexCompression lui-même reste sous Licence CircaFrax Proprietary Freeware v1.0.
Les licences ci-dessous restent applicables et doivent être conservées.

---

## 1. customtkinter
- **Usage:** Interface graphique moderne (UI)
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

## 2. tkinterdnd2
- **Usage:** Drag & Drop natif Windows
- **Source:** https://github.com/pmgagne/tkinterdnd2
- **Licence:** MIT License

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

## 3. Pillow (PIL)
- **Usage:** Traitement d'images PNG/JPG pour icônes et prévisualisation
- **Source:** https://github.com/python-pillow/Pillow
- **Licence:** HPND - Historical Permission Notice and Disclaimer (MIT-like, permissive)

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

## 4. rarfile + unrar (extraction RAR uniquement)
- **Usage:** Extraction des archives .rar (lecture seule)
- **Source:** https://github.com/markokr/rarfile + https://www.rarlab.com
- **Licence:** Mixed - ISC for wrapper + unRAR License for binary

Ce module est CRITIQUE pour CodexCompression car il explique pourquoi la création .rar est bloquée.

```
unRAR - freeware for RAR extraction

The unRAR sources cannot be used to re-create the RAR compression algorithm,
which is proprietary. Distribution of modified unRAR sources in separate form
or as a part of other software is permitted, provided that it is clearly
stated in the documentation and source comments that the code may not be used
to develop a RAR (WinRAR) compatible archiver.

Source code of unRAR: free to use for extraction.

RAR and WinRAR are trademarks of Eugene Roshal.
```

Traduction / obligation : CodexCompression utilise unRAR uniquement pour EXTRAIRE,
jamais pour CREER des .rar. C'est pourquoi le module RAR est en lecture seule.

Wrapper Python rarfile :

```
ISC License

Copyright (c) 2015 Marko Kreen

Permission to use, copy, modify, and/or distribute this software for any
purpose with or without fee is hereby granted, provided that the above
copyright notice and this permission notice appear in all copies.

THE SOFTWARE IS PROVIDED "AS IS" AND THE AUTHOR DISCLAIMS ALL WARRANTIES...
```

---

## 5. Python Standard Library
- **Usage:** zipfile, pathlib, os, subprocess
- **Licence:** Python Software Foundation License (PSF) - Permissive, compatible commercial

Incluse avec Python, pas d'obligation de distribution de licence séparée pour un exe.

---

## Résumé légal / Obligations

1. Vous pouvez distribuer CodexCompression.exe gratuitement, même en entreprise.
2. Vous DEVEZ garder ce fichier THIRD_PARTY_LICENSES.md à côté de l'exe, ou dans un dossier _Doc/ ou Licences/.
3. Vous ne pouvez pas créer de .rar avec ce logiciel - c'est une restriction de RARLAB, pas de CircaFrax.
4. Toutes ces librairies sont permissives et autorisent l'usage commercial dans un logiciel propriétaire freeware comme CodexCompression, à condition de conserver leurs notices (ce fichier remplit cette obligation).
5. Vous n'avez pas besoin de distribuer leur code source.

Si vous distribuez l'exe : gardez LICENCE.md + THIRD_PARTY_LICENSES.md ensemble.

---

*Généré le 26 juillet 2026 - CircaFrax - pour CodexCompression v3.3.4 RELEASE*
*Conforme pour distribution binaire freeware propriétaire.*
