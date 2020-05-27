---
Text: Text
Hello: Hallo
---

<a href="https://gitlocalize.com/repo/4578/ru?utm_source=badge"> <img src="https://gitlocalize.com/repo/4578/ru/badge.svg"> </a>

# ![Markdown Here Logo](https://raw.github.com/adam-p/markdown-here/master/src/common/images/icon48.png) Markdown hier

[**Besuchen Sie die Website.**](http://markdown-here.com)<br>
[**Hol es dir für Chrome.**](https://chrome.google.com/webstore/detail/elifhakcjgalahccnjkneoccemfahfoa)<br>
[**Hol es dir für Firefox.**](https://addons.mozilla.org/en-US/firefox/addon/markdown-here/)<br>
[**Hol es dir für Safari.**](https://s3.amazonaws.com/markdown-here/markdown-here.safariextz)<br>
[**Hol es dir für Thunderbird und Postbox.**](https://addons.mozilla.org/en-US/thunderbird/addon/markdown-here/)<br>
[**Hol es dir für Opera.**](https://addons.opera.com/en/extensions/details/markdown-here/)<br>
[**Besprechen Sie es und stellen Sie Fragen in der Google-Gruppe.**](https://groups.google.com/forum/?fromgroups#!forum/markdown-here/)<br>

*Markdown Hier finden Sie* eine Erweiterung für Google Chrome, Firefox, Safari, Opera und Thunderbird, mit der Sie E-Mails <sup>†</sup> in Markdown <sup>‡</sup> schreiben und vor dem Senden rendern können. Es unterstützt auch die Syntaxhervorhebung (geben Sie einfach die Sprache in einem umzäunten Codeblock an).

Das Schreiben von E-Mails mit Code ist ziemlich mühsam. Das Schreiben von Markdown mit Code ist einfach. Ich habe E-Mails in Markdown im Github-Editor geschrieben und dann die Vorschau in E-Mails kopiert. Dies ist ein ziemlich absurder Workflow, daher habe ich beschlossen, ein Tool zum Schreiben und Rendern von Markdown direkt in der E-Mail zu erstellen.

To discover what can be done with Markdown in *Markdown Here*, check out the [Markdown Here Cheatsheet](https://github.com/adam-p/markdown-here/wiki/Markdown-Here-Cheatsheet) and the other [wiki pages](https://github.com/adam-p/markdown-here/wiki).

<sup>†: Und Google Groups-Posts und Blogger-Posts sowie Evernote-Notizen und Wordpress-Posts! <a href="#compatibility">Mehr sehen</a> .</sup><br>
<sup>‡: Und mathematische TeX-Formeln!</sup>

![Screenshot der Konvertierung](https://raw.github.com/adam-p/markdown-here/master/store-assets/markdown-here-image1.gimp.png)

### Inhaltsverzeichnis

**[Installationsanleitung](#installation-instructions)**<br>
**[Gebrauchsanweisung](#usage-instructions)**<br>
**[Fehlerbehebung](#troubleshooting)**<br>
**[Kompatibilität](#compatibility)**<br>
**[Notizen und Sonstiges](#notes-and-miscellaneous)**<br>
**[Erstellen der Erweiterungspakete](#building-the-extension-bundles)**<br>
**[Nächste Schritte, Credits, Feedback, Lizenz](#next-steps)**<br>

## Installationsanleitung

### Chrom

#### Chrome-Webstore

Rufen Sie die [Chrome Web Store-Seite für *Markdown Here auf*](https://chrome.google.com/webstore/detail/elifhakcjgalahccnjkneoccemfahfoa) und installieren Sie sie normal.

Stellen Sie nach der Installation sicher, dass Sie Ihre Webmail neu laden oder Chrome neu starten!

#### Handbuch / Entwicklung

1. Klonen Sie dieses Repo.
2. Öffnen Sie in Chrome die Einstellungen für Erweiterungen. (Schraubenschlüssel-Taste, Werkzeuge, Erweiterungen.)
3. Aktivieren Sie auf der Seite Erweiterungseinstellungen das Kontrollkästchen "Entwicklermodus".
4. Klicken Sie auf die jetzt sichtbare Schaltfläche "Entpackte Erweiterung laden ...". Navigieren Sie zu dem Verzeichnis, in das Sie das Repo geklont haben, und dann zum `src` Verzeichnis darunter.
5. Die *Markdown Here-* Erweiterung sollte jetzt in Ihrer Erweiterungsliste sichtbar sein.
6. Laden Sie Ihre Webmail-Seite (und möglicherweise Ihre Anwendung) neu, bevor Sie versuchen, eine E-Mail zu konvertieren.

### Firefox und Thunderbird

#### Mozilla Add-Ons-Site

Gehen Sie zur [Firefox-Add-On-Seite für *Markdown Here*](https://addons.mozilla.org/en-US/firefox/addon/markdown-here/) und installieren Sie sie normal.

Oder gehen Sie zum Menü "Extras> Add-Ons" und suchen Sie nach "Markdown Here".

Starten Sie nach der Installation Firefox / Thunderbird neu!

**Hinweis:** Es dauert bis zu einem Monat, bis Mozilla Änderungen an der Firefox / Thunderbird-Erweiterung genehmigt hat, sodass Aktualisierungen (Funktionen, Korrekturen) hinter den hier gezeigten zurückbleiben. Sie können die neueste Version manuell installieren, bevor sie aus der Liste der Versionen überprüft wird: [https://addons.mozilla.org/en-US/firefox/addon/markdown-here/versions/](https://addons.mozilla.org/en-US/firefox/addon/markdown-here/versions/)

#### Handbuch / Entwicklung

1. Klonen Sie dieses Repo.
2. Befolgen Sie die Anweisungen im MDN-Artikel ["Einrichten einer Erweiterungsentwicklungsumgebung"](https://developer.mozilla.org/en/Setting_up_extension_development_environment) .

### Safari

[Laden Sie die Erweiterung direkt herunter.](https://s3.amazonaws.com/markdown-here/markdown-here.safariextz) Wenn der Download abgeschlossen ist, doppelklicken Sie zum Installieren darauf.

#### Einstellungen

Um zu den Markdown Here-Einstellungen zu gelangen, öffnen Sie die Safari-Einstellungen und wechseln Sie dann zur Registerkarte "Erweiterungen". Klicken Sie dann auf das Feld "Klicken Sie auf mich, um die Markdown Here-Optionen anzuzeigen".

### Oper

Beachten Sie, dass *Markdown Here* nur mit Opera-Versionen 16 und höher funktioniert (dh mit solchen, die auf Chromium basieren).

Gehen Sie zur [Store-Seite von Opera Add-ons für *Markdown Here*](https://addons.opera.com/en/extensions/details/markdown-here/) und installieren Sie sie normal.

Stellen Sie nach der Installation sicher, dass Sie Ihre Webmail neu laden oder Chrome neu starten!

## Gebrauchsanweisung

Installieren Sie es und dann ...

1. Stellen Sie in Chrome / Safari / Opera *sicher, dass* Sie Ihre Webmail-Seite neu laden, bevor Sie versuchen, Markdown Here zu verwenden.

2. Melden Sie sich in Chrome / Firefox / Safari / Opera bei Ihrem Google Mail-, Hotmail- oder Yahoo-Konto an und starten Sie eine neue E-Mail. Starten Sie in Thunderbird eine neue Nachricht.

3. Stellen Sie sicher, dass Sie den Rich Editor verwenden.

    - Klicken Sie in Google Mail auf den Link "Rich Formatierung", falls dieser sichtbar ist.
    - Stellen Sie in Thunderbird sicher, dass "Nachrichten im HTML-Format verfassen" in Ihrem Bereich "Kontoeinstellungen", "Zusammensetzung und Adressierung" aktiviert ist.

4. Verfassen Sie eine E-Mail in Markdown. Zum Beispiel:

    <pre>** Hallo ** `Welt`. `` `Javascript-Alarm ('Hallo Syntaxhervorhebung.'); `` `</pre>

5. Klicken Sie mit der rechten Maustaste in das Erstellungsfeld und wählen Sie im Kontextmenü den Eintrag "Markdown Toggle". Oder klicken Sie auf die Schaltfläche in Ihrer Adressleiste. Oder verwenden Sie den Hotkey (standardmäßig <kbd>STRG</kbd> + <kbd>ALT</kbd> + <kbd>M</kbd> ).

6. Sie sollten sehen, dass Ihre E-Mail von Markdown korrekt in Rich HTML gerendert wurde.

7. Senden Sie Ihre tolle E-Mail an alle, die Sie kennen. Es wird ihnen genauso erscheinen, wie es für Sie aussieht.

### Zurück zu Markdown

Nachdem Sie Ihren Markdown in hübsches HTML gerendert haben, können Sie immer noch zu Ihrem ursprünglichen Markdown zurückkehren. Klicken Sie einfach mit der rechten Maustaste auf eine beliebige Stelle im neu gerenderten Markdown und klicken Sie auf "Markdown-Umschaltung". Ihr E-Mail-Erstellungskörper ändert sich wieder in den von Ihnen geschriebenen Markdown.

Beachten Sie, dass alle Änderungen, die Sie am hübschen HTML-Code vornehmen, verloren gehen, wenn Sie zu Markdown zurückkehren.

In Google Mail können Sie auch den Befehl "Rückgängig" des Browsers verwenden ( <kbd>STRG</kbd> + <kbd>Z</kbd> / <kbd>CMD</kbd> + <kbd>Z</kbd> oder über das Menü "Bearbeiten"). Seien Sie gewarnt, dass Sie möglicherweise auch die letzten eingegebenen Zeichen verlieren.

### Antworten

In Google Mail, Thunderbird und Google Groups können Sie "Markdown Toggle" normalerweise verwenden: Schreiben Sie einfach Ihre Antwort (oben, unten, inline, wo auch immer) und konvertieren Sie sie dann. Die ursprüngliche E-Mail, auf die Sie antworten, wird in Ruhe gelassen. (Technisch: Vorhandene `blockquote` Blöcke bleiben erhalten.)

In Hotmail und Yahoo (die das Original nicht in ein `blockquote` ) und optional in Google Mail, Thunderbird und Google Groups können Sie sicherstellen, dass nur der Teil der Antwort, den Sie geschrieben haben, konvertiert wird, indem Sie auswählen, was Sie konvertieren möchten und dann auf "Markdown Toggle" klicken - siehe nächster Abschnitt.

### Auswahl / stückweise Umwandlung

Manchmal möchten Sie nicht die gesamte E-Mail konvertieren. Manchmal ist Ihre E-Mail nicht ganz Markdown. Um nur einen Teil der E-Mail zu konvertieren, wählen Sie den Text aus (mit der Maus oder Tastatur), klicken Sie mit der rechten Maustaste darauf und klicken Sie auf den Menüpunkt "Markdown Toggle". Ihre Auswahl wird auf magische Weise in hübsches HTML gerendert.

Um zu Markdown zurückzukehren, setzen Sie den Cursor einfach an eine beliebige Stelle im konvertierten Textblock, klicken Sie mit der rechten Maustaste und klicken Sie erneut auf den Menüpunkt "Markdown Toggle". Jetzt ist es magisch zurück zum ursprünglichen Markdown.

![Screenshot der Auswahlkonvertierung](https://raw.github.com/adam-p/markdown-here/master/store-assets/markdown-here-image2.gimp.png)

#### Wissenswertes zum Konvertieren / Zurücksetzen einer Auswahl

- Wenn Sie nur einen Teil eines Textblocks auswählen, wird nur dieser Text konvertiert. Der konvertierte Block wird in ein Absatzelement eingeschlossen, sodass die ursprüngliche Zeile aufgeteilt wird. Sie wollen das wahrscheinlich nie tun.

- Sie können mehrere konvertierte Blöcke gleichzeitig auswählen und zurücksetzen. Ein Ergebnis davon ist, dass Sie Ihre gesamte E-Mail auswählen, auf "Markdown Toggle" klicken können und alle Teile davon, die Sie konvertiert haben, zurückgesetzt werden.

- Wenn Sie beim Klicken auf "Markdown Toggle" nichts ausgewählt haben, überprüft *Markdown Here* , ob sich irgendwo in der Nachricht konvertierte Blöcke befinden, und setzt sie zurück. Wenn keine konvertierten Blöcke gefunden werden, wird die gesamte E-Mail konvertiert.

### Optionen

Auf die Seite *Markdown Here* Options kann über die Erweiterungsliste Chrome, Firefox, Safari oder Thunderbird zugegriffen werden. Die verfügbaren Optionen umfassen:

- Styling-Änderungen für den gerenderten Markdown.
- Syntax zur Hervorhebung der Themenauswahl und -änderung.
- Aktivierung und Anpassung der Verarbeitung von TeX-Mathematikformeln.
- Was der Hotkey sein sollte.

Für Chrome und Firefox werden alle Änderungen, die in den *Markdown Here-* Optionen vorgenommen wurden, automatisch zwischen Ihren anderen Installationen dieses Browsers synchronisiert (wenn Sie die Synchronisierungsfunktion im Browser aktiviert haben).

![Screenshot der Optionen](https://raw.githubusercontent.com/adam-p/markdown-here/master/store-assets/markdown-here-chrome-options-1.gimp.png)

## Fehlerbehebung

See the [Troubleshooting wiki page](https://github.com/adam-p/markdown-here/wiki/Troubleshooting).

## Kompatibilität

Siehe die [Kompatibilitäts-Wiki-Seite](https://github.com/adam-p/markdown-here/wiki/Compatibility) .

## Notizen und Sonstiges

- *Markdown Hier* wird [Github Flavored Markdown verwendet](http://github.github.com/github-flavored-markdown/) , mit der Einschränkung, dass spezielle GFM-Links nicht unterstützt werden ( [Problem Nr. 11](https://github.com/adam-p/markdown-here/issues/11) ). Sie werden es auch nicht sein, da MDH nicht Github-spezifisch ist.

- Die verfügbaren Sprachen für die Syntaxhervorhebung (und die Art und Weise, wie sie in den eingezäunten Codeblock geschrieben werden sollen) sind auf der [Demoseite vonlight.js](http://softwaremaniacs.org/media/soft/highlight/test.html) zu sehen.

- Inline in Ihren Markdown eingebettete Bilder bleiben beim "Markdown Toggle" erhalten. Mit Google Mail können Sie Bilder in Ihre E-Mail einfügen. Dies ist möglicherweise viel einfacher als das Verweisen auf ein externes Bild.

- E-Mail-Signaturen werden automatisch von der Konvertierung ausgeschlossen. Insbesondere wird alles nach dem Semi-Standard `'-- '` (beachten Sie das nachfolgende Leerzeichen) in Ruhe gelassen.

    - Beachten Sie, dass Hotmail und Yahoo Signaturen *nicht* automatisch mit dem `'-- '` , sodass Sie es selbst hinzufügen müssen.

- Der Menüpunkt "Markdown Toggle" wird für mehr Elementtypen angezeigt, als korrekt gerendert werden können. Dies soll den Leuten helfen, zu erkennen, dass sie keinen umfangreichen Editor verwenden. Andernfalls sehen sie den Menüpunkt einfach nicht und wissen nicht warum.

- Styling:

    - Die Verwendung von browserspezifischen Stilen (-moz-, -webkit-) sollte vermieden werden. Wenn sie verwendet werden, werden sie möglicherweise nicht korrekt gerendert, wenn Personen die E-Mail in einem anderen Browser als dem, in dem die E-Mail gesendet wurde, lesen.
    - Die Verwendung zustandsabhängiger Stile (wie `a:hover` ) funktioniert nicht, da sie zum Zeitpunkt der expliziten Darstellung der Stile nicht übereinstimmen. (In E-Mails müssen Stile explizit auf alle Elemente angewendet werden - Stylesheets werden entfernt.)

- Weitere optimierte Funktionen finden Sie im Abschnitt [Tipps und Tricks](https://github.com/adam-p/markdown-here/wiki/Tips-and-Tricks) .

## Erstellen der Erweiterungspakete

```
cd utils
node build.js
```

### Chrome- und Opera-Erweiterung

Erstellen Sie eine Datei mit der Erweiterung `.zip` die folgende Dateien und Verzeichnisse enthält:

```
manifest.json
common/
chrome/
```

### Firefox / Thunderbird-Erweiterung

Erstellen Sie eine Datei mit der Erweiterung `.xpi` die folgende Dateien und Verzeichnisse enthält:

```
chrome.manifest
install.rdf
common/
firefox/
```

### Safari-Erweiterung

Der browserspezifische Code befindet sich im [`markdown-here-safari`](https://github.com/adam-p/markdown-here-safari) Projekt.

Verwenden Sie den Safari Extension Builder.

## Nächste Schritte

Siehe die [Problemliste](https://github.com/adam-p/markdown-here/issues) und das [Notes-Wiki](https://github.com/adam-p/markdown-here/wiki/Development-Notes) . Alle Ideen, Fehler, Pläne, Beschwerden und Träume werden an einem dieser beiden Orte landen.

Sie können gerne ein Problem mit Funktionsanfragen erstellen, wenn das, was Sie möchten, noch nicht vorhanden ist. Wenn Sie einen weniger formellen Ansatz bevorzugen, um eine Idee zu veröffentlichen, veröffentlichen Sie sie in der [Google-Gruppe "Markdown-Here"](https://groups.google.com/forum/?fromgroups=#!forum/markdown-here) .

Es ist auch einiges an Arbeit erforderlich, um über die neuesten Änderungen in allen Anwendungen und Websites, auf denen Markdown Here funktioniert, auf dem Laufenden zu bleiben.

## Credits

*Markdown Hier* wurde auf den Schultern von Riesen codiert.

- Markdown-to-HTML: [chjj / markiert](https://github.com/chjj/marked)
- Syntaxhervorhebung: [isagalaev / Highlight.js](https://github.com/isagalaev/highlight.js)
- HTML-zu-Text: [mtrimpe / jsHtmlToText](https://github.com/mtrimpe/jsHtmlToText)

## Feedback

Alle Fehler, Funktionsanfragen, Pull-Anfragen, Rückmeldungen usw. sind willkommen. [Erstellen Sie ein Problem](https://github.com/adam-p/markdown-here/issues) . Oder [posten Sie in der Google-Gruppe "Abschriften hier"](https://groups.google.com/forum/?fromgroups=#!forum/markdown-here) .

## Lizenz

### Code

MIT License: http://adampritchard.mit-license.org/ or see [the `LICENSE` file](https://github.com/adam-p/markdown-here/blob/master/LICENSE).

### Logo

Copyright 2015, [Austin Anderson](http://protractor.ninja/) . Lizenziert für Markdown Hier unter der [MDH-Lizenzvereinbarung](https://github.com/adam-p/markdown-here/blob/master/CLA-individual.md) .

### Andere Bilder

[Creative Commons Attribution 3.0 Unported (CC BY 3.0) -Lizenz](http://creativecommons.org/licenses/by/3.0/)

---

![Dos Equis Mann sagt](https://raw.github.com/adam-p/markdown-here/master/store-assets/dos-equis-MDH.jpg)

- Anfragen ziehen
- Es erfordert auch einiges an Arbeit
- Lizenz
- Error
- Code
