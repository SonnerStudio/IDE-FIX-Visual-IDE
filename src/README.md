# IDE-FIX Visual IDE - Source Code Structure

This directory contains the complete source code for IDE-FIX Visual IDE.

## Directory Structure

```
src/
├── main.tsx                    # React Entry Point
├── App.tsx                     # Root Component
├── App.css                     # App styles
│
├── workbench/                  # VS Code Workbench-inspired layout
│   ├── ActivityBar.tsx         # Left sidebar with icons
│   ├── Sidebar.tsx             # Collapsible sidebar container
│   ├── Panel.tsx               # Bottom panel container
│   ├── Explorer/               # File explorer
│   ├── Search/                 # Search functionality
│   └── Terminal/               # Integrated terminal
│
├── editor/                     # Monaco Editor Integration
│   ├── MonacoEditor.tsx        # Monaco wrapper component
│   ├── EditorService.ts        # Editor state management
│   └── LanguageFeatures.ts    # Code features (go-to-def, etc.)
│
├── visual/                     # Visual Canvas Editor
│   ├── Canvas/                 # Custom canvas rendering
│   ├── Components/             # Visual component nodes
│   └── LogicEditor/            # Visual logic blocks
│
├── services/                   # Core Services
│   ├── language/               # LSP Integration
│   ├── filesystem/             # File operations
│   ├── git/                    # Git integration
│   └── extensions/             # Extension system
│
├── components/                 # Shared UI Components
│   ├── MagicHat/               # Magic hat component system 🎩
│   ├── FixMascot/              # Fix mascot (AI assistant) 🐾
│   ├── PropertyPanel/          # Component properties editor
│   ├── LogicEditor/            # Visual logic editor
│   └── Preview/                # Live preview component
│
├── core/                       # Core Logic
│   ├── CodeGen/                # Code generation
│   ├── SyncManager/            # Visual-code synchronization
│   └── Project/                # Project management
│
├── styles/                     # Global Styles & Themes
│   ├── theme.css               # Theme variables
│   ├── animations.css          # Animation library
│   └── glassmorphism.css       # Glassmorphism effects
│
├── debug/                      # Debugging System
│   └── (DAP implementation)
│
├── git/                        # Git Integration
│   └── (Git service implementation)
│
└── libraries/                  # Component Libraries
    └── react/                  # React component library
```

## Getting Started

See the main [README.md](../README.md) for setup instructions.

## Development Phases

This structure follows the 20-phase development plan outlined in [docs/entwicklungsplan.md](../docs/entwicklungsplan.md).
