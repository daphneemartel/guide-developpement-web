# Liste de contrôle 101 (pour TP long de Intégration I)

## Structure de répertoires et nomenclatures
- [X] Les noms de dossier sont signifiants et n'ont pas de majuscules, d'espaces ou de caractères spéciaux
- [X] Les noms de fichier sont signifiants et n'ont pas de majuscules, d'espaces ou de caractères spéciaux
- [X] La page se nomme _index.html_ et se situe à la racine du site
- [X] La nomenclature des fichiers est systématique
- [X] La nomenclature des images est systématique (section associée, fonction, etc.)
- [X] Tous les noms de classe sont signifiants et utilisent une nomenclature constante


## Favicon
- [X] Le favicon est fonctionnel et intégré dans toutes les pages 
- [X] Le favicon est signifiant et en lien avec le thème du site

---

## HTML 

### Contenu minimal de l'élément head 
- [X] Doctype: La déclaration du type de document est présent 
- [X] L'élément `html` inclut l'attribut `lang="fr"` (ou "en" si le texte est en anglais). 
- [X] L'élément `charset` définit l'encodage du texte en UTF-8
- [X] Les éléments `meta` (`description`, `keywords`, `author`) sont présents
- [X] L'élément `meta` viewport est présent et complet 
- [X] L'élément `title` est présent et placé après l'élément `charset` 
- [X] Le contenu des éléments `title` est écrit sans faute
- [X] L'élément `link` est bien utilisé pour relier la feuille de styles du document.

### Structure et sémantique
- [X] Les éléments HTML sont utilisés en fonction de leur signification
- [X] Le contenu HTML est écrit dans un ordre logique
- [X] Les éléments de structure sont utilisés selon les règles
- [X] `h1` est unique et décrit le thème de la page
- [X] Les titres (`h1`, `h2`, `h3`, etc.) sont utilisés dans l'ordre et de manière pertinente

### Validité et lisibilité
- [X] Les balises sont correctement imbriquées
- [X] Le code HTML est valide selon le [Validateur HTML du w3c](https://validator.w3.org/)
- [X] Le balisage est indenté correctement et régulièrement

### Hyperliens
- [X] Les liens de la navigation principale sont tous fonctionnels  
- [X] Les liens du contenu sont tous fonctionnels

### Images réactives
- [X] Les images sont imbriquées dans picture (deux sources)

---
## Accessibilité

- [X] Les éléments `a` contiennent du texte (libellé du lien) 
- [X] Toutes les balises `img` ont un attribut `alt` avec un contenu pertinent

---

## CSS
- [X] Les règles de styles sont consignées dans une seule feuille de style externe
- [X] L'instruction __@charset "UTF-8";__ est placée sur la première ligne du fichier
- [X] La feuille de style de réinitialisation précède l'ensemble des règles 
- [X] La charte typo de base est présentée sous le sélecteur :root
- [X] Les tailles de typo sont en em, rem ou vw
- [X] La feuille de styles est valide selon https://jigsaw.w3.org/css-validator/

### Lisibilité
- [X] La feuille de style est ordonnée en fonction des affinités et de la hiérarchie du contenu 
- [X] La feuille de style est écrite lisiblement  
- [X] La feuille de style est commentée
- [X] Les polices importées de Google Fonts sont fonctionnelles

### Réactivité (_Responsive Web Design & Mobile First_)
- [X] L'approche Mobile d'abord est utilisée
- [X] La réactivité de la navigation principale est harmonieuse (horizontale à verticale)
- [X] La réactivité de la zone de contenu des sections est harmonieuse (largeur du texte contrôlée) 
- [X] La réactivité des images (images adaptées écran étroit vs large)
- [X] Le ou les points de rupture sont judicieusement choisis en fonction de l'interface

### Contrôle de la mise en forme 
- [X] L'ensemble du site comporte une identité visuelle personnalisée: couleurs, polices, etc.
- [X] La hiérarchie visuelle des titres est cohérente
- [X] Les images sont mis en forme de manière contrôlée 
- [X] Les hyperliens de contenu sont mis en forme
- [X] Les alignements sont consistants d'une section à l'autre

---

## Performance
- [X] Taille et poids des images contrôlés

## Droits d'auteur
- [X] Les sources des contenus sont indiquées
