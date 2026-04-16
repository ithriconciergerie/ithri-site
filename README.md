# Ithri Conciergerie — Site Web

## 🚀 Déploiement sur Vercel (100% gratuit)

### Étape 1 — Préparer le projet
1. Extrayez le dossier `ithri-site` sur votre ordinateur
2. Créez un compte gratuit sur [github.com](https://github.com)
3. Créez un nouveau repository "ithri-site" et uploadez tous les fichiers

### Étape 2 — Déployer sur Vercel
1. Allez sur [vercel.com](https://vercel.com) → "Sign up" avec votre compte GitHub
2. Cliquez **"New Project"** → importez votre repo "ithri-site"
3. Vercel détecte automatiquement Next.js → cliquez **"Deploy"**
4. ✅ Votre site est en ligne en ~2 minutes sur une URL type `ithri-site.vercel.app`

### Étape 3 — Connecter votre domaine
1. Achetez votre domaine (ex: `ithriconciergerie.com`)
2. Dans Vercel → Settings → Domains → ajoutez votre domaine
3. Suivez les instructions DNS → actif en 24h

---

## ✏️ Modifier le contenu facilement

### Ajouter / modifier un appartement
→ Ouvrez `components/apartments.js`
→ Copiez un bloc existant et modifiez les valeurs

### Modifier les voitures / prix
→ Ouvrez `components/cars.js`
→ Changez `CAR_PRICE_PER_DAY` pour le prix
→ Ajoutez un bloc pour un 2ème véhicule

### Changer les photos
→ Remplacez les liens `img:` par vos propres photos
→ Hébergez vos photos sur [Cloudinary](https://cloudinary.com) (gratuit)

### Changer les textes
→ Tout le contenu est dans `app/page.jsx`

---

## 🔧 Lancer en local (développement)
```bash
npm install
npm run dev
# Ouvre http://localhost:3000
```

## 📦 Stack technique
- **Next.js 14** — Framework React
- **Vercel** — Hébergement gratuit
- **Polices** — Cormorant Garamond + Montserrat (Google Fonts)
