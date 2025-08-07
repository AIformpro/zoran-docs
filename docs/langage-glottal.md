# Langage glottal

Le langage glottal est la syntaxe utilisée par le cadre Zoran pour représenter des glyphes triadiques. Chaque glyphe est composé d'une triade de symboles et d'une fonction associée.

## Syntaxe

Un glyphe est représenté sous forme d'objet JSON comprenant une triade et une fonction, par exemple :

```
"ARTNODE": {
  "triad": ["Alpha", "Beta", "Gamma"],
  "function": "Interface de création artistique",
  "description": "Glyphe permettant la création et l'inspiration artistique."
}
```

### Triades

La triade est une liste de trois éléments qui définissent la structure interne d’un glyphe. Ces éléments peuvent faire référence à des concepts mathématiques, philosophiques ou artistiques selon le domaine.

## Utilisation

Pour créer vos propres glyphes, modifiez la triade et la fonction dans le fichier `glottal_grammar.master.json` ou utilisez le script `glyph_forge.py` du dépôt principal.
