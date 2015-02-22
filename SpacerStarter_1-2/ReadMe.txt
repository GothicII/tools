SpacerStarter 1.2 by Lubo
-------------------------
*************************

Der SpacerStarter wurde am 07.01.2006 als 
Hilfstool für den Minemod geschrieben.
Er ist für alle Gothic-Modder frei verfügbar.


Version 1.2:
Ab jetzt ist auch der SpacerStarter für den Gothic 2
Spacer dabei.


Dateien:
Spacer1Starter.exe: der SpacerStarter für Gothic I
Spacer2Starter.exe: der SpacerStarter für Gothic II
ReadMe.txt: Informationen zum SpacerStarter


Installation:
Kopiert einfach die Spacer1Starter.exe in euren Gothic-Ordner (bzw.
die Spacer2Starter.exe in euren Gothic 2-Ordner) unter
\system. Dann führt die exe aus. Der SpacerStarter wird sich dann
automatisch installieren und eine Meldung ausgeben, wenn die Installation
erfolgreich war. ACHTUNG: der SpacerStarter benennt eure originale
spacer.exe in spacer_exe.exe um und nennt sich selber spacer.exe!
Wenn ihr ihn also deinstallieren wollt, müsst ihr die spacer.exe
löschen und die spacer_exe.exe in spacer.exe umbennen. 


Nutzen:
Der SpacerStarter startet, wie der Name schon sagt, den Spacer.
Weil viele Leute Probleme mit dem Spacer haben, weil z.B. das
Hauptfenster verschwindet, startet der SpacerStarter den Spacer
so, dass alle Fenster sichtbar sind. Normalerweise müsste das
durch das einfache Löschen eines Registry-Eintrages klappen,
da das aber leider nicht funktioniert hat, habe ich noch eine
Funktion zum maximierten Starten des Spacers eingebunden.
Es gab ursprünglich auch die Option, eine Anfrage zu erhalten,
ob der Spacer maximiert oder oder nicht maximiert gestartet 
werden soll. Da das nicht maximierte Starten zwar meist, aber
nicht immer funktioniert, habe ich diese Option versteckt. Ihr 
könnt sie anschalten, in dem ihr den Registry-Wert
HKEY_CURRENT_USER\Software\SpacerStarter\Spacer1Starter\AskForStartMode
auf 1 setzt. Eine weitere weggelassene Option ist der
Standard-Startmodus. Er ist immer auf 1, d.h. maximiert gesetzt.
Wenn ihr ihn auf "nicht maximiert" schalten wollt, dann setzt den Registry-
Wert HKEY_CURRENT_USER\Software\SpacerStarter\Spacer1Starter\DefaultStartMode
auf 2. Um die Optionen für den SpacerStarter für Gothic 2 zu verändern,
müsst ihr natürlich entsprechend die Werte im Unterschlüssel \Spacer2Starter\
ändern. Wenn euch das alles zu kompliziert ist, dann lassts einfach weg ;-).


Viel Spaß mit dem SpacerStarter,
Lubo