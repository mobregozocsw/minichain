# minichain

Smallest possible tool-use agent I could write

## Getting started

```bash
pip install -r requirements.txt
export OPENAI_API_KEY=sk-...
```

## Highlights

- Works with any OpenAI-compatible model
- Tool schemas declared next to the functions
- Three tools: calculator, word count, note lookup
- Plain loop: plan -> call -> observe -> answer

## How to use

```bash
python agent.py "how many words in my note called todo?"
```

## Project structure

```text
├── .github/
│   └── workflows/
│       └── ci.yml
├── docs/
│   ├── configuration.md
│   ├── development.md
│   └── usage.md
├── examples/
│   └── quickstart.md
├── .gitignore
├── CHANGELOG.md
├── CONTRIBUTING.md
├── SECURITY.md
├── agent.py
└── requirements.txt
```

## Development

```bash
python -m venv .venv && source .venv/bin/activate
pip install -r requirements.txt
```

## Why

Needed this for myself; figured others might too.
