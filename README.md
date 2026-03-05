# 🎙 SaintGab Radio — GitHub Pages + OBS

Ta radio en ligne, 100% gratuite, propulsée par OBS + YouTube Live.

## 🚀 Mise en ligne sur GitHub Pages

1. Va sur **github.com** → crée un nouveau repository nommé `ma-radio`
2. Upload le fichier `index.html` dans ce repo
3. Va dans **Settings → Pages**
4. Source → **Deploy from a branch** → branche `main` → dossier `/ (root)`
5. Clique **Save** → ton site est en ligne sur `https://TONNOM.github.io/ma-radio`

## 🔧 Configuration OBS

1. Ouvre OBS → **Paramètres → Flux**
2. Service : **YouTube - RTMPS**
3. Connecte ton compte Google
4. La clé de stream est automatique ✅
5. Clique **Démarrer le stream** 🔴

## 🌍 Connecter YouTube à ta page

1. Lance ton live sur YouTube
2. Copie l'ID dans l'URL : `youtube.com/watch?v=**CECI_EST_L_ID**`
3. Sur ta page radio → clique **⚙️ Configurer ma radio**
4. Colle l'ID → Appliquer ✅

## 📻 Résultat

```
Micro + Musique
      ↓
     OBS
      ↓
YouTube Live (gratuit)
      ↓
  GitHub Pages
(ta page radio) 🌍
```

Tout le monde écoute sur `https://TONNOM.github.io/ma-radio`

---
100% gratuit • Aucun serveur • Juste OBS + YouTube + GitHub
