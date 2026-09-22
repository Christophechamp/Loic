# Carrousel d'entrevue | Loïc St-Martin

Carrousel interactif pour l'entrevue de Loïc St-Martin, Analyste financier chez Sollio Groupe Coopératif.

## Structure

- `index.html` – Carrousel complet, auto-contenu
- `images/` – Photos des 6 diapos (800 × 800 px, avec versions webp + 2x)

## Utilisation

1. Ouvrir `index.html` dans un navigateur
2. Naviguer avec les flèches, les pastilles, ou le clavier (← →)
3. Le carrousel défile automatiquement toutes les 7 secondes

## Pour modifier

- Dupliquer un `<li class="rec-slide">` pour ajouter une diapo
- Les pastilles se génèrent toutes seules
- Noms d'images : `Loic.jpg`, `Loic2.jpg`, `Loic3.jpg`, etc.
- L'`alt` de chaque image décrit la diapo pour l'accessibilité
- Chaque image a des versions webp et 2x pour haute résolution

## Détails techniques

- Aucune dépendance externe
- Responsive (mobile-friendly)
- Accessible (ARIA labels, clavier)
- Défilement natif du navigateur pour performance
- Autoplay 7 secondes + interactions utilisateur
- Format carré 800×800 identique à Andrea
