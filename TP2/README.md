# TP 2 HTML : Site Vitrine Centre Médical Al Amal

## 📋 Fichiers livrables

### Fichiers HTML créés :
1. **index.html** - Page principale du site vitrine
2. **contact.html** - Page de contact avec formulaire patient

### Fichiers médias nécessaires (à placer dans le même dossier) :
- **poster.jpg** - Image du centre médical (vous l'avez déjà)
- **t-rex-roar.mp3** - Audio d'accueil (vous l'avez déjà)
- **ma_video.mp4** ou **ma_video.avi** - Vidéo de présentation (à créer/ajouter)
- **mon_doc.pdf** - Guide patient (vous l'avez déjà)

---

## ✅ Conformité avec les exigences du TP

### Partie 1 : Structure générale ✓
- Page principale avec titre et sections identifiées
- Organisation logique du contenu

### Partie 2 : Navigation et liens ✓
- Lien externe : Ministère de la Santé (https://www.sante.gov.ma) avec target="_blank"
- Lien interne : vers page contact.html
- Liens ancrés : navigation interne (#services, #presentation, etc.)
- Liens mailto: et tel: fonctionnels

### Partie 3 : Intégration des médias ✓

**Image :**
- Image avec attribut src="poster.jpg"
- Texte alternatif adapté au contexte médical
- Dimensions spécifiées (width="600" height="400")

**Audio :**
- Élément <audio> avec contrôles
- Message d'information (utilise t-rex-roar.mp3)
- Contrôle utilisateur activé

### Partie 4 : Vidéo de présentation ✓
- Balise <video> avec attribut poster="poster.jpg"
- Contrôles de lecture activés (controls)
- Sources multiples (mp4 et avi)
- Message de fallback pour navigateurs incompatibles

### Partie 5 : Formulaire de contact patient ✓
- Champ nom (type="text", required)
- Champ email (type="email", required)
- Zone de texte pour le message (textarea, required)
- Bouton d'envoi (submit)
- Validation HTML avec attributs required
- Champs supplémentaires : téléphone, date, service médical, etc.

### Partie 6 : Localisation (iframe) ✓
- Carte Google Maps intégrée
- Largeur adaptée (width="100%")
- Hauteur définie (height="450")
- Localisation : Mohammedia, Maroc

### Partie 7 : Expérience utilisateur ✓
- Titres hiérarchisés (h1, h2, h3)
- Séparateurs visuels (<hr>)
- Tableau pour les horaires
- Navigation claire
- Footer avec liens

---

## 🚀 Instructions d'utilisation

1. **Téléchargez les deux fichiers HTML** (index.html et contact.html)
2. **Placez-les dans le même dossier que vos médias** :
   - poster.jpg
   - t-rex-roar.mp3
   - ma_video.mp4 (ou .avi)
   - mon_doc.pdf

3. **Ouvrez index.html dans votre navigateur**

4. **Testez toutes les fonctionnalités** :
   - Navigation entre les pages
   - Lecture audio
   - Lecture vidéo (si vous avez le fichier vidéo)
   - Formulaire de contact
   - Carte Google Maps
   - Tous les liens

---

## 📝 Notes importantes

### Pour la vidéo :
Si vous n'avez pas de fichier vidéo "ma_video.mp4", vous pouvez :
- Créer une vidéo simple avec votre téléphone
- Utiliser une vidéo libre de droits
- Ou remplacer par une vidéo YouTube en iframe (comme dans page3.html)

### Pour l'audio :
Le fichier t-rex-roar.mp3 est utilisé comme placeholder. Dans un vrai contexte médical, vous pourriez enregistrer :
- Un message de bienvenue
- Les horaires d'ouverture
- Des informations pratiques

---

## 🎯 Points forts de ce site

1. **Complet** : Toutes les exigences du TP sont couvertes
2. **Professionnel** : Contexte médical réaliste
3. **Accessible** : Textes alternatifs, structure sémantique
4. **Fonctionnel** : Tous les liens et médias sont opérationnels
5. **Responsive** : Largeur 100% pour la carte, viewport configuré

---

## 📸 Capture d'écran

N'oubliez pas de prendre une capture d'écran du rendu final pour votre livrable !

---

**Bon courage pour votre TP ! 🏥**
