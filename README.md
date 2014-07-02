tudockblog-extjs-example-mvvm
=============================

Beispiel(e) für den TUDOCK Blogartikel zum Thema "MVVM in ExtJS5" aus der Reihe "Neue Features in ExtJS5"

**Wichtig**: Dieser Beitrag basiert auf der GPL-Version von ExtJS5, (c) Sencha, Inc, lizensiert unter der GPLv3. Weitere
Infos findet ihr auf der [ExtJS Website](http://www.sencha.com/products/extjs)

# Wie nutze ich dieses Beispiel?
## Voraussetzungen
Die Grundvoraussetzung für dieses Beispiel sind zunächst einmal [git](http://git-scm.com) für das Auschecken des Github
Repositories. Um einfach mit dem Projektstand arbeiten zu können, bietet sich natürlich auch Sencha Cmd an, das ihr
ebenfalls [bei Sencha](www.sencha.com/products/sencha-cmd) bekommt.

## Auschecken
```bash
mkdir -p ~/SenchaProjects/
cd ~/SenchaProjects/
git clone https://github.com/TUDOCK/tudockblog-extjs-example-mvvm.git
```

## Server mit Sencha Cmd starten
Wenn man clientseitiges Javascript entwickelt, sollte man dies am Besten im selben Kontext wie eine mögliche Live-Umgebung
tun. Das heißt: Das Javascript über einen Webserver ausliefern. Damit man jetzt aber nicht einen kompletten Apache, IIS
 oder Ähnliches installieren muss, bringt Sencha Cmd 5 einen kleinen aber feinen Webserver von Haus aus mit. Einfach
 ins Projektverzeichnis wechseln, und den Server mit _sencha web start_ starten.

```bash
cd ~/SenchaProjects/tudockblog-extjs-example-mvvm
sencha web start
```

Jetzt seid ihr Startklar - der Quelltext-Stand ist einfach über http://localhost:1841 aufrufbar.