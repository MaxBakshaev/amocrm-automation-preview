# Исходники схем

Схемы в README и в `docs/` — картинки, отрисованные из этих файлов Mermaid. Чтобы поправить схему, отредактируйте `.mmd` и пересоберите PNG, например через mermaid-cli:

```bash
npx -p @mermaid-js/mermaid-cli mmdc -i who.mmd -o ../img/diagrams/who.png -s 2 -b white
```
