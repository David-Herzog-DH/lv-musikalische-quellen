## Ziele der Vorlesung und Übung

 -   Einführung in die Arbeit mit Git und GitHub für alle Studierenden
 -   Einführung in die Arbeit mit MEI (Music Encoding Initiative) XML-Dateien für alle Studierenden
 -   Gemeinsame Installation von Musescore (nightly build) mit der MEI-Erweiterung für alle Studierenden

## Was ist git?

Git ist ein Versionsverwaltungssystem, das von Linus Torvalds für die Entwicklung des Linux-Kernels entwickelt wurde. Es ist ein verteiltes Versionsverwaltungssystem, das heißt, dass jede*r Autor*in oder Entwickler*in eine eigene Kopie des gesamten Repositorys besitzt. Git ist ein Open-Source-Programm und kann unter der GNU General Public License v2.0 verwendet werden.

## Was ist GitHub?

GitHub ist eine Online-Plattform, die Git zur Versionskontrolle von Code verwendet. Es ermöglicht Autor*innen und Entwicklern*innen, Code hochzuladen, zu teilen und zusammenzuarbeiten. Man kann Projekte klonen, Änderungen vorschlagen und digitale Werke in Teams entwickeln. Es ist weit verbreitet in der Wissenschaft und der Softwareentwicklung und oft ein wichtiges Tool in der Ausbildung von Informatik-Studenten und Digital Humanities.
Dieses Projekt wird auf GitHub gehostet.
Link: [https://github.com/David-Herzog-DH/lv-musikalische-quellen](https://github.com/David-Herzog-DH/lv-musikalische-quellen)

## Was ist MEI?
Die Music Encoding Initiative (MEI) ist eine gemeinschaftlich getriebene, Open-Source-Anstrengung, um ein System zur Kodierung von musikalischen Dokumenten in einer maschinenlesbaren Struktur zu definieren. MEI bringt Spezialistinnen aus verschiedenen musikwissenschaftlichen Gemeinschaften zusammen, darunter Technologinnen, Bibliothekarinnen, Historikerinnen und Theoretiker*innen, um gemeinsam Best Practices für die Darstellung einer breiten Palette von musikalischen Dokumenten und Strukturen zu definieren. Die Ergebnisse dieser Diskussionen werden im MEI-Schema formalisiert, einer Kerngruppe von Regeln zur Erfassung der physischen und intellektuellen Eigenschaften von Musiknotationsdokumenten, die als eXtensible Markup Language (XML) Schema ausgedrückt werden. Dies wird ergänzt durch die MEI-Richtlinien, die detaillierte Erklärungen der Komponenten des MEI-Modells und Vorschläge für Best Practices bieten. Das Schema wird vom MEI-Technikteam entwickelt und gepflegt. Übersetzt von [www.music-encoding.org](https://music-encoding.org/about/)

## Was ist MuseScore?

[MuseScore](https://musescore.org/de) ist ein Notensatzprogramm. 
Laut eigenen Angaben, das beliebteste der Welt.
MuseScore ist Open Source und kostenlos.
MuseScore ist für Windows, Mac und Linux verfügbar.
MuseScore unterstützt in der Zukunft die Arbeit mit MEI-Dateien.
Wir werden versuchen gemeinsam die Nightly Build Version von MuseScore installieren und verwenden, um die MEI-Dateien zu öffnen.
Link: [https://musescore.org/de](https://musescore.org/de)
MuseScore SourceCode ist auch auf GitHub zu finden.

## MoVi Stiftung Mozarteum

Link: [https://dme.mozarteum.at/movi/de](https://dme.mozarteum.at/movi/de)

Die Digitale Interaktive Mozart Musikausgabe ist eine vollständig digitale Ausgabe; die Musik wird als digitales Bild direkt aus dem zugrunde liegenden Code erzeugt. Die digitale Ausgabe der musikalischen Werke von Wolfgang Amadé Mozart, die in DME::Musik bereitgestellt wird, basiert auf der vollständigen Kodierung der Musik nach den Prinzipien der Music Encoding Initiative (MEI), einem Unterbereich von XML.

Jedes musikalische Merkmal und jedes Notationszeichen ist individuell im Code dokumentiert und umschrieben; jedes Element erhält eine einzigartige ID, die speziell für dieses Element ist, sodass es individuell adressierbar ist. Der Code ist auch maschinenlesbar und kann automatisch verarbeitet werden.

Es ist ein leistungsstarkes Werkzeug, in dem eine Fülle von Informationen gespeichert werden kann. Diese Informationen umfassen Variantenlesungen und redaktionelle Markierungen, Anmerkungen und Kommentare, Metadaten und die Verknüpfung zu anderen Datenquellen. Übersetzt aus Quelle: [https://dme.mozarteum.at/movi/](https://dme.mozarteum.at/movi/en)


## Ablauf der Vorlesung (30.10.2023) und Übung (07.11.2023)

Das Repository wird auf GitHub gehostet unter folgenden link:
### 1. Link auf git repository
[https://github.com/David-Herzog-DH/lv-musikalische-quellen](https://github.com/David-Herzog-DH/lv-musikalische-quellen)

### 2. Ansicht des Repositories auf GitHub

Alle Dateien und auch Ihre commits (Änderungen) sind auf GitHub sichtbar.
Dies ist ein öffentliches Repository, das heißt, dass alle Änderungen für alle sichtbar sind. [https://github.com/David-Herzog-DH/lv-musikalische-quellen](https://github.com/David-Herzog-DH/lv-musikalische-quellen)


### 3. Installation von Git
Jedes heruntergeladene git Repository enthält die gesamte Versionsgeschichte des Projekts. Diese ist in dem versteckten Ordner .git gespeichert.
Damit Sie mit git arbeiten können, müssen Sie git auf Ihrem Computer installieren.
Git ist für Linux, Windows und MacOS Betriebssysteme verfügbar, um nur einige
zu nennen.

Hier ein Link zu einer einfachen Erklärung und zur Hilfe bei der Installation von Git auf GitHub:

[https://rogerdudler.github.io/git-guide/index.de.html](https://rogerdudler.github.io/git-guide/index.de.html)

#### 3.1. Installationsdateien für Git
Link für Linux: [https://git-scm.com/download/linux](https://git-scm.com/download/linux)
Link für Windows: [https://gitforwindows.org/]([https://gitforwindows.org/)
Link für Mac: [https://git-scm.com/download/mac](https://git-scm.com/download/mac)

#### 3.2. Erschaffen eines lokalen Repositorys
Nachdem Sie Git installiert haben, können Sie ein lokales Repository erstellen.
Wechseln Sie in das Verzeichnis, in dem Sie das Repository erstellen möchten.
Im Terminal (Linux, Mac) oder in der Git Bash (Windows) folgenden Befehl eingeben: 
``git init``  
Dies erstellt ein lokales Repository in dem Verzeichnis, in dem Sie sich befinden.
Sie finden nun eine Ordner .git (versteckter Ordner) in dem Verzeichnis.
Dieser Ordner enthält die gesamte Versionsgeschichte des Projekts.

#### 3.3. Hinzufügen von Dateien zum Repository
Anmelden bei GitHub.
Bitte schicken Sie mir Ihren GitHub Benutzernamen, damit ich Sie als Contributor hinzufügen kann.

``david.herzog@mozarteum.at``

Sie können nun Dateien zu dem Repository hinzufügen und bearbeiten.

#### 3.4. Klonen eines Repositorys
Sie können auch ein Repository von GitHub klonen.
In diesem Fall haben wir für Sie ein Repository erstellt, das Sie klonen können.
Wechseln Sie in das Verzeichnis, in dem Sie das Repository erstellen möchten.
Im Terminal (Linux, Mac) oder in der Git Bash (Windows) folgenden Befehl eingeben: 

``git clone https://github.com/David-Herzog-DH/lv-musikalische-quellen``


Dies erstellt ein lokales Repository in dem Verzeichnis, in dem Sie sich befinden.

#### 3.5 Installation von Visual Studio Code

Visual Studio Code ist ein Code-Editor, der von Microsoft für Windows, Linux und macOS entwickelt wurde. Es enthält Unterstützung für Debugging, eingebetteten Git-Control, Syntaxhervorhebung, intelligente Code-Vervollständigung, Snippets und Code-Refactoring. Es ist kostenlos und Open Source.
Link: [https://code.visualstudio.com/download](https://code.visualstudio.com/download)


#### 3.6 Installation von Git GUI
Als Alternative Visual Studio Code kann auch Git GUI verwenden.
Git GUI ist eine grafische Benutzeroberfläche für Git.
Sie können Git GUI verwenden, um Änderungen zu verfolgen, zu verwalten und zu teilen.
Git GUI ist für Linux, Windows und MacOS Betriebssysteme verfügbar, um nur einige
zu nennen.

Link Windows: [https://git-scm.com/download/gui/windows](https://git-scm.com/download/gui/windows)
Link Mac: [https://git-scm.com/download/gui/mac](https://git-scm.com/download/gui/mac)
Link Linux: [https://git-scm.com/download/gui/linux](https://git-scm.com/download/gui/linux)

Weitere Betriebssystemversionen: [https://git-scm.com/download/gui](https://git-scm.com/download/gui)



### 4-Übung mit Git und GitHub

Sie können im GitHub Repository online im Browser Dateien hinzufügen, bearbeiten und löschen.
Sie können auch Dateien in Ihrem lokalen Repository hinzufügen, bearbeiten und löschen.
Sie können Dateien von Ihrem lokalen Repository zu dem GitHub Repository hochladen. 
Dies geschieht wie folgt:
1. Änderungen in Ihrem lokalen Repository vornehmen.
2. Änderungen in Ihrem lokalen Repository committen. (Änderungen werden in der lokalen Versionsgeschichte gespeichert)
3. Änderungen von Ihrem lokalen Repository zum GitHub Repository pushen. (Änderungen werden in der GitHub Versionsgeschichte gespeichert und ist für alle sichtbar!) Hier kann es zu Konflikten kommen, da ihr lokales Repository möglicherweise nicht mehr aktuell ist (mit dem des Servers übereinstimmt). In diesem Fall müssen Sie die Änderungen vom Server zu Ihrem lokalen Repository pullen und dann Ihre Änderungen pushen.
Wenn Änderungen anderer mit Ihren Änderungen kollidieren, so wird Ihnen dies angezeigt und Sie müssen die Änderungen manuell zusammenführen.

#### 4.1. .gitignore
Die Datei .gitignore enthält eine Liste von Dateien, die von Git ignoriert werden sollen. Dies ist wichtig, weil viele Tools und Editoren lokale
Dateien generieren, die nicht versioniert und in das Server Repository hochgeladen werden sollen.

#### 4.2 Einfache Befehle
``git status`` zeigt den Status des lokalen Repositorys an.
``git add`` fügt Dateien zum lokalen Repository hinzu.
``git commit`` committet Änderungen im lokalen Repository.
``git push`` pusht Änderungen vom lokalen Repository zum GitHub Repository.
``git pull`` pullt Änderungen vom GitHub Repository zum lokalen Repository.

#### 4.3. Erstellen einer neuen Datei
Erstellen Sie eine neue Datei in Ihrem lokalen Repository.

#### 4.4. Ändern einer Datei
Ändern Sie eine Datei in Ihrem lokalen Repository.
Wir werden im Laufe der Übung eine Datei gemeinsam bearbeiten.

#### 4.5. Commiten einer Datei
Wir werden im Laufe der Übung eine Datei gemeinsam committen.

#### 4.6. Pullen von Änderungen vom GitHub Repository zu Ihrem lokalen Repository
Wir werden im Laufe der Übung Änderungen vom GitHub Repository zu Ihrem lokalen Repository pullen.

#### 4.7. Pushen von Änderungen von Ihrem lokalen Repository zum GitHub Repository
Wir werden im Laufe der Übung Änderungen von Ihrem lokalen Repository zum GitHub Repository pushen.

#### 4.8. Konflikte und Mergen
Wir werden Mergen von Änderungen gemeinsam üben.

#### 4.9. Erzeugen eines branches für die Gruppenarbeit
Wir werden gemeinsam einen branch für die Gruppenarbeit erzeugen.

### 5. Installation von MuseScore (Vorabversion mit MEI Unterstützung)

Diese Vorabversion enthält die Unterstützung für MEI-Dateien.
Link: [https://ftp.osuosl.org/pub/musescore-nightlies/windows/4x/nightly/MuseScoreNightly-latest-master-x86_64-portable.exe](https://ftp.osuosl.org/pub/musescore-nightlies/windows/4x/nightly/MuseScoreNightly-latest-master-x86_64-portable.exe)

Achtung: Die oben angegebene Version ist eine Vorabversion und kann Fehler enthalten.
Verwenden Sie diese Version nur für die Übung und nicht für Ihre eigene Arbeit.

Dies ist die offizielle Seite von MuseScore, auf der Sie die neueste Version von MuseScore herunterladen können.  
Link: [https://musescore.org/de/download](https://musescore.org/de/download) 

Es empfiehlt den aktuellen Stand der Arbeit immer wieder zu sichern, um Datenverlust zu vermeiden. Werden Sie eins mit der Tastenkombination ``Strg + S``.

-- David Herzog 2023-10-30 12:33:00

``david.herzog@mozarteum.at``


