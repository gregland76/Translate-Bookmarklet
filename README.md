# Bookmarklet Traduction

Ce petit bookmarklet permet de traduire rapidement un texte (anglais ↔ français) via Google Translate.

**Fonctionnement**
- Il récupère le texte sélectionné sur la page ou le contenu du champ actif.
- S'il ne détecte pas de texte, il propose une invite pour saisir le texte à traduire.
- Il essaie de deviner la langue source (en/ fr) : si le texte contient des indices français, il demande la traduction vers l'anglais, sinon vers le français.

**Installer**
1. Ouvrez [bookmarklet.html](bookmarklet.html).
2. Glissez-déposez le lien **Traduire (glisser-déposer)** dans la barre de favoris de votre navigateur.
3. Alternative : cliquez sur **Copier** et collez le code dans un nouveau favori (URL du favori).

**Utilisation**
- Sur n'importe quelle page, sélectionnez un texte, ou placez le focus dans un champ contenant du texte.
- Cliquez sur le favori ajouté dans votre barre de favoris.
- Une nouvelle onglet s'ouvrira sur Google Translate avec le texte pré-rempli.

**Remarques & dépannage**
- Si la copie vers le presse-papiers échoue (anciens navigateurs ou pages non sécurisées), le bouton affiche une fenêtre pour copier manuellement.
- Le bookmarklet utilise Google Translate ; la disponibilité et l'interface dépendent de Google.

**Fichier**
- Le bookmarklet et les instructions se trouvent dans `bookmarklet.html`.

---

Si vous voulez que je crée aussi un petit commit Git ou une version imprimable, dites-le-moi.
