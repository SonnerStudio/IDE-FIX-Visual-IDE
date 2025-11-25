# Contributing to IDE-FIX Visual IDE

Vielen Dank für dein Interesse, zu IDE-FIX beizutragen! 🎩✨

Wir freuen uns über jede Art von Beitrag, sei es Code, Dokumentation, Design oder Testing.

## 🌟 Code of Conduct

Dieses Projekt folgt einem Code of Conduct. Durch deine Teilnahme erklärst du dich damit einverstanden, respektvoll und konstruktiv zu kommunizieren.

## 🚀 Wie kann ich beitragen?

### Bug Reports 🐛

Wenn du einen Fehler findest:
1. Prüfe, ob der Bug bereits in den [Issues](https://github.com/SonnerStudio/IDE-FIX-Visual-IDE/issues) gemeldet wurde
2. Wenn nicht, erstelle ein neues Issue mit:
   - Beschreibung des Problems
   - Schritte zur Reproduktion
   - Erwartetes vs. tatsächliches Verhalten
   - Screenshots (wenn hilfreich)
   - System-Info (OS, Node-Version, etc.)

### Feature Requests 💡

Hast du eine Idee für ein neues Feature?
1. Prüfe [Discussions](https://github.com/SonnerStudio/IDE-FIX-Visual-IDE/discussions) und Issues
2. Erstelle ein Issue mit:
   - Klare Beschreibung des Features
   - Use Case / Problem das es löst
   - Mögliche Implementierung (optional)

### Code Contributions 🔧

#### Setup Development Environment

```bash
# Repository forken und klonen
git clone https://github.com/DEIN-USERNAME/IDE-FIX-Visual-IDE.git
cd IDE-FIX-Visual-IDE

# Dependencies installieren
npm install

# Development Server starten
npm run dev

# Tests ausführen
npm test
```

#### Pull Request Prozess

1. **Fork** das Repository
2. **Erstelle einen Branch** für dein Feature: `git checkout -b feature/amazing-feature`
3. **Committe deine Änderungen** mit aussagekräftigen Commit-Messages
4. **Push** zu deinem Fork: `git push origin feature/amazing-feature`
5. **Öffne einen Pull Request** gegen den `main` Branch

#### Commit Guidelines

Wir verwenden [Conventional Commits](https://www.conventionalcommits.org/):

```
feat: Add magic particle effect to hat animation
fix: Resolve Monaco editor crash on Mojo files
docs: Update installation instructions
style: Format code with Prettier
refactor: Extract LSP client to separate service
test: Add unit tests for CodeGenerator
chore: Update dependencies
```

#### Code Style

- **TypeScript**: Verwende TypeScript strict mode
- **ESLint**: Code muss ohne Errors/Warnings laufen
- **Prettier**: Code wird automatisch formatiert
- **Kommentare**: Erkläre komplexe Logik

### Documentation 📖

Verbessere die Dokumentation:
- README.md Updates
- Code-Kommentare
- Tutorial-Erstellung
- API-Dokumentation

### Testing 🧪

- Schreibe Unit-Tests für neue Features
- Bestehende Tests müssen bestehen
- E2E-Tests für kritische User-Flows

## 📋 Development Guidelines

### Projekt-Struktur

```
src/
├── workbench/      # VS Code-ähnliche Workbench
├── editor/         # Monaco Editor Integration
├── visual/         # Custom Canvas Editor
├── services/       # Core Services (LSP, Git, etc.)
├── components/     # Shared React Components
└── styles/         # Themes & Styles
```

### Wichtige Konzepte

1. **Separation of Concerns**: UI-Logik getrennt von Business-Logik
2. **Type Safety**: Nutze TypeScript-Typen konsequent
3. **Performance**: Canvas-Rendering muss 60 FPS halten
4. **Accessibility**: ARIA-Labels, Keyboard-Navigation

### Testing-Strategie

- **Unit Tests**: Jest für Services und Utils
- **Component Tests**: React Testing Library
- **E2E Tests**: Playwright
- **Visual Tests**: Storybook

## 🎨 Design Contributions

Interessiert an UI/UX-Verbesserungen?
- Teile deine Designs in Discussions
- Erstelle Mockups (Figma, Sketch, etc.)
- Folge der magischen Design-Language

## 🐾 Fix Mascot Guidelines

Wenn du an Fix-Features arbeitest:
- Halte den Charakter konsistent (freundlich, hilfsbereit)
- Animationen sollten smooth sein (60 FPS)
- Texte sollten klar und ermunternd sein

## ❓ Fragen?

- **GitHub Discussions**: Für allgemeine Fragen
- **Issues**: Für spezifische Probleme
- **Discord** (coming soon)

## 🏆 Contributors

Alle Contributors werden in der README.md erwähnt!

## 📄 Lizenz

Durch deinen Beitrag stimmst du zu, dass dein Code unter der MIT License veröffentlicht wird.

---

**Danke, dass du IDE-FIX besser machst! 🎩✨**
