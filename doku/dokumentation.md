# Dokumentation Linux Essentials August 2025

## Unterschied Terminal / Shell

Heutzutage spricht man von einem Terminal als ein Programm, in dem eine Shell läuft. Mithilfe einer Shell können wir Kommandos absetzen. Eine Shell folgt einer gewissen Syntax bzw. Skripsprache. 

Es gibt verschiedene Shells: Shells die als Vermittler zwischen Benutzer und Betriebssytem fungieren, andere Shells können genutzt werden, um einzelne Befehle einer Programmiersprache abzusetzen, z.B. die Python Shell. In einer MySQL Shell können Datenbanken erstellt und verwaltet werden etc.

Unter Linux nutzen wir in der Regel die BASH als Shell. Auch hier gibt es einige SH kompatible Varianten wie die ZSH, KSH, Fish-Shell etc.

## Kommandos



### Grundlegende Kommandos

- `mkdir`
- `cd`
- `ls`
- `touch`
- `cp`
- `mv`
- `rm`
- `alias`
- `rmdir`

- ``

### Shell-Builtins
In die Shell (in unserem Fall BASH) eingebaute Kommandos. Sie sind essenziell bzw. wichtig, damit die Shell an sich funktioniert, z.B. das Kommando `cd`. 

Builtins haben keine eigene Manpage, ihre Funktionsweise ist in der Manpage der BASH erklärt. Eine Kurzhilfe zu den Builtins erhält man mit dem Kommando `help`.

### Extern realisierte Kommandos
Die meisten Kommandos sind _extern realisiert_, d.h. sie sind nicht in die BASH eingebaut. So gut wie alle _extern realisierten_ Kommandos haben eine Manpage (`man <kommando>`) in welcher die Art wie das Kommando zu benutzen ist und sämtliche Optionen mit Erklärungen angegeben sind.

