# sortie-kit

Small Go tool: declutter ~/Downloads in one command

## Install

```bash
go build -o bin/ ./...
```

## Highlights

- Single static binary, no runtime deps
- Groups files into folders by extension
- Dry-run prints the plan before moving anything
- Skips hidden files and folders by default

## Usage

```bash
./bin/sortie-kit ~/Downloads --dry-run
./bin/sortie-kit ~/Downloads
```

## Project structure

```text
├── .github/
│   └── workflows/
│       └── ci.yml
├── docs/
│   ├── configuration.md
│   ├── faq.md
│   └── roadmap.md
├── examples/
│   └── quickstart.md
├── .editorconfig
├── .gitignore
├── CHANGELOG.md
├── CONTRIBUTING.md
├── SECURITY.md
├── go.mod
└── main.go
```

## Development

```bash
go build ./...
go vet ./...
```
