# TUGMD Wordpress in cool

## Bedrock

- [Bedrock](https://roots.io/bedrock/) moderner WordPress-Stack (über 10Mio installationen)
- [Bedrock Dokumentation](https://roots.io/bedrock/docs/)
- Wordpress Boilerplate mit Composer
  - Plugins und Themes können über Composer installiert werden
  - bessere Git Integration
  - Non-Dev Environments können Plugins und Themes nicht per Backend installiert werden
- Easy Configuration mit `.env`-Datei
  - Environment spezifische Konfigurationen
- Verbesserte Ordnerstruktur
- WordPress-Multisite-Unterstützung

## Sage
- [Sage](https://roots.io/sage/) modernes WordPress-Theme
- [Sage Dokumentation](https://roots.io/sage/docs/)
- Theme Boilerplate
- nur das nötigste an Dateien
- nutzt Laravel und Blade als Template-Engine
- Community Packages über Acorn (Framework für Laravel)
- benutzt BUD (Auf Webpack basierendes Build-Tool)
- Out of the box Support für Tailwind

## Gutenberg Blöcke mit ACF

- [ACF](https://www.advancedcustomfields.com/) (Advanced Custom Fields) ist ein Plugin, um benutzerdefinierte Felder zu erstellen
- [Log1x/acf-composer](https://github.com/Log1x/acf-composer) Composer Plugin für ACF
- Ermöglicht das Erstellen von Gutenberg-Blöcken mit ACF über Terminal Commands
- `wp acorn acf:block Example` erstellt einen neuen Block
