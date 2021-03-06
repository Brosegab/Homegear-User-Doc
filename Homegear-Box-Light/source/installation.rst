Installation
************

Inbetriebnahme
==============

Aufbau
------

.. tip:: Bevor Sie starten, überprüfen Sie bitte ob alle mitgelieferten Gegenstände vollständig und in gutem Zustand sind.

- Diese sind unter :ref:`Mitgeliefert <Link-auf-Mitgeliefert>` aufgelistet.
  Sollten sie nicht im Guten Zustand oder nicht vollständig sein Senden Sie sie bitte an uns zurück.

- Der erste Schritt ist die Homegear-Box mit dem mitgeliefertem Netzstromkabel zu verbinden, sowie den Netzstecker mit einer Steckdose in ihrem Haus.
  Nach dem das Netzkabel angeschlossen wurde leuchtet eine rote Konroll-LED auf, die die Verbindung bestätigt.

.. caution:: Wenn Sie den Netzstecker ziehen, um die Homegear-Box auszuschalten, warten Sie mindestens 5 Sekunden bevor Sie diesen wieder einstecken.

- Als nächstes wird noch das beigefügte LAN-Kabel benötigt, welches an die Homegear-Box und an die Netzwerksteckdose angeschlossen wird.
  Nach dem das Netzwerkkabel angeschlossen wurde leuchten zwei LEDs auf, grün(blinkend) und gelb(leuchtend). 

Wer ein Adapter zugekauft hat muss nur die mitgelieferte Brücke in die dafür vorgesehenen Steckverbindungen beider Boxen einsetzen um eine Verbindung zu der Homegear-Box und dem Adapter herzustellen

Nun kann Ihre Homegear-Box senden und empfangen und ist bereit von Ihnen programmiert zu werden.



Software
--------

1. Voraussetzung ist ein Browserfähiges Gerät
2. Stellen Sie sicher, dass sich ihre Homegear-Box im gleichen Heimnetz befindet, wie das Gerät mit dem sie auf ihr Netzwerk zugreifen
3. Starten Sie wenn nicht schon geschehen ihren PC, Labtop oder Sonstiges und öffnen Sie den Internetbrowser   

- Um die Homegear-Box im Netzwerk zu finden wird einen IP-Scanner benötigt, der unter diesem Name heruntergeladen werden kann:
.. _Link-auf-Advanced-IP-Scanner:
`Advanced IP Scanner <http://www.advanced-ip-scanner.com/de/>`

Sobald der Download fertig ist kann das Programm aktivieren werden - bitte als Nächstes auf die Downloaddatei klicken, ausführen und 
anschliesend die gewünschte Sprache wählen und mit "Ok" bestätigen 

Wer die Datei installieren möchte kann auf "Weiter >" klicken, wer sie sich nicht installieren will wählt den Punkt neben Ausführen an und klickt "Weiter >"

Lesen Sie bitte die Lizenzvereinbarung, klicken Sie auf den Punkt neben "ich akzeptiere die Vereinbarung" und bestätigen Sie mit dem Button "Ausführen"

Das Fenster mit dem Namen "Advanced IP Scanner", dass sich nach der Bestätigung geöffnet hat enthält einen Button "Scannen", mit dem die Homegear-Box gesucht wird 

Das Programm wird die Geräte anzeigen, welche sich in der Nähe des Computers befinden bzw. im gleichen LANNetz verbunden sind

Nachdem das Programm fertig ist muss nach "Raspberry Pi Foundation" gesucht werden, um die IP-Adresse(Name) zu finden

.. caution:: In der Spalte wird jetzt der ""Name"" angezeigt, der aus einer **Reihe von Zahlen besteht**, diesen **Bitte in irgend einer Form speichern** - Beispiel: 192.168.9.999

Nun ist ihre Homegear-Box gefunden, um sich mit ihr zu verbinden muss ""Name"":2001/admin/ in den Internetbrowser eingegeben und mit der 
Entertaste bestätigt werden - Beispiel: 192.168.9.999:2001/admin/

Sollte es nicht funktionieren, überprüfen Sie bitte noch einmal ob die Eingabe bzw. der gefundene ""Name"" auch der Richtige ist 

Wenn die Verbindung aufgebaut wurde ist dieser Startseiteninhalt zu sehen

.. image:: Startseite.png

Der :ref:`Advanced IP Scanner <Link-auf-Advanced-IP-Scanner>` kann geschlossen bzw. gelöscht werden, er ist für die weitere Verwendung nicht mehr relevant 

.. note:: Hier dürfen Sie sich einen Anmeldenamen/Benutzernamen ausdenken und ein Passwort überlegen, welches Sie auch unbedingt in irgendeiner Form speichern sollten. Es spielt keine Rolle wie klein oder groß ihr Benutzername bzw. Passwort ist, dieser wird allein vom Eingabespeicher begrenzt. Bitte geben Sie dann anschliesend ihren Benutzernamen und ihr Passwort ein, bestätigen Sie ihr Passwort und klicken Sie auf "Anmelden".

.. image:: Dashboard.png

Oben Rechts, wie im Bild gezeigt, wird zwischen den Sprachen Deutsch und Englisch gewechselt, da die Voreinstellung Englisch ist, wird empfohlen Aufgrund der Anleitung auf Deutsch umzuschalten

.. image:: Sprache.png

Neben dem gerade benutzten Symbol der Sprachauswähl ist ein weiteres Symbol zu sehen, dass an eine Klocke oder Klingel erinnert, welche Fehlermeldungen entgegennimmt und anzeigt  

Ihr Profil können Sie über den rechten Oberen Button anwählen und ändern, 
Auserdem können Sie die Gruppe ändern auf die der Benutzer Zugriff haben soll.  

.. image:: Profil.png

Wie zu sehen ist zeigt das Dashboard die Systeminformationen, installierte Module, Geräte und die Netzwerkschnittstellen auf.
Es enthält die wichtigsten technischen Daten, die sehr überschaubar einzulesen sind.
Wenn Sie fertig sind klicken Sie auf "Speichern".



Inventar
^^^^^^^^

Beim Öffnen des Inventars werden folgende Unterpunkte ausgefahren

.. image:: Geräte.png

Geräte
""""""

Hier kann die (Dateiformat)Familie ausgewählt werden mit der das anzuschliesende Gerät arbeitet. 
Nächster Punkt ist das Gerät selbst und der Type des Gateways 

.. _Link-auf-Familien:

.. note :: Eine Familie ist ein Dateiformat bestimmter Geräte, die bei jedem Gerät unterschiedlich sein kann. Sie ist auf jedem Gerät bzw. Beschreibung des Geräts vermerkt und muss mit angelernt und ausgewählt werden

.. note :: Ein Gateway ist sowas wie ein Übersetzter, es übersetzt die Sprache eines Gerätes in die, mit der die Homegear-Box kommuniziert, wenn alle benötigten Gateways vorhanden sind können sich alle Geräte miteinander verbinden (kommunizieren)


Gateways
""""""""

Hier kann die (Dateiformat)Familie und anschliesend auch der Type des Gateways ausgewählt werden

.. _Link-auf-Räume:

Räume
"""""

Der Raumname ist beim Anklicken der Schaltfläche "Raum hinzufügen" zu erstellen bzw. zu ändern.
Wenn das Abschalten eines Raumes erwünscht wird kann dies so in z.B. Node Blude einfach eingestellt werden 
mehr dazu unter :ref:`Konfiguration <Link-auf-Konfiguration>`   

.. _Link-auf-Stockwerke:

Stockwerke
""""""""""

Es hat die gleiche Funktion wie Räume, nur dass die Funktion Stockwerke alle Räume in diesem Stockwerk einbinden soll,
um ein ganze Wohnung oder Ebene im Haus auf einen Befehl hin ansteuern zu können 

.. _Link-auf-Gruppen:

Gruppen
"""""""

Mit Gruppen sind Geräteverknüpfungen gemeint, die Sie gerne verbunden haben möchten und sich mit einem Befehl steuern lassen 
Somit lassen sich alle Lichter oder nur gewünschte Lichter-Gruppen kontrollieren, was sehr komfortabel ist   


.. _Link-auf-Variablen:

Variablen
"""""""""

Hier kann der Variablenname für die Geräte vergeben und auch der Type definiert werden
Auserdem ist sie "Global" und kann auch in anderen Programmierplattformen unter dem gleichen Namen verwendet werden 

.. tip:: Es ist wichtig sich Räume Stockwerke oder Gruppen anzulegen, um einen Überblick für alle angeschlossenen Systeme zu haben 

.. note:: Die (Dateiformat)Familie oder Protokollfamilie ist auf jedem Gerät vermerkt




Programmierung
^^^^^^^^^^^^^^

Node-BLUE ist unsere Programmierplattform für die Verknüpfung der Geräte im Haus

Hier werden die Verknüpfungen der Geräte bearbeitet, mehr dazu unter dem Punkt :ref:`Programmierung <Link-auf-Konfiguration>`




Einstellungen
^^^^^^^^^^^^^

.. image:: Einstellungen.png

Hier befinden sich die Benutzter und Module welche gelistet werden wie im Inventar


Benutzter
"""""""""

Hier kann der Benutzername, die Sicherung über ein Passwort und die Zuweisung in eine Gruppe eingestellt werden
Mit dieser Funktion können mehrere Personen mit verschieden vergebenen Berechtigungen Homegear steuern   

.. _Link-auf-Module:

Module
""""""

Hier werden die vorhandenen Module gelistet die geladen sind, es besteht die Möglichkeit diese hier zu deaktivieren oder neu zu laden



Wartung
^^^^^^^

.. image:: Wartung.png

Dienste, Aktualisierungen und Sicherungen können hier überprüft und eingesehen werden 


Dienst
""""""

Wenn Sie die Zentrale neu starten wird Ihre "Homegear-Box" neu gestartet, wenn etwas nicht mehr richtig funktioniert ist es zu empfehlen die Homegear-Box einmal Neu zu Starten  


Aktualisierungen
""""""""""""""""

Wenn eine neue Aktualisierung vorliegt bitte auf den Button "Aktualisierungen installieren" klicken, wenn sie die Aktualisierungsbitten ignorieren, kann es schlimmstenfalls zur kompletten Funktionslosigkeit führen
.. caution:: Bitte nehmen Sie sich die Zeit um die Aktualisierung durchzuführen 


Sicherung
"""""""""

Hier kann eine Sicherung erstellt oder bei Bedarf wiederhergestellt werden
Um die eigene Programmierung vor Verlust zu schützen ist es hilfreich eine Sicherung nach jedem Benutzen zu erstellen, um bei Verlust diese wieder herstellen zu können  



Homegear-Box Eigenschaft
------------------------

Die Homegear-Box arbeitet mit den Funktionen eines Raspberry Pi's, deshalb verhält er sich wie ein kleiner aber normaler Computer

Er bietet einen Desktop auf Linux basierend, sowie ein Ordnerverzeichnis, ein Rechentool und sonstige Fuktionen 

Wer in als kleinen Computer verwenden will kann Monitor, Tastatur, Maus, Heatset :ref:`etc.<Link-auf-Hardware-Spezifikation>` anschliesen

.. caution:: Aber Achtung wer nicht sicher ist was er tut sollte auf keinen Fall auf diese Option zugreifen, alle Änderungen die zu einem Funktionsverlust von Homegear führen müssen für die Wiederherstellung kostenpflichtig behoben werden.