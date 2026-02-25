# CineTrack — Documentation Interactives

Cette page documenta les maquettes et le roadmap de développement de **CineTrack**, une application **React Native** de découverte et suivi de films avec IA embarquée.

## 📱 Accéder à la documentation

La documentation interactive est disponible sur **GitHub Pages** :

- **URL**: https://quentinncl.github.io/expo-start-project-cinetrack/
- Fichier: `index.html` (généré automatiquement par GitHub Pages)

## 📋 Contenu de la documentation

La maquette interactice présente :

- **Accueil** — Grille de films populaires avec système de favoris
- **Recherche** — Barre de recherche avec debounce et résultats instantanés  
- **Favoris** — Gestion des films favoris avec persistance
- **Détail** — Page détaillée d'un film avec synopsis et notes
- **CineBot** — Chat IA pour recommandations personnalisées

## 🛠️ Structure du développement

Le roadmap se divise en **3 jours** :

### Jour 1 — Fondations
- Écran d'accueil avec grid de films
- Écran de détail avec navigation Stack
- Gestion des favoris de base

### Jour 2 — Fonctionnalités
- Écran de recherche avec debounce
- Persistance des favoris (AsyncStorage + Context API)
- Pages vides élégantes

### Jour 3 — IA
- Intégration API IA (format OpenAI)
- Chat streaming avec CineBot
- Recommandations personnalisées

## 📚 Concepts clés par écran

Chaque écran utilise des concepts spécifiques :

- **Components**: View, Text, Image, Pressable
- **Layouts**: StyleSheet, Flexbox, FlatList
- **État**: useState, Context API, useReducer
- **Navigation**: Expo Router, Stack navigation
- **Storage**: AsyncStorage pour persistance
- **API**: Streaming SSE, System prompts

---

**Note interactive** — Cliquez sur les éléments du mock telefone pour naviguer entre les écrans.
