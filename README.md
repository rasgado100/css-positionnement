# Positionnement CSS : toutes les méthodes, de `float` à Grid

Le code qui accompagne l'article **« Le positionnement en CSS : toutes les méthodes, de float à Grid »** : [lien vers l'article](https://blog.cyrillerasgado.com/blog/comment-positionner-un-element-en-css).

Une démo par méthode de positionnement, en HTML et CSS pur. Pas de framework, pas d'installation, pas de JavaScript.

## Lancer le projet

1. Clone le repo :
   ```bash
   git clone https://github.com/rasgado100/css-positionnement.git
   cd css-positionnement
   ```
2. Ouvre `index.html` dans ton navigateur. C'est tout.

Si tu préfères un petit serveur local : `npx serve .`

## Ce qu'il y a dedans

| Dossier | Ce que tu y trouves |
| --- | --- |
| `01-flux-normal` | `block`, `inline`, `inline-block`, `margin: 0 auto` |
| `02-float` | Image entourée de texte, et le piège du parent qui s'effondre |
| `03-relative-absolute` | Le badge sur une carte, et le bug classique quand on oublie `relative` |
| `04-fixed` | Un bouton « retour en haut » collé à la fenêtre |
| `05-sticky` | Un header et un sommaire qui restent visibles au scroll |
| `06-z-index` | L'empilement, et le piège du contexte d'empilement |
| `07-flexbox` | Navbar, centrage, colonnes, `flex-wrap` |
| `08-grid` | Colonnes, grille responsive, `span`, centrage |
| `09-modale` | Mini-projet 1 : une modale en CSS pur (`fixed` + `absolute` + `transform`) |
| `10-page-complete` | Mini-projet 2 : une page complète (Grid + Flexbox + `sticky` + badge) |

Les styles communs (couleurs, boîtes) sont dans `assets/base.css`. Chaque démo a son propre `style.css`, commenté pour que tu repères l'essentiel.

## Comment t'en servir

- Ouvre une démo avec l'article à côté.
- Casse le code : change une valeur, supprime une ligne (par exemple le `position: relative` de la carte) et regarde ce qui se passe.
- Les commentaires dans les fichiers CSS indiquent les endroits où il y a un piège.

## Licence

MIT : fais-en ce que tu veux.

Une question, une idée d'amélioration ? écris-moi.
