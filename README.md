<!--
author: Volker Göhler
version: 0.1.0
edit: true
comment: This repository is a collection of wallpaper symbols for the DiAgnostiK Project
@import: https://raw.githubusercontent.com/Ifi-DiAgnostiK-Project/Tapetensymbole/refs/heads/main/makros.md


-->

# Badges

![Github Makro-build action](https://github.com/Ifi-DiAgnostiK-Project/Tapetensymbole/actions/workflows/github_workflows_update-makros.yml/badge.svg)

[![LiaScript Course](https://raw.githubusercontent.com/LiaScript/LiaScript/master/badges/course.svg)](https://liascript.github.io/course/?https://raw.githubusercontent.com/Ifi-DiAgnostiK-Project/Tapetensymbole/refs/heads/main/README.md)

[![GitHub](https://img.shields.io/badge/Ansehen%20auf-GitHub-181717?logo=github)](https://github.com/Ifi-DiAgnostiK-Project/Tapetensymbole/blob/main/README.md)

# DiAgnostiK Tapetensymbole

Repository für Tapetensymbole nach DIN-EN-235.

- Link zur LiaScript [Bildhilfe](https://liascript.github.io/course/?https://raw.githubusercontent.com/liaScript/docs/master/README.md#24)! 😃

Das  LiaScript Dokument muss mit einem Kommentar beginnen indem die Makro Datei eingefügt wird. Das kann auch in dieser Datei beobachtet werden.

```markdown
<!--
@import: https://github.com/Ifi-DiAgnostiK-Project/Tapetensymbole/blob/main/makros.md?raw=true
-->
```

## Beispiel

Alle Beispiele funktionieren nur mit LiaScript und nicht hier im Github! Bitte obigen Link zu Kurs oder Live Editor nutzen.

### einfach mit Makro:

> `@Tapetensymbole.Beispiel(10)`

@Tapetensymbole.Beispiel(10)

### schwieriger direkt als markdown Bild

- funktioniert auch außerhalb von LiaScript!

```md
![Beispielzeichen](https://github.com/Ifi-DiAgnostiK-Project/Tapetensymbole/blob/main/img/Tapetensymbole/Beispiel.png?raw=true)<!-- style="height: 10rem;" -->
```

![Beispielzeichen](https://github.com/Ifi-DiAgnostiK-Project/Tapetensymbole/blob/main/img/Tapetensymbole/Beispiel.png?raw=true)<!-- style="height: 10rem;" -->

### Skalierung

Der Parameter (die Zahl in den runden Klammern) steuert die Größe in Zeilenhöhe des Textes.

> `@Tapetensymbole.license`

@Tapetensymbole.license

> `@Tapetensymbole.Beispiel(10)`
@Tapetensymbole.Beispiel(10)

> `@Tapetensymbole.Beispiel(5)`
@Tapetensymbole.Beispiel(5)

> `@Tapetensymbole.Beispiel(1)`
@Tapetensymbole.Beispiel(1)

## Bildermakros

Alle Bilder sind in dieser Datei abgebildet:

- [makros.md](https://github.com/Ifi-DiAgnostiK-Project/Tapetensymbole/blob/main/makros.md)

Zum anzeigen bitte folgenden LiaScript Link benutzen:

[![LiaScript Course](https://raw.githubusercontent.com/LiaScript/LiaScript/master/badges/course.svg)](https://github.com/Ifi-DiAgnostiK-Project/Tapetensymbole/blob/main/makros.md?raw=true)
