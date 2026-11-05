# Prvi koraci s Pandocom

Instalirati Pandoc u 10ak minuta.

Provjereno s Pandocom 3.13 na Windows, bash.

## Prije početka

- Mora imati VS Code, terminal, datoteku README.md.

## 1. Instalirajte Pandoc

### Windows

Preuzeti najnoviju verziju .msi na https://pandoc.org/installing.html, slijediti upute za instalaciju te ponovno pokrenuti VS Code.

### macOS

[Koraci za macOS. Ako nemate Mac, ostavite odjeljak za kolegu iz dijela D.]

## 2. Provjerite instalaciju

```bash
pandoc --version
```

**Očekivani rezultat:** pandoc 3.13

## 3. Pretvorite Markdown u Word

U istoj mapi će se pojaviti Word dokument README.docx.

## 4. Pretvorite Markdown u web-stranicu

Nastat će datoteka README.html koju možete otvoriti u web pregledniku.

## Ako ne radi

| Poruka | Što znači | Što učiniti |
|---|---|---|
| `command not found` | Pandoc nije preuzet | provjeriti instalaciju i ponovno pokrenuti VS Code |

## Što ste napravili

Zna instalirati Pandoc, provjeriti njegovu verziju i pretvoriti Markdown datoteku u Word i HTML format.