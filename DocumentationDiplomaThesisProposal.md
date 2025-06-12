# Leitfaden _Diplomarbeits-DB_

## Ausgangslage

Viele Restaurants und Lieferdienste koordinieren ihre Bestellungen derzeit manuell oder mit unflexiblen Sysmten. Dies
führt zu unklaren Abholzeiten, mangelnder Transparenz und langen Wartenzeiten für den Kunden, als auch für das Personal in den Betrieben und die Lieferfahrer. Besonders in Stoßzeiten kommt es dadurch zu organisatorischen Engpässen.

## Untersuchungsanliegen der individuellen Themenstellungen

### Markus (iOS-App & Datenbank)

- Prüfen, wie eine native iOS-App mit Swift sinnvoll zur Darstellung und Bearbeitung fahrerbezogener Aufträge genutzt werden kann.
- Untersuchen, wie die Synchronisation zwischen mobiler App und zentraler Datenbank (z. B. Abholzeiten, Statusmeldungen) zuverlässig und latenzarm umgesetzt werden kann.
- Evaluieren, wie GPS-Daten der Fahrer datenschutzkonform erfasst, verarbeitet und visualisiert werden können.
- Analysieren, wie die Datenbankstruktur aufgebaut sein muss, um skalierbar und gleichzeitig performant große Mengen an Bestellungen und Fahrerinformationen zu verwalten.

### Steven (Web-App & C# Backend)

- Untersuchen, wie Bestelldaten aus Drittquellen automatisiert ins System übernommen und mit vorhandenen Aufträgen abgeglichen werden können.
- Analysieren, welche Algorithmen zur dynamischen Berechnung optimaler Abholzeiten auf Basis verfügbarer Fahrerdaten geeignet sind.
- Evaluieren, wie in der Web-App eine verständliche, übersichtliche Darstellung aller Aufträge und Fahrerstandorte realisiert werden kann.
- Prüfen, welche Sicherheitsmechanismen im Backend notwendig sind, um DSGVO-konforme Datenverarbeitung (v. a. bei Standort- und Kundeninformationen) zu gewährleisten.


## Zielsetzung

Ziel ist die Entwicklung einer Dispositionsplattform zur automatisierten Koordination von Bestellungen und Fahrern in der Gastronomie-Logistik. Durch optimierte Abholzeitberechnung, mobile Anbindung und zentrale Übersicht sollen Wartezeiten reduziert, Abläufe effizienter gestaltet und die Kundenzufriedenheit gesteigert werden.

## Geplantes Ergebnis der individuellen Themenstellungen

(Maximal 400 Zeichen.)

Aus _Leowiki_:

> Hier die jeweiligen Ergebnisse der einzelnen KandidatInnen auflisten. Dabei können die Ergebnisse durchaus von den Untersuchungsanliegen abgeleitet werden. Beispielsweise wird aus „Untersuchen, wie ein benutzerfreundliches UI…“ sicherlich das Ergebnis „Ein benutzerfreundliches UI …“ abgeleitet werden können. Dies ist aber nicht zwingend bei jedem Ergebnis der Fall.

> Zusätzlich muss hier noch eine Kostenschätzung (nicht aufgeschlüsselt, sondern nur die Gesamtsumme und die wichtigsten ein bis zwei Kostenpunkte) dokumentiert werden. Wording: Maximale Kosten: xxxxx € für Raspberry Pi 4. Bei keinen zu erwartenden Kosten ist „Keine zu erwartenden Kosten“ zu dokumentieren.

Wie beschrieben, ist das Umformulieren der Untersuchungsanliegen eine billige Strategie - beachtet aber das Zeichenlimit (400 statt 800!). Auch hier gilt der Punkt bzgl. dem Aufteilen von gleichen Themen durch cleveres Formulieren.

Beispiel:

> Fr. Musterfrau:

> Eine GUI über die die Abfrage der Messdaten konfiguriert und durchgeführt werden kann.

> Eine Vorverarbeitungs-Pipeline in Python mit der die Messdaten für das Trainieren eines Modells und die Vorhersage vorbereitet werden.

> Eine ausführliche Evaluierung des trainierten Modells mit sinnvollen Metriken und realistischen Daten.

> Hr. Kowalski:

> Modellierung einer Datenbank zur Speicherung der Messdaten.

> Experimenteller Einsatz verschiedener ML-Algorithmen in einem Jupyter Notebook und abschließende Bereitstellung als Web Service.

> Implementierung eines konfigurierbaren Benachrichtigungs-Systems, das Verantwortliche bzw. Abteilungen über bevorstehende Wartungen informiert.

## Meilensteine

Aus _Leowiki_:

> 1. Die Meilensteine sollen sich auf das Projekt beziehen und nicht auf die Dokumentation (aka schriftliche Arbeit).
> 2. Es sollen mindestens 5 bis 7 Milestones und das jeweils zugehörige Datum angegeben werden.
> 3. Milestones sind in Form einer Aussage formuliert, deren Gültigkeit man überprüfen kann. Bsp: "Die Datenschnittstelle in Richtung Anlagensteuerung ist implementiert und getestet" (gut). "Implementieren der Datenschnittstelle" (schlecht!)
> 4. Die Abgabe der Diplomarbeit zum Abgabetermin ist kein Meilenstein, der in der Datenbank dokumentiert werden darf.
> 5. Die KandidatInnen sollen sich in diesem Punkt schon soweit mit dem Thema auseinandergesetzt haben, dass sie sinnvolle Angaben zum Projekt machen können.

Beachtet hier, dass ein Datum angegeben werden muss, obwohl auf der Plattform _Der Abgabetermin muss nicht angeführt werden._ steht. Ansonsten sollen wie gesagt _nur projektrelevante_ Meilensteine eingetragen werden, _keine_ Angaben zur Diplomarbeit wie z.B. _Kapitel 3 fertig_.

Beispiel:

> 1. Die Messdaten können über die GUI abgefragt und in einer Datenbank gespeichert werden.
> 2. Die Daten wurden vorverarbeitet und ein erstes Modell wurde trainiert.
> 3. Ein Web-Service wurde vorbereitet, mit dem ein Modell für Vorhersagen genutzt werden kann.
> 4. Das Modell wurde umfangreich evaluiert und durch Anpassung der Hyperparameter und Vorverarbeitung optimiert.
> 5. Ein Benachrichtigungs-System wurde implementiert und getestet.

# Individuelle Themenstellungen der Kandidatin/des Kandidaten

Hier müssen die ProjektmitarbeiterInnen eingetragen werden. Bei _Individuelle Themenstellung_ kann man ganz pragmatisch _Siehe "Untersuchungsanliegen der individuellen Themenstellungen"._ hinschreiben. Bei _Arbeitsaufwand_ ist 180 Stunden ein guter Richtwert.

# Mögliche Kooperationspartner/innen bzw. Auftraggeber/innen

Der Punkt ist recht klein und wird leicht übersehen - hier gehören die Daten der Partnerfirma inkl. einer Ansprechpartnerin/eines Ansprechpartners hin.

## Rechtliche Regelung

Ich lasse hier folgenden Standard-Text verwenden - sollte in den meisten Fällen für euch ebenfalls zutreffend sein:

> Es wurde mündlich vereinbart, dass sowohl Code als auch Ergebnisse den ProfessorInnen demonstriert werden dürfen. Sämtliche potentiell firmenkritischen Daten und Bilder werden bei der Einbindung in die Diplomarbeit entsprechend unkenntlich gemacht.

Sollte eure Partnerfirma nach einer _Sperre_ der Diplomarbeit fragen, könnt ihr folgende Informationen aus dem _Leowiki_ kommunizieren:

> Physische Diplomarbeiten (das ausgedruckte Werk) sind bei uns nicht öffentlich zugänglich. Die DA-Betreuer*innen müssen natürlich das Recht haben, die Arbeit zu lesen und auch den Source-Code einzusehen. Im Rahmen der Reife- und Diplomprüfung liegt bei der Präsentation und Diskussion der DA die schriftliche Arbeit (nicht der Source Code) als Tischexemplar auf und kommt anschließend bei uns an der Schule ins Archiv, welches nur über den Abteilungsvorstand oder den Schulleiter zugänglich ist.