# Haushaltsbudget

Eine responsive, barrierearme Haushaltsbudget-App ohne Bibliotheken oder Frameworks. Die Anwendung läuft vollständig im Browser und wird direkt über `index.html` gestartet.

## Nutzung

1. `index.html` doppelt anklicken oder in einem Browser öffnen.
2. Unter **Neue Ausgabe** eine Bezeichnung, einen Betrag, eine Kategorie und ein Datum eingeben.
3. Die Ausgaben über die Suche oder den Kategorie-Filter einschränken.
4. In **Budget nach Kategorie** prüfen, welche Monatslimits noch verfügbar sind. Überschreitungen werden rot markiert und zusätzlich als Statusmeldung ausgegeben.
5. Einträge können über das ×-Symbol wieder gelöscht werden.

Die Beispieldaten liegen als Array von Objekten direkt im JavaScript. Es sind neun realistische Einträge enthalten. Es werden keine externen APIs, Abhängigkeiten oder Build-Schritte benötigt.

## KI-Nutzung

Für die Umsetzung wurde GitHub Copilot (Auto-Modus) verwendet. Das Tool half beim Strukturieren der Single-Page-App, beim Formulieren der deutschen UI-Texte, bei der Umsetzung der Budgetberechnung sowie bei der Prüfung von Validierung, Filterung und responsivem Layout.
