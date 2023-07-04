
### Dossiers les plus importants pour se retrouver 

- layouts
- pages
- routes
- redux
- components
- hooks

#### Utilite de chaque Dossiers et conventions de nomenclature

#### ```--------layouts```: Il contient en global la structure de notre page. Voici les fichiers et dossiers importants
```css
RequireAuth.js: C'est ici qu'on verifie si le user est connecte ou pas .
```
```css
sidebar/
  SidebarComponent.js: Le sidebar de notre application
```
```css
navbar/
  NavbarComponent.js: Le navbar de notre application
```


#### ```--------routes```: gère toutes les routes de l'applications. Que cela soit les routes back ou front. Ce dossier contient ***2 grands dossiers*** et ***1 fichier***: ```api```, ```navigation``` et ```Routes```



```css
navigationRoutes.js: Ce fichier contient le systeme de routing de l'application. C'est ici qu'on ajoute les pages qui doivent s'afficher dans un tableau. Puis on map ces tableaux dans ***Roots.js****
```
```css
Roots.js: Le fichier qui map toutes les routes de facon recursive. C'est a dire que si vous voulez avoir des routes imbriquer, il suffit juste d'aller sur navigationRoutes.js et ajouter la propriete children sur la route que vous voulez
```

#### ```--------redux```: contient l'etat, la logique et les appels d'api. Voici les dossiers a comprendre: ```apiController``` et ```features```
```css
apiController/
  ici on définit les appels d'api
```
```css
features/
  ici on définit les slices de l'application
```
#### ```--------components```: ici on définit les composants de l'application

#### ```--------hooks```: Don't Repeat Your self, ce dossier nous permet de créer des hooks réutilisables
