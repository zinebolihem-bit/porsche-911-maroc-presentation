# Porsche 911 au Maroc — Dépôt

Ce dépôt contient la présentation en format Markdown "presentation.md" : une diapositive par section, images libres de droits listées avec leurs liens et crédits.

Aperçu :
- 10 diapositives (titre, sommaire, histoire, gamme, fiches techniques, prix indicatifs au Maroc, concessions, aspects pratiques, galerie, sources)
- Auteur : Zineb olehem
- Images : uniquement libres de droits (Unsplash, Pexels, Wikimedia Commons). Les images ne sont pas incluses dans le dépôt — elles sont référencées par lien pour respecter les licences et permettre au propriétaire du dépôt d’importer celles qu’il souhaite.

Comment générer un PDF :
1. Ouvrez "presentation.md" localement ou dans un éditeur (Visual Studio Code, Typora, etc.).
2. Téléchargez les images via les liens dans la section Galerie et placez-les dans un dossier `images/`.
3. Remplacez les liens d’image dans le markdown par les chemins locaux (`images/nom.jpg`).
4. Ouvrez le Markdown dans PowerPoint (ou copiez-collez par diapositive) et exportez en PDF, OU utilisez Pandoc :

   pandoc presentation.md -o presentation.pdf --pdf-engine=xelatex

Remarques :
- Si vous souhaitez que je génère directement un PDF et que je l’ajoute au dépôt, je peux le faire (mais je dois incorporer les images dans le fichier). Dites‑le si vous voulez que je génère le PDF final (je peux intégrer des images libres et committer le PDF ici).

Lien du dépôt : https://github.com/zinebolihem-bit/porsche-911-maroc-presentation

