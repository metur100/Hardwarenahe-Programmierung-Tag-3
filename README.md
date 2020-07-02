# Hardwarenahe-Programmierung-Tag-3
 In dieser Ubung arbeiten Sie intensiver mit dem Stack in Assembler und implementieren Funktionen und Funktionsaufrufe nach C-Standard in Assembler.

# Aufgabe 1 Stackentwicklung
Betrachten Sie das folgende Beispiel zur Stackentwicklung aus der Vorlesung.
push dword 0xDEADBEEF
push dword 0xCAFEAFFE
pop eax
pop ebx
Schreiben Sie ein Programm, welches die obigen Befehle ausfuhrt und dabei die Stackentwicklung
sichtbar macht. Das heiﬂt, Ihr Programm sollte bei jeder Anderung des Stacks genau die relevanten
Teile des Stacks ausgeben.

# Aufgabe 2 Stack

Schreiben Sie ein Assembler-Programm, welches zehn Zeichen (char) interaktiv einliest und diese in
umgekehrter Reihenfolge ausgibt. Verwenden Sie keine lokalen oder globalen Variablen fur die Losung,
sondern uberlegen Sie sich, wie Sie den Stack elegant fur diese Aufgabe nutzen konnen.
Hinweis: Da Sie jede Ihrer Eingaben mit Enter abschlieﬂen, wird das Enter-Zeichen mit eingelesen.
Lassen Sie sich etwas einfallen, um dieses Problem zu losen!
Beispiel:
Eingabe: x a x b x c x d x e
Ausgabe: e x d x c x b x a x

# Aufgabe 3 Funktionen

Am vorherigen Ubungstag sollten Sie ein Assembler-Programm schreiben, das eine Zahl vom Benutzer
einliest und pruft ob diese durch drei teilbar ist. Schreiben Sie Ihr Programm so um, dass die Berech-
nung in einer separaten Funktion erfolgt, welche die benotigten Eingabewerte als Ubergabeparameter 
erh®alt und das Ergebnis als Ruckgabewert ubergibt.
Eingaben des Benutzers und Ausgabe an den Benutzer sollen weiterhin in der main erfolgen.

# Aufgabe 4 Stackentwicklung

Skizzieren Sie die Stackentwicklung Ihres Programms aus der vorherigen Aufgabe. Beachten Sie, dass
der Stack in nasm von oben nach unten wachst. Skizzieren Sie den Stack erstmals nach dem Prolog der
main Funktion und anschlieﬂend immer dann, wenn sich der Stack verandert. Wir empfehlen hierzu
eine einfache Textdatei zu verwenden, eine Vorlage finden Sie im ILIAS. Die unten angegebenen
Speicheradressen sind fiktiv. Fuhren Sie diese fort (32-Bit Stack-Breite).
