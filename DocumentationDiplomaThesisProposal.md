
## Ausgangslage

Viele Restaurants und Lieferdienste koordinieren ihre Bestellungen derzeit manuell oder mit unflexiblen Systemen. Dies
führt zu unklaren Abholzeiten, mangelnder Transparenz und langen Wartezeiten für den Kunden, als auch für das Personal in den Betrieben und dem Lieferanten. Besonders in Stoßzeiten kommt es dadurch zu organisatorischen Engpässen.

## Untersuchungsanliegen der individuellen Themenstellungen

### Markus

- Prüfen, wie eine native iOS-App mit Swift sinnvoll zur Darstellung und Bearbeitung fahrerbezogener Aufträge genutzt werden kann.
- Untersuchen, wie die Synchronisation zwischen mobiler App und zentraler Datenbank (z. B. Abholzeiten, Statusmeldungen) zuverlässig und latenzarm umgesetzt werden kann.
- Evaluieren, wie GPS-Daten der Fahrer datenschutzkonform erfasst, verarbeitet und visualisiert werden können.
- Analysieren, wie die Datenbankstruktur aufgebaut sein muss, um skalierbar und gleichzeitig performant große Mengen an Bestellungen und Fahrerinformationen zu verwalten.

### Steven

- Untersuchen, wie Bestelldaten aus Drittquellen automatisiert ins System übernommen und mit vorhandenen Aufträgen abgeglichen werden können.
- Analysieren, welche Algorithmen zur dynamischen Berechnung optimaler Abholzeiten auf Basis verfügbarer Fahrerdaten geeignet sind.
- Evaluieren, wie in der Web-App eine verständliche, übersichtliche Darstellung aller Aufträge und Fahrerstandorte realisiert werden kann.
- Prüfen, welche Sicherheitsmechanismen im Backend notwendig sind, um DSGVO-konforme Datenverarbeitung (v. a. bei Standort- und Kundeninformationen) zu gewährleisten.


## Zielsetzung

Ziel ist die Entwicklung einer Dispositionsplattform zur automatisierten Koordination von Bestellungen und Fahrern in der Gastronomie-Logistik. Durch optimierte Abholzeitberechnung, mobile Anbindung und zentrale Übersicht sollen Wartezeiten reduziert, Abläufe effizienter gestaltet und die Kundenzufriedenheit gesteigert werden.

## Geplantes Ergebnis der individuellen Themenstellungen

### Markus

- Eine native iOS-App zur Anzeige und Bearbeitung von Fahreraufträgen inkl. Tourverlauf.
- Eine zentral angebundene Datenbankstruktur für mobile Statusupdates und GPS-Daten.
- Datenschutzkonforme Integration von GPS-Tracking zur Tourdokumentation.

### Steven

- Eine Web-App zur Visualisierung und Verwaltung aller Bestellungen und Fahrer.
- Backend-Logik zur automatisierten Abholzeitberechnung auf Basis von Fahrerdaten.
- Schnittstelle zum Import externer Bestelldaten (z. B. POS-Systeme).

## Meilensteine

### Markus

- Die Datenbankstruktur zur Verwaltung von Fahrer- und Auftragsdaten ist erstellt und funktionsfähig. (15.07.2025)
- Die mobile App kann Bestellungen anzeigen und mit der zentralen Datenbank synchronisieren. (29.07.2025)
- GPS-Daten werden datenschutzkonform erfasst und in der Datenbank gespeichert. (12.08.2025)
- Die App stellt geplante Abhol- und Lieferzeiten samt Tourverlauf dar. (26.08.2025)
- Fahrer können Statusänderungen (z. B. „Abgeholt“, „Zugestellt“) mobil dokumentieren. (09.09.2025)
- Die App funktioniert stabil auf aktuellen iOS-Geräten und wurde erfolgreich getestet. (23.09.2025)
- Die Kommunikation zwischen App und Server ist verschlüsselt und stabil. (07.10.2025)

### Steven

- Die Web-App zeigt alle offenen und laufenden Bestellungen übersichtlich an. (15.07.2025)
- Die Schnittstelle zum Import externer Bestellungen (z. B. POS-System) ist implementiert. (29.07.2025)
- Die automatische Berechnung optimaler Abholzeiten wurde erfolgreich umgesetzt. (12.08.2025)
- Eine Live-Kartenansicht zur Anzeige der Fahrerpositionen wurde integriert. (26.08.2025)
- Das Backend verarbeitet Statusmeldungen der Fahrer korrekt und in Echtzeit. (09.09.2025)
- Die Benutzeroberfläche für Disponenten wurde auf Usability getestet und angepasst. (23.09.2025)
- Das Gesamtsystem wurde unter realistischen Bedingungen getestet und optimiert. (07.10.2025)

## Individuelle Themenstellungen der Kandidatin/des Kandidaten

### Markus Schoder

**Individuelle Themenstellung:** Siehe „Untersuchungsanliegen der individuellen Themenstellungen“  
**Arbeitsaufwand:** 180 Stunden  

### Steven Ou

**Individuelle Themenstellung:** Siehe „Untersuchungsanliegen der individuellen Themenstellungen“  
**Arbeitsaufwand:** 180 Stunden  