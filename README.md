# SWG-TischPool UI Verbesserungen

Dieses Repository enthält Verbesserungen für die SWG-TischPool Anwendung, um sie benutzerfreundlicher und logischer zu gestalten.

## Änderungen

1. **Schriftfarbe in Eingabefeldern**
   - Alle Eingabefelder haben jetzt schwarze Schrift für bessere Lesbarkeit
   - Betrifft Login-Seite, Buchungs-Formulare und alle anderen Eingabefelder

2. **Logout-Button**
   - Ein deutlicherer Logout-Button in der Kopfzeile
   - Zugänglich auch in der mobilen Ansicht

3. **Navigation**
   - Ergänzung um einen Profil-Link für schnellen Zugang zu den Benutzereinstellungen

4. **Dashboard-Verbesserungen**
   - Hilfetext zur besseren Orientierung
   - Übersichtlichere Darstellung der Buchungen und verfügbaren Schreibtische
   - Verbesserte visuelle Hierarchie und Informationsanordnung
   
## Implementierung

Die Änderungen wurden in folgenden Dateien vorgenommen:

- `client/src/app/login/page.tsx`
- `client/src/app/bookings/new/page.tsx`
- `client/src/app/admin/stats/page.tsx`
- `client/src/components/layout/AppLayout.tsx`
- `client/src/app/dashboard/page.tsx`

## Anwendungszweck

Das TischPool-System dient der Verwaltung und Buchung von Arbeitsplätzen im Büro. Die vorgenommenen Änderungen sollen die Benutzerfreundlichkeit verbessern und die Navigation erleichtern.