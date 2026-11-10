# Scrabble Frame

Application web statique (HTML / CSS / JavaScript) pour créer des cartes A4 de prénoms disposés en grille
façon Scrabble, à imprimer ou à exporter en PDF.

**Démonstration en ligne : https://sebgamblin.github.io/frame/**

## Fonctionnalités

- Les lettres communes entre prénoms créent les croisements.
- Plusieurs dispositions générées automatiquement (boutons ‹ ›).
- Cadres : Classique, Art déco, Pointillé ou sans cadre.
- Impression directe ou export PDF.

## Utilisation

Ouvrir `index.html` dans un navigateur, ou lancer un serveur local :

```bash
python -m http.server
```

L'export PDF charge `html2canvas` et `jsPDF` depuis cdnjs ; les polices viennent de Google Fonts.
