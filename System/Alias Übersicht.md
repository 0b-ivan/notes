
**ALIAS_STORE_0bIvan**

Diese Aliasse dienen zum schnellen Zugriff auf Sublime Text, Spotify Player und andere häufig verwendete Befehle.

```
alias tex="open -a 'Sublime Text.app'"
alias editzsh="tex ~/.zshrc"
alias spoti="spotify_player"
alias like="spoti like"
alias ccat= 'clear && cat'
alias tailme= 'tail -f logfile.txt | grep --color=always -E "ERROR|WARN|INFO|DEBUG"'
alias lock="x=1; while  [ $x -le 5 ]; do sleep 0.9; echo ' $x to Lock'; sleep 0.9 ; $c $(( x++ )); done ; pmset displaysleepnow"
```

**notMine**

Dieser Abschnitt enthält verschiedene nützliche Aliasse für die Farbdarstellung der Ausgabe, das Navigieren in Verzeichnissen und mehr.

```
alias ls='ls --color=auto'
alias ll='ls -la'
...
alias diff='colordiff'
...
```

**SAFETY NETS**
Diese Aliasse fügen Sicherheitsnetze hinzu, um ein versehentliches Löschen oder Überschreiben von Dateien zu verhindern.

```
alias rm='rm -I --preserve-root'
...
# alias chmod='chmod --preserve-root'
# alias chgrp='chgrp --preserve-root'
```

**SERVER**
Das sind nützliche, serverbezogene Aliasse:

``` 
## Optionen für free durchreichen ##
...
## Prozess mit der höchsten CPU-Auslastung anzeigen ##
...
## Informationen zur Server-CPU anzeigen ##
...
## Dieser hat mir schon so oft den Hintern gerettet ##
...

# Erstellt durch `pipx` am 2024-04-10 17:32:23
export PATH="$PATH:/Users/ibabayev/.local/bin"
alias python=/usr/bin/python3
export PATH=$PATH:/