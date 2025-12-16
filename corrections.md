## A) Favicons : utiliser `./` (fichiers à la racine)
- Vos favicons sont référencés sans `./`
- Veuillez utiliser `./` si les fichiers sont à la racine
- Exemple :
```
<link rel="icon" type="image/png" sizes="32x32" href="./favicon-32x32.png">
<link rel="icon" type="image/png" sizes="16x16" href="./favicon-16x16.png">
<link rel="manifest" href="./site.webmanifest">
<link rel="apple-touch-icon" sizes="180x180" href="./apple-touch-icon.png">
```

## B) Photo du header : ouvrir l’image dans un nouvel onglet + sécurité
- Le clic sur la photo doit ouvrir l’image dans un nouvel onglet
- Veuillez ajouter `target="_blank"` et `rel="noopener noreferrer"`
- Exemple :
```
<a href="./img/homer-simpson-png-vaztn2xp5wb28jcy.png" target="_blank" rel="noopener noreferrer" class="logo">
  <img src="./img/homer-simpson-png-vaztn2xp5wb28jcy.png" alt="Photo de Siyar Ozan Külüg">
</a>
```
