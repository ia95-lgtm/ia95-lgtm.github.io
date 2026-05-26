# Portfolio — Issam Amraoui

Site personnel et CV en ligne. Développeur full-stack (PHP/Laravel · Vue.js), Liège.

🔗 **En ligne :** https://ia95-lgtm.github.io

---

## Contenu du dépôt

| Fichier | Rôle |
|---|---|
| `index.html` | Le site (page unique, thème terminal/dev) |
| `CV_Issam_Amraoui.pdf` | CV téléchargeable depuis le site |
| `404.html` | Page d'erreur personnalisée |
| `.nojekyll` | Désactive le build Jekyll de GitHub (sert le site tel quel) |

---

## Déployer sur GitHub Pages (≈ 5 min)

1. **Créer le dépôt** sur GitHub, nommé exactement `ia95-lgtm.github.io` (visibilité *Public*).
2. **Téléverser** tout le contenu de ce dossier à la racine du dépôt
   (*Add file → Upload files*, puis glisser-déposer, puis *Commit changes*).
3. **Activer Pages** : onglet *Settings* → *Pages* → Source = branche `main`, dossier `/ (root)` → *Save*.
4. Patienter 1–2 min : le site est en ligne sur **https://ia95-lgtm.github.io**.

À chaque modification de `index.html` re-téléversée, le site se met à jour automatiquement.

---

## Domaine personnalisé (optionnel)

Pour un lien type `issamamraoui.dev` :
1. Acheter le domaine (Cloudflare Registrar ou Namecheap, ~12 €/an).
2. Ajouter un fichier `CNAME` (sans extension) à la racine, contenant uniquement le domaine, ex. `issamamraoui.dev`.
3. Chez le registrar, créer les enregistrements DNS pointant vers GitHub Pages
   (4 enregistrements A vers les IP de GitHub + un CNAME `www`).
4. Dans *Settings → Pages → Custom domain*, renseigner le domaine et cocher *Enforce HTTPS*.
