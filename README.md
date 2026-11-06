# Maison Infini – Homepage (3 pistes créatives)

Site statique, sans JavaScript, sans police web, images WebP légères uniquement : léger, éco-conçu et accessible (RGAA).

| Fichier | Piste | Ambiance |
|---|---|---|
| `piste-a.html` + `theme-a.css` | A · L'Atelier | Beige nude, lumière chaude, serif élégant (moodboard 1 : boutique, packaging) |
| `piste-b.html` + `theme-b.css` | B · Sans début ni fin | Brun nuit et or, ambiance écrin (moodboard 1 : visuels sombres) |
| `piste-c.html` + `theme-c.css` | C · L'étincelle | Éditorial, blanc cassé, gris-bleu et or, typographie affirmée (moodboard 2 : palette) |

**`index.html` + `home.css` : homepage boutique avec photos et logo (dossier `img/`).**

`base.css` est partagé par les trois pistes. `accessibilite.html` est la déclaration d'accessibilité.

## Mise en ligne sur GitHub Pages

1. Créez un dépôt GitHub (ex. `maison-infini`) et déposez tous les fichiers à la racine.
2. *Settings → Pages → Build and deployment* : source « Deploy from a branch », branche `main`, dossier `/ (root)`.
3. Le site est disponible à `https://<votre-compte>.github.io/maison-infini/`.

## À compléter avant diffusion

- Remplacer `contact@maison-infini.example` (index, pistes B et C, accessibilité) par la vraie adresse.
- Ajouter adresse, horaires, mentions légales.
- Faire valider les prix et les textes.

## Éco-conception

- 0 requête externe, 0 JavaScript, polices système uniquement, 8 images WebP (environ 105 Ko), dimensions renseignées, chargement différé sous la ligne de flottaison.
- Les photos viennent du moodboard du dossier (recadrées, petites). Pour des photos plus nettes : WebP/AVIF, `loading="lazy"`, `width`/`height`, texte alternatif pertinent.

## Accessibilité (RGAA)

Langue déclarée, lien d'évitement, repères ARIA, hiérarchie de titres, contrastes AA, focus visible, `prefers-reduced-motion`, textes en rem, tableau avec légende. Un audit RGAA complet (outils comme Asqatasun ou Accessibility Insights, test clavier et lecteur d'écran) reste nécessaire pour attester la conformité.
