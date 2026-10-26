# ferienhaus

Ferienhaus-Planer: Zimmerbelegung und Kostenaufteilung für gemeinsame Ferien.

- App: https://jaaanick.github.io/ferienhaus/ (GitHub Pages, `index.html`)
- Daten: `data/ferien.json` (wird von der App über die GitHub-API geschrieben)

Funktionen:

- Mehrere Ferien mit Anreise/Abreise, Zimmern und Schlafplätzen
- Belegungsplan (Zimmer × Nächte), Personen mit einem oder mehreren Aufenthalten, Warnung bei Überbelegung
- Kosten pauschal, pro Nacht, pro Woche, pro Person & Nacht (z.B. Kurtaxe) , als Staffelpreis pro Nacht (Grundpreis für X Personen, Zuschlag pro weitere Person, Kindertarif) oder pro Hund (pro Nacht oder pauschal, geht an den Hundehalter)
- Aufteilung nach Nächten, gleichmässig, Anwesende am Datum (Einkauf) oder prozentual; Gewichtung pro Person (z.B. Kind ×0,5)
- Abrechnung mit minimaler Anzahl Ausgleichszahlungen (auf 5 Rappen gerundet), bezahlte Ausgleiche erfassen, Zusammenfassung als Text kopieren

Bearbeiten: pro Gerät einmal einen Fine-grained Token mit «Contents: Read and write» für dieses Repo eingeben. Ohne Token ist die Seite nur lesbar (Link kann an Mitreisende gehen).
