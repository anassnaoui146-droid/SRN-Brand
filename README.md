# YOUR BRAND — Multi-page

Ce projet est une vraie structure multi-pages :
- index.html → Accueil
- boutique.html → Boutique
- histoire.html → Histoire
- blog.html → Blog
- article-1.html / article-2.html / article-3.html → articles séparés
- contact.html → Contact
- panier.html → Panier
- livraison.html / retours.html / conditions.html / confidentialite.html → pages séparées

## Important
Le navigateur du visiteur ne doit pas connaître `C:\Users\H_R\OneDrive\Desktop\divastra-like`. Cette adresse est seulement un dossier LOCAL. Pour que n'importe qui puisse accéder au site, il faut démarrer le serveur puis publier le projet sur un hébergement et utiliser un domaine/URL public.

## Lancer localement
```bash
cd backend_python
python -m venv .venv
# Windows
.venv\Scripts\activate
pip install -r requirements.txt
python app.py
```
Puis ouvrir `http://127.0.0.1:5000/`. Le Flask sert aussi les pages HTML, CSS et JS.

## Production
Pour rendre le site public, héberger Python + MySQL sur un serveur (VPS/PaaS), connecter un domaine, activer HTTPS, puis utiliser l'URL publique, par exemple `https://www.votredomaine.ma/`.
