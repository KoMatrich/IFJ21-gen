# Generátor kódu pro projekt IFJ a IAL
## Implementace Generátoru

### Autoři: 
- Martin Kocich <xkocic02@stud.fit.vutbr.cz>
- Vítězslav Kříž <xkrizv03@stud.fit.vutbr.cz> (kontrola funkčnosti)

### Požadavky

- Globálně instalované [gcc](https://gcc.gnu.org/)
- [Visual Studio Code](https://code.visualstudio.com/) nebo [Visual Studio 2019](https://visualstudio.microsoft.com/cs/vs/) s C/C++ moduly (doporučeno)
- [CMake](https://cmake.org/install/) verze >=3.10
- vložený soubor "ept.csv" ve složce projektu [vygenerovaný](http://www.fit.vutbr.cz/~ikocman/llkptg/) ve formátu CSV2

### Upozornění
- výsledný generovaný kód obsahuje funkce knihovny [Veritas-2D](https://github.com/Agrael1/Veritas-2D)

### Zprovoznění (win10 + VS)
```
cd .\build\
cmake ..
```