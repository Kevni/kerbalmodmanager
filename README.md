kerbalmodmanager
================

A command line mod manager for Kerbal Space Program

##TODO
Folgende Befehle müssen implementiert werden:

```
kmm add-source http://website.com/source.json
```
Fügt eine neue Datenquelle für Modifikationen hinzu.
```
kmm install mechjeb2[,rocketry]
```
Installiert eine Modifikation. Mehrere Mod's werden durch Kommas getrennt.
```
kmm remove mechjeb2[,rocketry]
```
Entfernt eine Modifikation. Mehrere Mod's werden durch Kommas getrennt
```
kmm install http://website.com/modlist.json
```
Installiert eine Liste von Mod's
```
kmm reset
```
Entfernt alle Mod's
```
kmm list
```
Zeigt eine Liste aller installierten Mod's an.
```
kmm find mech*2
```
Sucht in den Quellen nach dem Modnamen
