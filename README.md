# Site personnel de Serge Garcia — package prêt à publier

## Solution retenue

**Quarto + GitHub Pages + nom de domaine personnel**.

Pourquoi : Quarto est gratuit, très adapté aux chercheurs, permet d'écrire en Markdown sans développer un site à la main et génère un site statique rapide, sécurisé et durable. GitHub Pages héberge gratuitement le site. Un nom de domaine du type `sergegarcia.fr` ou `serge-garcia.fr` peut ensuite être relié au site.

## Ce que contient ce package

- `_quarto.yml` : configuration générale et menu.
- `styles.css` : design du site.
- `index.qmd` : page d'accueil.
- `recherche.qmd` : axes de recherche.
- `projets.qmd` : projets, responsabilités et expertise.
- `publications.qmd` : sélection de publications.
- `enseignement.qmd` : enseignements et encadrement.
- `cv.qmd` : CV synthétique + lien vers le CV PDF.
- `preview/index.html` : maquette HTML ouvrable immédiatement, sans installer Quarto.

## Logiciels à installer sur Windows

### Option recommandée : Positron + Quarto
1. Installer Quarto : https://quarto.org/docs/get-started/
2. Installer Positron (éditeur gratuit de Posit) ou utiliser RStudio si déjà installé.
3. Ouvrir le dossier du site.
4. Dans un terminal : `quarto preview`
5. Modifier les fichiers `.qmd`; le navigateur se met à jour.

### Publication

Le chemin le plus propre est GitHub Pages. Après création d'un compte GitHub et d'un dépôt, publier avec :

`quarto publish gh-pages`

Quarto peut aussi publier vers Netlify ou Quarto Pub.

## Nom de domaine

Je recommande un domaine court et neutre :

- `sergegarcia.fr`
- `serge-garcia.fr`
- éventuellement `sergegarcia-economics.fr`

Le domaine est acheté chez un registrar (OVHcloud, Gandi, Infomaniak, etc.) puis relié à GitHub Pages par les réglages DNS.

## Maintenance courante

Pour ajouter une publication : copier un bloc publication dans `publications.qmd`, modifier le titre, les auteurs, l'année et le DOI.

Pour actualiser un projet : modifier directement `projets.qmd`.

Pour changer l'accueil : modifier `index.qmd`.

## Éléments à décider plus tard

- nom de domaine définitif ;
- version anglaise éventuelle ;
- photo définitive (le prototype utilise la photo publique actuellement hébergée sur BETA) ;
- Google Scholar : ajouter l'URL exacte dans le menu lorsque souhaité ;
- éventuelle rubrique Actualités / Médias.
