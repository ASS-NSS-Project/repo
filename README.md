# repo
Amazing project - TODO change description

## Poetry 101

❗ Knihovny `pyyaml`, `pre-commit` a `conventional-pre-commits` jsou pouze priklady pro pouziti Poetry (v projektu jiz jsou instalovane).

Pokud menim soubor `pyproject.toml`
```bash
poetry lock
poetry install
```

Pridani knihovny `pyyaml` do projektu
```bash
poetry add pyyaml
```

Pridani knihoven `pre-commit` a `conventional-pre-commits` do konkretni groupy `dev`, nikoli globalne pro cely projekt
```bash
poetry add --dev pre-commit conventional-pre-commits
```

Poetry run => spouteni prikazu pomoci poetry (e.g., interpretace `main.py`)
```bash
poetry run python src/backend/main.py
```

Aktivace poetry prostredi
```bash
poetry env activate
```
