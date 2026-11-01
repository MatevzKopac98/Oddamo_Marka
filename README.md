# MARRIAGE.exe – SYSTEM UPGRADE

```
> Booting LIFE OS...
> Current mode: RELATIONSHIP_MODE
> Pending upgrade: HUSBAND_MODE v1.0
> ERROR: upgrade failed. Bugs detected. Merge conflict detected.
```

Dragi Marek,

tvoj življenjski operacijski sistem potrebuje nadgradnjo iz **RELATIONSHIP_MODE** v **HUSBAND_MODE**.
Na žalost je sistem poln hroščev, nova različica pa se tepe s staro.
Tvoja ekipa je poskušala pomagati. To ni nujno dobro.

Popravi sistem in odkleni **prvo lokacijo svoje fantovščine**.

## Pravila

- **Brez AI.** Ne ChatGPT, ne Claude, ne Copilot. Ekipa te gleda.
- **Namig** = 1 požirek.
- **Napačna koda** = 1 požirek.
- Ne spreminjaj podatkov v kodi in ne goljufaj s preverjanji. Popravljaj napake.

## Začetek

1. Na tej strani klikni zeleni gumb **Code → Codespaces → Create codespace on main**.
2. Počakaj, da se odpre urejevalnik. Spodaj je **terminal**.

Če imaš raje svoj računalnik: potrebuješ `git` in `g++`. Kloniraj repozitorij in nadaljuj enako.

## Modul 1 – Fantovščina (debug)

```bash
cd module1
g++ -std=c++17 bachelor_party.cpp -o bachelor_party
./bachelor_party
```

Program ima 8 hroščev. Popravljaj, dokler ne izpiše `UNLOCK CODE #1`. **Zapiši si jo.**

## Modul 2 – Nadgradnja (git)

Na veji `main` teče tvoj trenutni sistem, RELATIONSHIP_MODE.
Nadgradnja čaka na veji `husband-mode`. Združi jo:

```bash
cd ../module2
git merge origin/husband-mode
```

Nato:

1. Razreši konflikt v skladu z `module2/RELEASE_NOTES.md`.
2. Zaključi merge (`git add` + `git commit`).
3. Prevedi in zaženi `upgrade.cpp`. Sistem ti bo povedal, kaj je še narobe.

Ko je vse zeleno, dobiš `UNLOCK CODE #2`.

## Finale

```bash
cd ../final
g++ -std=c++17 unlock.cpp -o unlock
./unlock
```

Vnesi obe kodi. Vso srečo. Potreboval jo boš.
