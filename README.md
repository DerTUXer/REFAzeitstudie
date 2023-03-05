# REFAzeit V0.1
Ein Hallo an alle Programmierer dieser Welt. Um REFAzeitstudien durchführen zu
können ist eine teure Hardware und noch teuere Software von nöten.

Mit diesem Projekt möchte ich eine Open Source Variante allen zur Verfügenung 
stellen, damit auch Firmen mit kleim Budget die Möglichkeit haben präzise Vor
gabezeiten (te) / Verteilzeitsutien (tv) / Rüstzeiten (tr) / Störzeiten...
zu ermitteln. 

Da ich nur ein absoluter Laie bin, fehlen mir die benötigten skills. Dennoch
möchte ich mit einem Bash-Script anfangen, da es die einzige Sprache ist, die
ich ansatzweise ein kleines bisschen verstehe.
Für fortgeschnittene Programmiere solltes es daher kein Problem sein soetws zu
programmieren.

Ziel der Software
- Start der Stoppuhr bei 0 HM (Hundertstel Minute)
- Messpunkte nach Fortschrittzeit (in HM)
- Jeder Meßpunkt beinhaltet folgendes
          . fortlaufende Aufnummerierung
          . Eine Ablaufabschnitt Nummer
          . einen Leistungsgrat in %
          . einen Ablaufabschnitt Text (nicht zwingend notwendig)
          . vergabe von Bezugsmenge (BZM) (nicht zwingend notwendig)
          . nach jedem Messpunkt wird das Ergebnis in eine Datei gespeichtert

# Kurze Anleitung der aktuellen Version
Datei-Name bzw. Studien-Name vergeben
Nach Starten läuft die Uhr
Zum setzen des Messpunktes ENTER drücken
Nun die Ablaufabschnitts-Nr. eingeben
Zum Schluss den Leistungsgrad vergeben (Eingabe von %)
Zum Beenden einfach strg + c drücken
