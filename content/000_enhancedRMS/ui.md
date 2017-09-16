+++
title = "Die Benutzeroberfläche"
date = 2017-09-16T15:25:49+02:00
draft = false
+++


### Die Benutzeroberfläche <a name="Die Benutzeroberfläche"></a>


Die Taskleiste des AddIns besteht aus verschiedenen Abschnitten. Jeder Abschnitt wird nun seperat erklärt.


#### Das Login-Feld <a name="Das Login-Feld"></a>

![Image 1](/img/001_Login.png)

Dieser Abschnitt wird zur Authentifizierung benötigt. In dem Feld *Username* wird Ihr Nutzername eingetragen. Dieser sollte im *Active Directory* (Rechteverwaltung Ihrer Firma) eingetragen und meistens Ihr Anmeldename von Ihrem Computer sein. Das Gleiche gilt auch für das *Password*. Dieses ist dann das Passwort, welches Sie bei Ihrem Computerstart eingeben müssen.
Sobald die Daten eingegeben sind, kann mit Hilfe des *Login*-Symbols die Anmeldung durchgeführt werden.

Neben den beiden Eingabefenstern befindet sich ein vorerst ausgegrauter Knopf namens *Apply*. Dieser wird benötigt, sobald ein Dokument erstellt und daraufhin diverse Rechte vergeben wurden. Dieser Knopf sorgt dafür, dass sämtliche Rechte angepasst werden. Wie genau eine Rechtevergabe für ein Dokuemt funktioniert lesen Sie unter [Vergabe von Rechten für ein Dokument](/000_enhancedrms/functions/#vergabe-von-rechten-für-ein-dokument).


#### Die generellen Rechte <a name="Die generellen Rechte"></a>

![Image 1](/img/002_GenerelleRechte.png)


In diesem Abschnitt findet die Rechteverwaltung für Ihr Dokument statt. Sie haben hier die Möglichkeit die gewünschten Rechte für Ihr Dokuemnt festzulegen. Wie der Name des Abschnitts schon vermuten lässt werden hier die generellen Rechte vergeben. Das bedeutet, jeder Nutzer der das Dokument öffnet besitzt die gleichen Rechte. Bislang ist hier keine individuelle Anpassung möglich.
Wählen Sie hier nun die Rechte, die für alle Nutzer vergeben werden sollen. Hierbei ist eine Mehrfachauswahl möglich. Möchten Sie eine Person spezielle Rechte zuweisen, so können Sie dies in der nächsten Rubrik tun.

Haben Sie Ihren Text markiert und bestimmte Rechte ausgewählt, so wählen Sie den Knopf *Set Rights* und das AddIn setzt für den markierten Bereich die ausgewählten Rechte.


#### Die individuellen Rechte <a name="Die individuellen Rechte"></a>

![Image 1](/img/003_IndividuelleRechte.png)

Mit Hilfe dieses Abschnitts können Sie vereinzelten Personen spezielle Rechte freigeben. Die Funktionsweise ist hierbei die Selbe wie bei den [generellen Rechten](#Die generellen Rechte). Markieren Sie einen Textabschnitt, wählen Sie das Recht für den Benutzer und bestätigen Sie dies mit einem Klick auf *Set Rights*. Auch hier ist eine Mehrfachauswahl von Rechten möglich.
Um zu definieren, welcher Person diese Rechte zugesprochen werden, wird der nächste Abschnitt verwendet.


#### Das Nutzermanagement <a name="Das Nutzermanagement"></a>

![Image 1](/img/004_User.png)

Diese Rubrik wird für die Nutzerauswahl benötigt. Hier haben Sie die Möglichkeit, Personen hinzuzufügen und für hinzugefügte Personen Rechte an Ihrem Dokument zu vergeben. Geben Sie unter *New User* die E-Mail Adresse des Nutzers ein, den Sie zur Rechteverwaltung hinzufügen möchten. Hierbei muss die E-Mail Adresse des Nutzers eingegeben werden, welche im *Active Directory* eingetragen ist. Mit einem Klick auf *Add User* wird dieser Nutzer Hinzugefügt.

Unter dem Punkt *Existing User's* werden sämtliche Nutzer aufgelistet, die Sie bereits hinzugefügt haben. Dort können Sie nun einen Nutzer auswählen und für diesen die individuellen Rechte anlegen.

%TODO Was ist mit dem Löschen eines Users, gehen dann auch seine Rechte flöten?
