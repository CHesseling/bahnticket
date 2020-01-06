# bahnticket
A short Python script to calculate the distances you've traveled with Deutsche Bahn - by parsing your tickets

Dieses Python-Script berechnet die mit der Deutschen Bahn zurückgelegte Distanz.
Als Input kann man seine Bahnticket-PDFs im Unterordner "/tickets" ablegen und das Script versucht den Start- und Endpunkt herauszufiltern.

Dafür muss die Datei "D_Bahnhof_2017_09.csv" im gleichen Verzeichnis liegen wie das Notebook.

ToDo u.a.:
- Distanzen nicht über API sondern als Offline-File
- Mehrseiten-PDFs
- Weitere Fehler bei der Erkennung von Start und Ziel
- Tatsächliche Fahrtstrecke parsen statt nur Start / Ziel (es gibt ja oft mehrere Wege) 

Version: 0.1

-> Be kind, I'm just a journalist
