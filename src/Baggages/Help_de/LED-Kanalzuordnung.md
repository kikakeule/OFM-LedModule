### Kanalzuordnung

Hier wird festgelegt, welcher Dimmkanal auf welchem Hardwarekanal arbeitet.

Vorgehen:

- Zuerst den Typ waehlen:
- EK - Einzelkanal
- TW - Tunable White
- RGB - Rot/Gruen/Blau

- Danach die Nummer des Dimmkanals festlegen. Eine 0 bedeutet, dass der Hardwarekanal deaktiviert bleibt.
- In der letzten Spalte die Rolle des Hardwarekanals innerhalb des gewaehlten Dimmkanals bestimmen.

Beispiel:
- Sollen die Hardwarekanaele A und B gemeinsam ein Tunable-White-Leuchtmittel dimmen, dann erhalten beide den Typ TW und den Dimmkanal 1.
- Fuer ein zweites Tunable-White-Leuchtmittel auf C und D wird derselbe Typ verwendet, aber der Dimmkanal 2.

Hinweis:
- Bei Tunable White sollte eine Farbe auf einem ungeraden und die andere auf einem geraden Hardwarekanal liegen. So werden beide Farben abwechselnd angesteuert und kurzzeitige Stromspitzen vermieden.


