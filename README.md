# FC Bobbles Club — Créateur d’équipes (Futsal)

Application front 100% statique (HTML/CSS/JS) pour :
- créer des équipes équilibrées (duos, niveau joueurs)
- afficher barre d’équité & probabilité de victoire
- gérer MVP / mentions honorables, historique et Elo
- partager des feuilles de match / affiches (selon options)
- tirage chasubles (aléatoire)

> ⚠️ **Données locales** : tout est stocké en `localStorage`. Chaque appareil a ses propres données (pas de serveur).

---

## 🚀 Démarrage local

1. Télécharge/clône le repo.
2. Ouvre simplement `index.html` dans ton navigateur (double-clic).

Aucune installation ni build requis.

---

## ☁️ Déploiement — **Option 2 : GitHub Pages (gratuit)**

### 1) Créer le repo et pousser le code

Dans un terminal, à la racine où se trouve `index.html` :

```bash
git init
git add -A
git commit -m "init: FC Bobbles Club"
git branch -M main
git remote add origin https://github.com/<ton-user>/<ton-repo>.git
git push -u origin main
