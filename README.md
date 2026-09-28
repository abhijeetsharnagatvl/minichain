# minichain

Minimal tool-calling agent loop, framework-free

Built for my own use; public in case it helps someone.

## Install

```bash
pip install -r requirements.txt
export OPENAI_API_KEY=sk-...
```

## Highlights

- Tool schemas declared next to the functions
- Plain loop: plan -> call -> observe -> answer
- Three tools: calculator, word count, note lookup
- Works with any OpenAI-compatible model

## Usage

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
│   ├── faq.md
│   └── usage.md
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
