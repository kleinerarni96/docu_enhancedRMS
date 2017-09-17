+++
title = "Die Benutzeroberfläche"
date = 2017-09-16T15:25:49+02:00
draft = false
+++


Für einen groben Überblick werden in den folgenden Absätzen sämtliche Bereiche der grafischen Oberfläche erklärt. Hier geht es vorerst nur um die Funktionsweisen der Bereiche. Eine genaue Anleitung, wie ein Dokument verfasst beziehungsweise geöffnet werden kann finden Sie unter [Anwendungsbeispiele](/000_enhancedrms/examples).


## Das Login-Feld

![Image 1](/img/GUI_1.jpg)

Dieser Abschnitt wird zur Authentifizierung benötigt. In dem Feld *Username* wird Ihr Nutzername eingetragen. Dieser sollte im *Active Directory* (Rechteverwaltung Ihrer Firma) eingetragen und meistens Ihr Anmeldename von Ihrem Computer sein. Das Gleiche gilt auch für das *Password*. Dieses ist dann das Passwort, welches Sie bei Ihrem Computerstart eingeben müssen.
Sobald die Daten eingegeben sind, kann mit Hilfe des *Login*-Symbols die Anmeldung durchgeführt werden. Wundern Sie sich dabei nicht, dass das AddIn keine Reaktion in Form einer Rückmeldung abgibt. Diese ist noch nicht implementiert worden.

Neben den beiden Eingabefenstern befindet sich ein vorerst ausgegrauter Knopf namens *Apply*. Dieser wird benötigt, sobald ein Dokument erstellt und daraufhin diverse Rechte vergeben wurden. Nach dem Betätigen des Knopfes wird der Dokumentenschutz und sämtliche vergebenen Rechte auf das Dokument angewandt. Wie genau eine Rechtevergabe für ein Dokuemt funktioniert lesen Sie unter [Vergabe von Rechten für ein Dokument](/000_enhancedrms/examples/#vergabe-von-rechten-für-ein-dokument).


## Die generellen Rechte

![Image 2](/img/GUI_2.jpg)


In diesem Abschnitt findet die Rechteverwaltung für Ihr Dokument statt. Sie haben hier die Möglichkeit die gewünschten Rechte für Ihr Dokument festzulegen. Wie der Name des Abschnitts schon vermuten lässt werden hier die generellen Rechte vergeben. Das bedeutet, jeder Nutzer der das Dokument öffnet besitzt die gleichen Rechte. Bislang ist hier keine individuelle Anpassung möglich.
Wählen Sie hier nun die Rechte, die für alle Nutzer vergeben werden sollen. Es besteht die Möglichkeit, mehrere Rechte auszuwählen und sie gleichzeitig zu setzen. Möchten Sie einer Person spezielle Rechte zuweisen, so können Sie dies in der nächsten Rubrik tun.

Haben Sie Ihren Text markiert und bestimmte Rechte ausgewählt, so wählen Sie den Knopf *Set Rights* und das AddIn setzt für den markierten Bereich die ausgewählten Rechte.


## Die individuellen Rechte

![Image 3](/img/GUI_3.jpg)

Mit Hilfe dieses Abschnitts können Sie vereinzelten Personen spezielle Rechte freigeben. Die Funktionsweise ist hierbei die Selbe wie bei den [generellen Rechten](#Die generellen Rechte). Markieren Sie einen Textabschnitt, wählen Sie das Recht für den Benutzer und bestätigen Sie dies mit einem Klick auf *Set Rights*. Auch hier ist eine Mehrfachauswahl von Rechten möglich.
Um zu definieren, welcher Person diese Rechte zugesprochen werden, wird der nächste Abschnitt verwendet.


## Das Nutzermanagement

![Image 4](/img/GUI_4.jpg)

Diese Rubrik wird für die Nutzerauswahl benötigt. Hier haben Sie die Möglichkeit, Personen hinzuzufügen und für hinzugefügte Personen Rechte an Ihrem Dokument zu vergeben. Geben Sie unter *New User* die E-Mail Adresse des Nutzers ein, den Sie zur Rechteverwaltung hinzufügen möchten. Hierbei muss die E-Mail Adresse des Nutzers eingegeben werden, welche im *Active Directory* eingetragen ist. Mit einem Klick auf *Add User* wird dieser Nutzer hinzugefügt. Wählen Sie nun mit Hilfe des *Existing User's* Menü den Benutzer, für welchen Sie eine individuelle Rechteanpassung vornehmen möchten. Unter dem Punkt *Existing User's* werden sämtliche Nutzer aufgelistet, die Sie bereits hinzugefügt haben. Dort können Sie nun einen Nutzer auswählen und für diesen die individuellen Rechte anlegen. Benötigen Sie einen Nutzer nicht mehr, so können Sie, bei ausgewähltem Nutzer im *Existing User's* Menü, diesen mit einem Klick auf *Remove User* entfernen.
Haben Sie individuelle Rechte für einen Nutzer gesetzt und ihn nachträglich, bevor sie den Dokumentenschutz angewendet haben, entfernt? Keine Sorge, ihre Rechteanpassungen für diesen Benutzer sind weiterhion übernommen. Wenden Sie nur den Dokumentenschutz mit einem Klick auf  [*Apply*](/000_enhancedrms/ui/#das-login-feld) an und ihr Dokument ist mit den gesetzten Rechten geschützt.


