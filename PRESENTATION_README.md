# 🎓 PFA Presentation - Simulation de Stabilité des Structures Civiles par IA

Une présentation professionnelle et interactive créée avec Next.js, TypeScript, Tailwind CSS et Framer Motion.

## ✨ Fonctionnalités

- **15 slides professionnelles** avec animations fluides
- **Navigation intuitive** : clavier, souris, et boutons
- **Mode plein écran** pour les présentations
- **Animations créatives** sur chaque slide
- **Design moderne** avec dégradés et effets visuels
- **Responsive** et optimisé pour tous les écrans

## 🚀 Démarrage rapide

### Installation

```bash
cd programm
npm install
```

### Lancement en mode développement

```bash
npm run dev
```

Ouvrez [http://localhost:3000](http://localhost:3000) dans votre navigateur.

### Build pour production

```bash
npm run build
npm start
```

## 🎮 Contrôles de présentation

### Navigation au clavier

- **Flèche droite** ou **Espace** : Slide suivante
- **Flèche gauche** : Slide précédente
- **F** : Basculer en mode plein écran
- **Echap** : Quitter le mode plein écran

### Navigation à la souris

- **Boutons de navigation** : En bas au centre de l'écran
- **Bouton plein écran** : En haut à droite
- **Indicateur de slide** : En bas à droite
- **Barre de progression** : En haut de l'écran

## 📋 Structure des slides

1. **Slide de titre** - Présentation du projet
2. **Plan** - Sommaire de la présentation
3. **Introduction** - Contexte du projet
4. **Problématique** - Défis à relever
5. **Objectifs** - Objectifs généraux et spécifiques
6. **Étude de l'existant** - Tableau comparatif des solutions
7. **Dataset IA** - Sources et préparation des données
8. **Architecture** - Architecture 3-tiers du projet
9. **Structure** - Organisation des dossiers
10. **Technologies** - Stack technique utilisée
11. **Méthodologie** - Approche Agile/SCRUM
12. **Qualité & Sécurité** - KPIs et mesures de sécurité
13. **Résultats attendus** - Livrables du projet
14. **Conclusion** - Synthèse et perspectives
15. **Remerciements** - Slide finale

## 🎨 Personnalisation

### Modifier le contenu

Éditez le fichier `lib/presentations.ts` pour modifier :
- Le contenu des slides
- Les couleurs de fond
- Les animations
- L'ordre des slides

### Ajouter des slides

```typescript
{
  id: 'slide-new',
  type: 'content', // cover, plan, content, table, split, thanks
  content: {
    title: 'Nouveau slide',
    bulletPoints: ['Point 1', 'Point 2', 'Point 3'],
  },
  background: 'bg-gradient-to-br from-blue-900 to-purple-900',
  animation: 'fade',
  order: 16,
}
```

## 🎯 Types de slides disponibles

- **cover** : Slide de couverture avec titre principal
- **plan** : Sommaire avec liste numérotée
- **content** : Contenu avec titre et bullet points
- **table** : Tableau avec en-têtes et données
- **split** : Contenu réparti en deux colonnes
- **thanks** : Slide de remerciement avec animations spéciales

## 🛠️ Technologies utilisées

- **Next.js 16** - Framework React
- **TypeScript** - Typage statique
- **Tailwind CSS 4** - Styles utilitaires
- **Framer Motion** - Animations fluides
- **React 19** - Bibliothèque UI

## 📱 Responsive Design

La présentation est entièrement responsive :
- Desktop : Affichage complet avec tous les effets
- Tablet : Layout adapté
- Mobile : Navigation simplifiée

## 🎓 Utilisation pour la défense

1. Lancez la présentation en mode plein écran (touche F)
2. Utilisez les flèches du clavier pour naviguer
3. Prenez votre temps sur chaque slide
4. Les animations se déclenchent automatiquement
5. La barre de progression indique l'avancement

## 📝 Notes pour la présentation

- Chaque slide a son propre design unique
- Les animations attirent l'attention sur les points importants
- Les tableaux et listes sont clairement structurés
- Les couleurs suivent une palette cohérente
- Les icônes et emojis rendent la présentation vivante

## 🚀 Déploiement

### Vercel (recommandé)

```bash
npm install -g vercel
vercel
```

### Netlify

```bash
npm run build
# Déployez le dossier .next
```

### Docker

```bash
docker build -t pfa-presentation .
docker run -p 3000:3000 pfa-presentation
```

## 📄 License

Ce projet est créé pour le PFA 2025 - EMSI

## 👥 Équipe

Projet réalisé par l'équipe PFA 2025

---

**Bonne présentation ! 🎉**
