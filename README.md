# Repo
Níže jsou jakési konvence, které by bylo vhodné dodržovat.

## Git Commit Message Generator
[link](https://utilityfordev.com/git-commit-generator)

## Poetry 101

❗ Knihovny `pyyaml`, `pre-commit` a `conventional-pre-commits` jsou pouze příklady pro použití Poetry (v projektu již jsou instalované).

Pokud měním obsah souboru `pyproject.toml` (dependency tracker), používám následující dva příkazy:
```bash
poetry lock
poetry install
```

Přidaní knihovny `pyyaml` do projektu:
```bash
poetry add pyyaml
```

Přidání knihoven `pre-commit` a `conventional-pre-commits` do konkretní projektové groupy `dev`, nikoli globalně pro celý projekt:
```bash
poetry add --dev pre-commit conventional-pre-commits
```

Poetry run => spouštění příkazů pomocí Poetry (e.g., interpretace `main.py`):
```bash
poetry run python src/backend/main.py
```

Aktivace Poetry prostředí:
```bash
poetry env activate
```
