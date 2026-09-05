# ps3_ghidra
A collection of scripts/loaders/plugins for ghidra used to aid ps3 reverse engineering

## find_stdu.java

Here is stupid script made from one of already existing ones. You need to run it on unanalyzed file to get best result, or result at all until i learn java, and that api. 

Is just looking for hex pattern of      stdu        r1, and create function there. For now it scan only undefinied parts, that why need to run before analyze. Seems to not cause any issues, you can run autoanalyze right when it finish.

## ps3.py
nasty script

put ps3.xml in main ghidra folder

does imports and exports

only works on elfs for now

# Ps3GhidraScripts – Python 3 Version

This is a fork of the original Ps3GhidraScripts by clienthax, 
updated for Python 3 (Ghidra 11.3+ / PyGhidra).

## Changes
- `print` statements with parentheses (Python 3)
- `xrange` replaced with `range`
- Removed `.encode('utf-8')` (unnecessary in Python 3)
- Added null check for `func` (prevents crashes)
- Adjusted path for `ps3.xml`

## Usage
1. Place `ps3.xml` in the same folder as `ps3.py`.
2. Start Ghidra with `pyghidraRun.bat`.
3. Load and run the script.


# Ps3GhidraScripts – Python 3 Version

Dies ist ein Fork der originalen Ps3GhidraScripts von clienthax, 
angepasst für Python 3 (Ghidra 11.3+ / PyGhidra).

## Änderungen
- `print`-Anweisungen mit Klammern (Python 3)
- `xrange` durch `range` ersetzt
- `.encode('utf-8')` entfernt (überflüssig in Python 3)
- Nullprüfung für `func` eingebaut (verhindert Abstürze)
- Pfad für `ps3.xml` angepasst

## Nutzung
1. Lege `ps3.xml` in den gleichen Ordner wie `ps3.py`.
2. Starte Ghidra mit `pyghidraRun.bat`.
3. Lade das Skript und führe es aus.
