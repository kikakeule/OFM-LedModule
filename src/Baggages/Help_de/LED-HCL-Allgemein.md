# LED HCL Allgemein

Diese Einstellungen koppeln einen LED-Kanal an eine externe HCL-Fuehrung, zum Beispiel aus einem HclModule.

- HCL aktivieren: Schaltet die HCL-Kopplung fuer diesen Kanal frei.
- HCL-Eingaenge: Legen fest, welche HCL-Informationen der Kanal von aussen uebernimmt. Je nach Kanal stehen getrennte oder kombinierte Vorgaben zur Verfuegung.
- HCL aktiv setzen bei: Aktiviert den lokalen HCL-Modus automatisch nach Reset und/oder Busspannungswiederkehr.
- HCL KO Lesen bei: Liest die konfigurierten HCL-Werte nach Reset oder Busspannungswiederkehr erneut ein.
- Lokale Eingaenge im HCL-Modus: Legen fest, wie lokale Bedienung und externe HCL-Fuehrung zusammenwirken.
- Rueckkehr nach lokalem Override: Bestimmt, wann nach einer manuellen Uebersteuerung wieder auf HCL gewechselt wird.
- Einschaltverhalten, Verhalten bei zweitem EIN und Verhalten bei HCL-Start: Regeln das Verhalten des Kanals beim Aktivieren oder erneuten Uebernehmen der HCL-Fuehrung.

Praxis:
- Das HclModule liefert die Vorgaben, der LED-Kanal setzt sie lokal um.
- Mit den Rueckkehr- und Override-Einstellungen wird festgelegt, wie stark lokale Bedienung HCL temporaer uebersteuern darf.
- Beim TW-Kanal gibt es zusaetzlich einen kombinierten Eingang fuer Dimmwert und Farbtemperatur ausserhalb der HCL-Kopplung.