# PVA2 - Programování a vývoj aplikací
## Cvičení 12: Výjimky

### 1 Neexistující index
Ošetřete situaci v souboru `neexistujici_index.py`, aby program nespadnul při přístupu na neexistující index.

### 2 Přetypování

Ošetřete situaci v souboru `pretypovani.py`, která může nastat při pokusu o přetypování. Vyzkoušetje zadat řetětec, který se nebude skládat pouze z čísel desítkové číselné soustavy.

### 3
V programu `game.py` zapracujte zpracováný výjimek. V zprávě uživateli zobrazte taktéž i hodnotu, jakou se uživatel pokusil zadat.

Funkčnost ověřte zadání textových vstupů a desetinných hodnot.

### 4 Zachycení více druhů výjimek
V programu `math.py` naprogramujte funkci `calcDivAbyB`, která bude mít dva vstupní atributy `a,b`. Funkce bude provádět výpočet dle vzorce:

`((a + b) // (a - b))`. 

Do funkce zapracujte zpracování výjimek a ošetřete situace:
* dělení nulou
* zadání textu do atributu
