# Eco-BTP Deal - Documentation Projet

## Statut Actuel
**Phase : Alpha**
**Testeurs : 10 artisans pionniers**
**Date : 20 janvier 2026**

---

## URLs de Production

| Environnement | URL |
|---------------|-----|
| **Web App** | https://eco-btp-deal-mobile.vercel.app |
| **Vercel Dashboard** | https://vercel.com/el-jebari-bachirs-projects/eco-btp-deal-mobile |

---

## Configuration Technique

### Identifiants Application
```
App ID: com.ecobtp.deal
App Name: Eco-BTP Deal
Version: 1.0.0
```

### Stack Technique
- **Frontend**: React 18.3.1 + TypeScript
- **Styling**: Tailwind CSS 3.4
- **Build Tool**: Vite 5.4
- **Mobile**: Capacitor 6.0 (Android)
- **Hébergement**: Vercel

### Dépendances Principales
```json
{
  "react": "^18.3.1",
  "react-dom": "^18.3.1",
  "recharts": "^2.12.0",
  "lucide-react": "^0.460.0",
  "@capacitor/core": "^6.0.0",
  "@capacitor/android": "^6.0.0",
  "@capacitor/splash-screen": "^6.0.0"
}
```

---

## Structure du Projet

```
eco-btp-deal-mobile/
├── App.tsx                    # Composant principal
├── index.tsx                  # Point d'entrée
├── index.css                  # Styles Tailwind
├── types.ts                   # Types TypeScript
├── components/
│   ├── WelcomeModal.tsx       # Écran d'accueil (modifié pour Alpha)
│   ├── GuideModal.tsx         # Guide utilisateur
│   ├── PickupSlip.tsx         # BON DE RETRAIT (signature)
│   ├── RSECertificateModal.tsx # CERTIFICAT RSE
│   ├── ProDashboard.tsx       # Tableau de bord Pro
│   ├── AdminDashboard.tsx     # Interface Admin
│   ├── BrowseListings.tsx     # Marketplace
│   ├── PostListing.tsx        # Publication annonces
│   ├── ChatWindow.tsx         # Messagerie
│   ├── SupportChatbot.tsx     # Support client
│   └── ...
├── android/                   # Projet Android natif
├── capacitor.config.json      # Config Capacitor
├── tailwind.config.js         # Config Tailwind
├── vite.config.ts             # Config Vite
└── package.json               # Dépendances
```

---

## Fonctionnalités Validées

### Core Features
- [x] Bon de Retrait avec signature numérique
- [x] Certificat RSE avec impact CO₂
- [x] Marketplace de matériaux
- [x] Tableau de bord Pro
- [x] Interface Admin
- [x] Chat support
- [x] Notifications

### Message Alpha (WelcomeModal.tsx)
```
"Bienvenue sur la version Alpha"
"Réservé aux 10 artisans pionniers"
"Besoin d'aide ? Contactez votre conseillère via le chat"
```

---

## Commandes Utiles

### Développement
```bash
cd /home/jbr6z/eco-btp-deal-mobile
npm run dev          # Serveur local
npm run build        # Build production
```

### Déploiement
```bash
vercel --prod        # Déployer sur Vercel
```

### Android APK
```bash
npm run build
npx cap sync android
npx cap open android  # Ouvrir Android Studio
```

---

## Prochaines Étapes (Post-Alpha)

- [ ] Collecte des retours terrain des 10 artisans
- [ ] Corrections bugs signalés
- [ ] Améliorations UX basées sur feedback
- [ ] Passage en Phase Beta
- [ ] Publication Google Play Store

---

## Contact Projet
**Conseillère disponible via le chat intégré**

---

*Document généré automatiquement - Eco-BTP Deal v1.0.0 Alpha*
