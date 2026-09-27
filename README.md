# Logipropre — site (proposition optimisée)

Site vitrine **optimisé** pour **Logipropre SRL** (nettoyage, évacuation et
assainissement — Wallonie & Bruxelles). Proposition de refonte à présenter au
propriétaire.

- **Une seule page** statique (`index.html`), CSS et JS en ligne, aucune
  dépendance hors la police Rubik (Google Fonts). Rapide, responsive, accessible.
- **SEO** : meta, Open Graph, données structurées `CleaningService` /
  `LocalBusiness`, sitemap, robots.
- **Contenu réel** : services, avis, coordonnées (081 39 65 30, Chée des
  Ardennes 3, 5330 Assesse), agrément Ministère de la Santé n°8666,
  TVA BE0832146964, réseaux sociaux.
- **Visuels** : logo officiel et photos de chantier fournis par le client
  (`img/`).

## Structure

| Fichier | Rôle |
|---|---|
| `index.html` | La page complète (styles + script inclus) |
| `img/logo.png` | Logo officiel Logipropre |
| `img/realisation-1.webp`, `realisation-2.webp` | Photos de chantier |
| `.github/workflows/pages.yml` | Déploiement GitHub Pages |
| `robots.txt` · `sitemap.xml` | Référencement |

## Déploiement

Poussé sur `main` → GitHub Pages via le workflow. URL de démo :
**https://cronobots.github.io/LOGIPROPRE/**

> Si Pages n'est pas actif : *Settings → Pages → Source : GitHub Actions*.

## À finaliser avant mise en production

- Brancher le **formulaire** sur l'e-mail de Logipropre (ou un service type
  FormSubmit).
- Ajouter d'autres **photos avant/après** et, si souhaité, une carte Google.
- Domaine : ne pas pointer `logipropre.be` sans l'accord du propriétaire.
