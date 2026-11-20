# Digiplexx OS Community Skill-Library

Claude-Code-Skills für Projektdokumentation, Community-Beiträge, Skill-Einreichungen und Kurzvideos.

## Installieren

Öffne Claude Code und füge den Marketplace hinzu.

```text
/plugin marketplace add Digiplexx/digiplexx-os-library
```

Installiere anschließend den gewünschten Skill, zum Beispiel:

```text
/plugin install readme-pro@digiplexx-os-library
```

Weitere Skills findest du mit `/plugin`. Falls Claude Code nach der Installation einen Neustart oder ein Neuladen anfordert, folge dem Hinweis.

## Skills

| Plugin | Nutzen | Aufruf |
| --- | --- | --- |
| [readme-pro](plugins/readme-pro/skills/projekt-readme/SKILL.md) | Schreibt ein README aus überprüfbaren Projektinformationen. | `/readme-pro:projekt-readme` |
| [show-and-share](plugins/show-and-share/skills/beitrag/SKILL.md) | Entwirft einen deutschen Show-&-Share-Beitrag für einen Skill oder eine Vorlage. | `/show-and-share:beitrag` |
| [skill-teilen](plugins/skill-teilen/skills/einreichen/SKILL.md) | Bereitet eine Skill-Einreichung für die Digiplexx OS Library vor. | `/skill-teilen:einreichen` |
| [skript-agent](plugins/skript-agent/skills/skript/SKILL.md) | Entwirft Kurzvideos und Social-Posts aus einem Briefing und optionalen Quellen. | `/skript-agent:skript` |

Vorlagen liegen unter [resources/](resources/). Wenn du einen Skill beitragen möchtest, findest du den Ablauf in [CONTRIBUTING.md](CONTRIBUTING.md).

## Herkunft und Lizenz

Der Startkatalog basiert auf der Digiplexx-OS-Projektvorlage. Die vier Skill-Anleitungen wurden für dieses Repository neu verfasst. Der Marketplace verweist auf die Plugin-Verzeichnisse dieses Repositories.

[MIT-Lizenz](LICENSE) · [Sicherheit und Meldungen](SECURITY.md)
