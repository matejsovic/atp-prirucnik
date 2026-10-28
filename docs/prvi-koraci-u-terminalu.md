# Prvi koraci u terminalu

<!-- Ovo je početna verzija (v0) za projekt P1.
     Sve što je u [uglatim zagradama] zamijenite svojim tekstom.
     Očekivane rezultate prepišite sa SVOJEG zaslona, ne izmišljajte ih.
     Kad završite, ovaj komentar izbrišite. -->

[Jedna ili dvije rečenice: što će čitatelj naučiti u ovom tutorialu i koliko otprilike traje.]

## Prije početka

- Windows 11 i Git Bash
- Visual Studio Code je pokrenut, a u njemu je otvorena mapa [atp-prirucnik].

## 1. Otvorite terminal

U izborniku **Terminal** odaberite **New Terminal**.

**Očekivani rezultat:** matej@MATEJ UCRT64 ~/Documents/atp-prirucnik (main)

## 2. Provjerite gdje se nalazite

```bash
pwd
```

**Očekivani rezultat:** - Visual Studio Code je pokrenut, a u njemu je otvorena mapa [atp-prirucnik].

## 3. Napravite mapu i uđite u nju

```bash
mkdir proba-terminala
cd proba-terminala
pwd
```

**Očekivani rezultat:** proba-terminala

## 4. Napravite datoteku i upišite u nju tekst

```bash
echo "# Moje bilješke" > biljeske.md
cat biljeske.md
```

**Očekivani rezultat:** # Moje bilješke

## 5. Dodajte još jedan redak

```bash
echo "- Naredba pwd ispisuje gdje se nalazim." >> biljeske.md
cat biljeske.md
```

**Očekivani rezultat:** # Moje bilješke

> overwritea sve redove, dok >> samo nadopunjuje postojeći sadržaj.

## 6. Kopirajte, preimenujte i izbrišite datoteku

```bash
cp biljeske.md kopija.md
mv kopija.md stara.md
rm stara.md
ls
```

**Očekivani rezultat:** biljeske.md

Upozorite čitatelja na ono što je važno znati prije naredbe `rm` - trajna je

## Ako ne radi

| Poruka | Što znači | Što učiniti |
|---|---|---|
| `No such file or directory` | [Objasnite.] | [Objasnite.] |
| [Druga poruka koju ste vidjeli na vježbama] | [Objasnite.] | [Objasnite.] |

## Što dalje

priručnik Srca *Uvod u Linux*, poglavlja 2 i 3.
