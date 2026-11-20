# Einen Skill einreichen

1. Prüfe den Katalog auf ähnliche Skills. Verbesserungen kannst du direkt als Änderung am bestehenden Skill einreichen.
2. Erstelle einen Fork und einen Branch für deinen Skill. Verwende `plugins/readme-pro/` als Strukturbeispiel.
3. Lege das Plugin-Manifest unter `plugins/<name>/.claude-plugin/plugin.json` und den Skill unter `plugins/<name>/skills/<befehl>/SKILL.md` an. Registriere den relativen Plugin-Pfad in `.claude-plugin/marketplace.json` und ergänze die README-Tabelle.
4. Validiere und probiere den Skill lokal aus. Führe im Wurzelverzeichnis aus:

   ```bash
   claude plugin validate .
   claude plugin validate ./plugins/<name>
   ```

5. Öffne einen Pull Request gegen den Hauptbranch und beschreibe Problem, Beispielaufruf, Testergebnis und gegebenenfalls externe Bestandteile.

Pro Pull Request bitte einen Skill. Schreibe die Beschreibung auf Deutsch. Reiche nur Inhalte ein, die du unter den Bedingungen dieses Projekts veröffentlichen darfst. Dokumentiere zulässige externe Bestandteile mit Quelle, Lizenz und erforderlichen Hinweisen. Prüfe vor dem Push, dass du keine Zugangsdaten oder persönlichen Projektinformationen mitlieferst.

Wenn du Unterstützung möchtest, installiere `skill-teilen@digiplexx-os-library` über den Plugin-Marketplace und rufe `/skill-teilen:einreichen` auf. Claude kann den Pull Request mit deiner Freigabe vorbereiten und einreichen.
