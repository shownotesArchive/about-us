#über [Shownot.es](http://shownot.es/)

##Geschichte

###Am Anfang war das (gesprochene) Wort ```07.2011```

Es war einmal vor langer, langer Zeit, genauer gesagt [am Freitag 15. Juli 2011, 19 Uhr](http://www.wrint.de/2011/07/15/kl010011-ferngesprache-iii/#more-301), als sich einige Podcasthörer zusammen fanden und bereit waren, die Welt zu verändern.  
Anfangs wurde das [Piratenpad](http://www.piratenpad.de/) ([Etherpad](http://de.wikipedia.org/wiki/EtherPad) der [Piratenpartei](http://www.piratenpartei.de/)) in einem nicht näher definiertem Format geschrieben.  
Gefüllt wurde es mit Links und mit Text der erwähnenswert schien. Zu jenen Tagen sprach man über den [exklusionistischen Charakter der deutschen Wikipedia](http://de.wiktionary.org/wiki/Exklusionist) und wir wollten Inklusionisten sein. So schrieben wir große Mengen an Text, fast völlig ohne eine Formatierung zu haben.  
Nach einem Dutzend an Sendungen wuchs in manchen der Ehrgeiz kontinuierlich Shownotes für die WRINT Episoden zu schreiben. Wir wollten für alle Hörer eine Möglichkeit bieten, die relevanten Links und Verweise in den 3- bis 4-stündigen Sendung zusammen an einem Ort zu haben und die Sendung thematisch überblicken zu können.
Das ursprüngliche Ziel hat sich bis heute nicht stark verändert, wir wollen für möglichst viele Audioinhalte zusätzliche Daten sammeln, zusammenführen und somit Podcasts leichter durchsuchbar und erwähnte Webseiten, Produkte, Personen, … leichter auffindbar machen. Wir lieben Metadaten!  

###Den Piraten sei gedankt ```11.2011```

Es hat sich eine Gruppe von Personen herausgebildet die regelmäßig Shownotes schreiben und die [Piraten-IT](https://wiki.piratenpartei.de/IT) hat eine [Team-Instanz für das Shownotes Team angelegt](https://shownotes.piratenpad.de/).
Das ermöglichte es, die Shownotes auf einer Seite halbwegs übersichtlich zu haben und diese erstmalig vor Vandalismus zu schützen.
Es fanden erste Überlegungen statt, unter einem Namen "Shownotes"  Sendungsnotizen zu schreiben, neben WRINT wurde damals auch begonnen regelmäßig Shownotes für NSFW zu schreiben.

###Mehr Aufmerksamkeit ```01.2012```

Tim Pritlove wurde Anfang 2012 auf das Shownotes Projekt aufmerksam, er äussert den Wunsch, schöner formatierte Shownotes haben zu wollen. Daraufhin gab es erste Standardisierungsansätze, die schliesslich ein Jahr später zum OSF gewachsen sind.
Es wurden vermehrt Zeitangaben gesetzt, welche anfangs noch händisch von einem vom [ePirat](http://epirat.de/) geschriebenen Uhr (Stream Laufzeit) Script abgeschrieben werden mussten.

###Hola Shownot.es ```08.2012```

Im August 2012 sponserte [Simon Waldherr](http://simon.waldherr.eu/) dem Shownotes Projekt die Domain [Shownot.es](http://shownot.es/). Mit der neuen Domain drängte sich dann auch eine schöne Webseite mit einer Übersicht der Shownotes auf.  
Diese Webseite wurde hauptsächlich von [Quimoniz](https://alpha.app.net/quimoniz) und [Simon](http://simon.waldherr.eu/) geschrieben und aktuell gehalten. Auf der Webseite werden die geparsten Versionen der Shownotes angeboten, wobei [die Shownotes zusätzlich auch auf auf GitHub](https://github.com/shownotes/shownot.es) zu finden sind und vollständig unter der [CC0 Lizenz](http://creativecommons.org/publicdomain/zero/1.0/) stehen.

###Open Shownotes Format ```09.2012```

Um die Shownotes Strukturierter und das Design der [Shownot.es Seite](http://shownot.es/) zu verschönern drängte sich ein eigenes Format auf, in welchen die Shownotes geschrieben werden.  
Dieses Format haben wir ```Open Shownotes Format``` genannt und arbeiten seit September 2012 daran. Obwohl wir im Gegensatz zu anderen Formaten keine Versionsnummern haben entwickelt sich das Format ständig weiter. Eine Definition der Sprache / des Formats ist mittlerweile auf [shownotes.github.io/OSF-in-a-Nutshell](http://shownotes.github.io/OSF-in-a-Nutshell/#deutsch) zu finden.  
Die [erste Implementation eines OSF Parsers](https://github.com/shownotes/OpenShownotesFormat) wurde von [Simon](http://simon.waldherr.eu/) in PHP geschrieben.

###Podcaster Workshop 2012 ```12.2012```

Auf dem [29C3, also dem 29ten Chaos Communication Congress](http://events.ccc.de/category/29c3/) wurde das Shownot.es-Projekt auf dem [Podcaster Workshop](http://events.ccc.de/congress/2012/wiki/Podcaster_Workshop) einer breiteren Öffentlichkeit Präsentiert.   
[Tim Pritlove](http://metaebene.me/timpritlove/), einer der beiden Organisatoren des Workshops stellte dort neben seinen eigenen Projekten und Workflows dankenswerterweise auch unsere Tools und Dienste vor.  
Als Teil des Shownot.es Teams war für uns [Evita Bley](https://alpha.app.net/evita) vor Ort.

###Show Pad und Module ```03.2013```

Im März 2013 begann die Arbeit an einem eigenen Pad, da uns das Piratenpad immer mehr an neuen Ideen hinderte. Dank der von [Simon](http://simon.waldherr.eu/) geschriebenen [Etherpad Bookmarklets](https://github.com/shownotes/EtherpadBookmarklets) wurde zwar mittlerweile die Zeitangabe automatisch eingefügt und auch ein einfacher Export als HTML oder Kapitelmarken Datei war möglich, allerdings wollten wir noch höher hinaus.  
Zum Glück hat sich zu dieser Zeit [luto](http://luto.at/) dem Shownot.es Team angeschlossen und sich dazu bereit erklärt, das [EtherPad lite](https://github.com/ether/etherpad-lite) für uns anzupassen. Das EtherPad lite ist im Gegensatz zu dem vorher verwendeten EtherPad um einiges schlanker und somit auch performanter. Diese Schlankheit bringt aber auch einige Nachteile, wie zum Beispiel eine fehlendes Usermanagement mit sich, welches [luto](http://luto.at/) deshalb selbst umsetzen musste.  
Neben dem Usermanagement, welches uns erfolgreich vor Trollen schützt wurden auch die [Etherpad Bookmarklets](https://github.com/shownotes/EtherpadBookmarklets) erweitert und ins neue Pad integriert. Da das ShowPad Modular aufgebaut ist kann man die Erweiterungen in deren eigene Repos finden. Das [insertTimestamp Modul](https://github.com/shownotes/ep_insertTimestamp) fügt die Zeitangaben ein und Synchronisiert die Uhrzeiten der Clients mit der des Servers.  
Ein weiteres Modul ist [tinyOSF](https://github.com/shownotes/tinyOSF.js) von [Simon](http://simon.waldherr.eu/), welches sich um die Umwandlung von OSF zu HTML, Markdown, mp4chaps-Kapitelmarken und einige weitere Formate kümmert.
Um regelmäßige Backups der Pad Datenbank kümmert sich das [show-pad-backup Modul](https://github.com/shownotes/show-pad-backup) von [luto](http://luto.at/).

###Wordpress Plugin ```04.2013```

Bisher mussten die Shownotes im Open Shownotes Format erst in einen von [Simon](http://simon.waldherr.eu/) geschriebenen OSF Parser (in PHP und JS verfügbar) geworfen werden, um weiterverwendbares HTML oder Chapterdaten zu bekommen, was jedoch einen unnötigen Mehraufwand für Podcaster bedeutet.
Um die Shownotes auch einfach in die jeweiligen Blogs der Podcaster zu bringen hat [Simon](http://simon.waldherr.eu/) im April 2013 begonnen, ein [Shownotes Wordpress Plugin zu schreiben](https://github.com/shownotes/wp-osf-shownotes) welches die Shownotes direkt aus dem ShowPad lädt und ohne viele Klicks und fast völlig automatisierbar die Shownotes einbindet. Anfangs funktionierte das Plugin nur zusammen mit dem [Podlove Publisher](https://github.com/podlove/podlove-publisher), wurde aber auf [Tims](http://metaebene.me/timpritlove/) Wunsch später auch als eigenständiges Plugin released.

###PPW13 und RP13 ```05.2013```

Um uns noch besser mit den Podcastern abstimmen zu können und uns gegenseitig auf neue Ideen zu bringen hat uns [Tim Pritlove](http://metaebene.me/timpritlove/) auf den [Podlove Podcaster Workshop 2013 (kurz PPW13)](http://metaebene.me/blog/2013/03/15/podlove-podcaster-workshop/) und die darauf folgende [Re-publica 2013](http://re-publica.de/) eingeladen. Das Shownot.es Team wurde dort von [Evita](https://alpha.app.net/evita), [Simon](http://simon.waldherr.eu/) und [luto](http://luto.at/) vertreten und kamen mit vielen neuen Ideen und neuen Kontakten von den beiden Veranstaltungen zurück.  
Auf der Re-publica stellten wir die Infrastruktur um Shownotes für Talks und Vorträge zu schreiben, hatten dabei ein paar Probleme und lernten vieles, was wir auf dem nächsten Chaos Communication Congress berücksichtigen wollen.  
Neben den Shownotes für die Vorträge haben wir aber auch Shownotes für [die täglich stattfindende Sondersendung](http://die-sondersendung.de/) geschrieben.

###Treffen und Skypekonferenzen ```06.2013```

Auf dem [PPW13](http://metaebene.me/blog/2013/03/15/podlove-podcaster-workshop/) und der [RP13](http://re-publica.de/) haben wir gelernt, dass persönliche Gespräche von Angesicht zu Angesicht oder zumindest akustische Unterhaltungen (d.h. keine Chats oder Instant Messenger) bei weitem Zielführender sind, als beispielsweise Diskussionen im IRC.  
Aus diesem Grund haben sich im Juni [Evita](https://alpha.app.net/evita) und [Simon](http://simon.waldherr.eu/) mit einigen Podcastern in Berlin getroffen und an neuen Ideen gefeilt.  
Ausserdem hatten wir am 02. Juli eine Skype Konferenz mit allen Mitgliedern des Kernteams, künftig wollen wir dies mindestens einmal im Monat machen.

---

und wenn sie nicht gestorben sind, dann Shownoten sie noch heute

##Mitglieder

```einfach eintragen, ich werde das ganze dann nach "dabei seit" sortieren oder wir lassen es einfach so, wie ihr wollt```  
```mir waere es lieber, wenn jeder seinen Realnamen eintragen wuerde, aber macht wie ihr wollt```   

Name             | aktiv seit | Zuständig für | Webseite                                       | App.net                                               | Twitter
-----------------|------------|---------------|------------------------------------------------|-------------------------------------------------------|------------------------
Kai              | 07.2011    | Twitter & ADN | [kaikubasta.de](http://kaikubasta.de/)         |                                                       | [@kaikubasta](http://twitter.com/kaikubasta)
Quimoniz         | 07.2011    | Webseite      |                                                | [@quimoniz](https://alpha.app.net/quimoniz)           | [@quimoniz](https://twitter.com/quimoniz)
kaeffchen heinz  | 07.2012    |               |                                                |                                                       | [@kaeffchen_heinz](https://twitter.com/kaeffchen_heinz)
Simon Waldherr   | 07.2012    | Parser        | [simon.waldherr.eu](http://simon.waldherr.eu/) | [@simonwaldherr](https://alpha.app.net/simonwaldherr) | [@simonwaldherr](https://twitter.com/simonwaldherr)
Evita Bley       | 08.2012    | Planung       | [podcascription.de](http://podcascription.de/) | [@evita](https://alpha.app.net/evita)                 | [@evitabley](https://twitter.com/evitabley)
luto             |            | Pad           | [luto.at](http://luto.at/)                     | [@luto](https://alpha.app.net/luto)                   | [@luutoo](https://twitter.com/luutoo)
Dr4k3            |            | Notification  | [fastreboot.de](http://fastreboot.de/)         | [@dr4k3](https://alpha.app.net/dr4k3)                 | [@dr4k3_LE](https://twitter.com/dr4k3_LE)

##Ziele

* Audioinhalte durchsuchbar machen
* mehr Metadaten für alle und alles
* mehr Semantik in Texten
* Spaß haben
* Podcaster und Hörerbindung steigern
* mehr Kommunikation zwischen Sender und Hörer
* Tools schreiben um diese Ziele zu erreichen


##Software \*

\* ***und andere Repositories***

Beschreibung           | Entwicklungsbeginn | Hauptsprache | Maintainer       | Repo
-----------------------|--------------------|--------------|------------------|------
shownot.es Webseite    | 08.2012            | HTML         | Quimoniz / Simon | [shownot.es](https://github.com/shownotes/shownot.es)
PHP OSF Parser         | 09.2012            | PHP          | Simon            | [OpenShownotesFormat](https://github.com/shownotes/OpenShownotesFormat)
Etherpad Bookmarklets  | 12.2012            | JavaScript   | Simon            | [EtherpadBookmarklets](https://github.com/shownotes/EtherpadBookmarklets)
*insert Timestamp* ^1  | 01.2013            | JavaScript   | Simon            | [ep_insertTimestamp](https://github.com/shownotes/ep_insertTimestamp)
*shownotes Changes* ^1 | 01.2013            | JavaScript   | luto             | [ep_shownotesChanges](https://github.com/shownotes/ep_shownotesChanges)
JS OSF Parser ^2       | 03.2013            | JavaScript   | Simon            | [tinyOSF.js](https://github.com/shownotes/tinyOSF.js)
ShowPad                | 03.2013            | node.js      | luto             | [show-pad](https://github.com/shownotes/show-pad)
Shownotes WP Plugin    | 04.2013            | PHP          | Simon            | [wp-osf-shownotes](https://github.com/SimonWaldherr/wp-osf-shownotes)
*ShowPad  Backup* ^1   | 04.2013            | JavaScript   | luto             | [show-pad-backup](https://github.com/shownotes/show-pad-backup)
OSF Definition         | 05.2013            | Markdown     | Simon            | [OSF-in-a-Nutshell](https://github.com/shownotes/OSF-in-a-Nutshell)
*chapter Bold* ^1      | 06.2013            | JavaScript   | luto             | [ep_chapterBold](https://github.com/shownotes/ep_chapterBold)
Zeitangabe Parser      | 06.2013            | JavaScript   | Simon            | [parseTime.js](https://github.com/SimonWaldherr/parseTime.js)

^1) ShowPad Modul  
^2) Sowohl als ShowPad Modul als auch Standalone  

[besucht github.com/shownotes](https://github.com/shownotes) um die vollständige Liste zu sehen
