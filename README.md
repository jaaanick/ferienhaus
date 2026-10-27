# ferienhaus

Ferienhaus-Planer: Zimmerbelegung und Kostenaufteilung für gemeinsame Ferien.

- App: https://jaaanick.github.io/ferienhaus/ (GitHub Pages, `index.html`)
- Jede Ferien hat einen eigenen geheimen Link: `https://jaaanick.github.io/ferienhaus/<Code>`
- Daten: `data/t/<id>.json`, pro Ferien eine Datei, verschlüsselt (AES-256-GCM). Dateiname und Schlüssel werden aus dem Code abgeleitet; ohne Link ist nichts lesbar oder zuzuordnen. `404.html` leitet `/ferienhaus/<Code>` an die App weiter.

Funktionen:

- Mehrere Ferien mit Anreise/Abreise, Zimmern und Schlafplätzen
- Belegungsplan (Zimmer × Nächte), Personen mit einem oder mehreren Aufenthalten, Warnung bei Überbelegung
- Kosten pauschal, pro Nacht, pro Woche, pro Person & Nacht (z.B. Kurtaxe)  oder als Staffelpreis pro Nacht (Grundpreis für X Personen, Zuschlag pro weitere Person)
- Zuschläge pro Ferien (Kind pro Nacht, Hund pro Nacht, Hund pauschal) werden automatisch der Person belastet, die Kinder bzw. Hunde dabei hat (Anzahl bei der Person)
- Aufteilung nach Nächten, gleichmässig, Anwesende am Datum (Einkauf) oder prozentual; Gewichtung pro Person (z.B. Kind ×0,5)
- Abrechnung mit minimaler Anzahl Ausgleichszahlungen (auf 5 Rappen gerundet), bezahlte Ausgleiche erfassen, Zusammenfassung als Text kopieren

Bearbeiten: pro Gerät einmal einen Fine-grained Token mit «Contents: Read and write» für dieses Repo eingeben. Ohne Token ist die Seite nur lesbar (Link kann an Mitreisende gehen).
