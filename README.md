# Vallier & Fils — site de démonstration

Plombier-chauffagiste fictif à Béziers, spécialisé en rénovation de salle de bain.
Deuxième exemple de la verticale **Artisan** de LocWeb.

Construit selon `template-nouveau-client/PROMPT-ARTISAN.md`.

## L'angle

Rapid'Eau tient l'**urgence** (bouton orange, « on arrive en 30 minutes »).
Celui-ci tient le **travail planifié** : bouton bleu calme, titres en serif,
promesse de date de fin contractuelle. Même socle, registre différent.

## Ce qui est en place

- Responsive, testé de 375 px au desktop
- Hero à trois plans enchaînés en fondu, avec lent recadrage
- Contrastes AA vérifiés par mesure
- Focus clavier visible sur tous les éléments interactifs
- `robots.txt`, `sitemap.xml`, canonical, schema.org `Plumber` avec catalogue
- Images en WebP, deux tailles, dimensions déclarées (aucun décalage au chargement)
- Zones `data-editable-zone` préfixées `vallier_` pour éviter toute collision
  de clés avec les autres sites du parc
- Sans JavaScript : la première image du hero reste et la page est complète

## Reste à faire

- Pages prestation (`/renovation-salle-de-bain`, `/plomberie`, `/chauffage`) —
  le prompt Artisan impose le multi-pages pour le référencement local
- Page mentions légales
- Branchement Supabase : `contenu-loader.js`, `leads-form.js`, manifeste

> Les photos viennent d'Unsplash. Les avis et le SIRET sont fictifs — c'est une
> démonstration, pas un site client.
