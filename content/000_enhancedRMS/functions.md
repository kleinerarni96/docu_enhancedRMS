+++
title = "Funktionen"
date = 2017-09-16T15:25:49+02:00
draft = false
+++




Das *enhancedRMS* AddIn besitzt eine Vielzahl an Rechten, die für User ausgesprochen werden können. Im Folgenden sind sämtliche Rechte einmal aufgelistet:

1. **View Right / Leserecht**
2. **Write Right / Schreibrecht**
3. Print Right / Druckrecht
4. Export Right / Exportierrecht
5. Save Right / Speicherrecht
6. Grant View Right / Das Recht auf Weitergabe des Leserechts
7. Grant Write Right / Das Recht auf Weitergabe des Schreiberechts
8. Forward Right / Das Recht auf Weiterleitung
9. Full Control Right / Das Recht der vollen Kontrolle

Nur die in der Aufzählung markierten Rechte sind bislang implementiert. Diese können erfolgreich verwendet werden, um ein Dokument gegen unautorisiertes Öffnen beziehungsweise Bearbeiten zu schützen. Im Folgenden werden die Möglichkeiten aufgezeigt, die ein Nutzer bei gewährtem Recht erhält. Die noch nicht implementierten Rechte sind dabei ebenfalls aufgeführt. Ihr Grundgedanke und ihre mögliche Anwendung wurden vorerst mit in diese Auflistung aufgenommen.

Eine Anleitung, wie Sie ein Dokument mit einem Rechten versehen und den Dokumentenschutz anwenden finden Sie [hier](/000_enhancedrms/examples/#vergabe-von-rechten-für-ein-dokument)

### **Das Leserecht**

Das Leserecht ermöglicht es dem Benutzer den Text eines Dokumentes zu lesen. Dabei kann er jedoch nur den Text lesen, für welchen er auch das Leserecht ausgestellt bekommen hat. Besteht beispielsweise ein Dokument aus mehreren Kapiteln und der Autor des Dokumentes hat der besagten Person lediglich das Leserecht für das erste Kapitel erteilt, so kann dieser Nutzer auch lediglich das erste Kapitel lesen, nachdem er das Dokument geöffnet hat. Alle restlichen Textabschnitte werden dem Nutzer nicht angezeigt. Er hat keine Möglichkeit herauszufinden, ob das Dokument ursprünglich mehr Text enthält als er zu Sehen bekommt.

### **Das Schreibrecht**

Bei dem Schreiberecht kann der Nutzer, dem das Recht erteilt wurde, den Text innerhalb des Textabschnittes bearbeiten. Er kann lediglich innerhalb des Abschnittes Ergänzungen bzw. Löschungen vornehmen. Jegliche andere Bereiche sind nicht zu beschreiben. Eine Markierung des Bereiches visualisiert dem Benutzer, in welchem Bereich er Änderungen vornhemen kann und in welchem Bereich nicht.

### Das Druckrecht

**NOCH NICHT IMPLEMENTIERT**

Mit Hilfe dieses Rechtes können Sie festlegen, welche Personen ihr Dokument drucken können. Dabei ist noch nicht bekannt, wie dieses Recht am Ende implementiert wird. Dabei könnte beispielsweise nur der markierte Bereich mit einem Druckrecht versehen  oder das komplette Dokument mit dem Setzen des Rechtes zum Drucken freigegeben werden.

### Das Exportierrecht

**NOCH NICHT IMPLEMENTIERT**

Dieses Recht ermöglicht dem Benutzer das Dokument zu exportieren. Exportieren umfasst hierbei den Export von einem Worddokument in ein Dokument mit anderer Endung. Beispielsweise kann eine .docx Datei per Export in eine .odt, .doc oder .rtf Datei umgewandelt werden. Außerdem kann aus ihr ein PDF/XPS Dokument erstellt werden. Auch hier ist weiterhin unklar, wie dieses in Zukunft implementiert wird.


### Das Speicherrecht

**NOCH NICHT IMPLEMENTIERT**

Mit Hilfe dieses Rechts ist ein Benutzer lediglich in der Lage, das Dokument unter einem anderen Namen abzuspeichern (das Dokument zu kopieren). Wie die Prozedur beim Setzen des Rechtes aussehen soll, ist bislang ebenfalls unbekannt.

### Das Recht auf Weitergabe des Leserechts

**NOCH NICHT IMPLEMENTIERT**

Sobald Sie dieses Recht einem Benutzer aussprechen, hat dieser die Möglichkeit weiteren Nutzern das Leserecht zu erteilen. Geben Sie der Person allerdings dieses Recht nur für einen bestimmten Textabschnitt, so kann er auch nur für diesen Textabschnitt das Leserecht an andere Personen weitergeben.


### Das Recht auf Weitergabe des Schreiberechts

**NOCH NICHT IMPLEMENTIERT**

Auch hier hat der Benutzer, welcher dieses Recht zugesprochen bekommen hat, die Möglichkeit, anderen Nutzern das Schreibrecht zu erteilen. Geben Sie der Person allerdings dieses Recht nur für einen bestimmten Textabschnitt, so kann sie auch nur für diesen Textabschnitt das Schreiberecht anderen Personen erteilen.

### Das Recht auf Weiterleitung

**NOCH NICHT IMPLEMENTIERT**

Dieses Recht befähigt eine Person, das Dokument per Email verschicken zu können. Dabei ist die Idee, dass die E-Mail beispielsweise an eine Person in einer anderen Firma geschickt werden kann, welche nicht im firmeninternen Active Directoy vorhanden ist. Geplant ist damit eine Ausweitung des Schutzes.

### Das Recht der vollen Kontrolle

**NOCH NICHT IMPLEMENTIERT**

Besitzt ein Nutzer dieses Recht, so hat er die gleichen Möglichkeiten wie Sie als Autor des Dokumentes. Diese Person erlangt vollen Schreibzugriff auf das Dokument, kann weiteren Nutzern Rechte aussprechen und ihr Dokument nach belieben formatieren, drucken, exportieren und so weiter. 


