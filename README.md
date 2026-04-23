Street Art Blog — Blog HTML5 / CSS3 Responsive

Description du projet :
Blog dédié au street art, développé en HTML5 et CSS3 pur, sans JavaScript ni framework. Projet d'intégration web axé sur le responsive design, les images adaptatives (<picture>) et la mise en page moderne avec CSS Grid et Flexbox.
Exercice réalisé dans le cadre de la formation 3W Academy.

Fonctionalités :

- Header avec logo et navigation (lien actif stylisé)
- Bannière hero avec citation de Banksy
- Section Actualités (2 articles avec date <time>)
- Section Interviews (2 portraits d'artistes)
- Footer avec formulaire newsletter et liens réseaux sociaux

Page Galerie :

- Grille de 17 photos en CSS Grid responsive (auto-fit, minmax)
- Gestion des formats portrait/paysage via grid-row: span 2
- Sidebar avec commentaires et événements à suivre

Responsive Design :

Images adaptatives avec la balise <picture> et srcset sur 3 breakpoints :

- BreakpointImage servieMobile (< 780px)*-mobile.jpgTablette (< 980px)*-tablette.jpgDesktop (≥ 981px)*-desktop.jpg

Media queries CSS :

- css@media screen and (min-width: 780px) { ... }
- @media screen and (min-width: 980px) { ... }

Stack technique :

- Outil Usage HTML5 Structure sémantique (article, section, aside, time, picture, blockquote, cite)
- CSS3 Mise en page, responsive designCSS Grid Galerie photos adaptive FlexboxNavigation, sections, footerFont Awesome 5Icônes réseaux sociauxGoogle FontsMali (titres) + Source Sans Pro (texte)

Comment utiliser ce projet :

Clone le repo :

- bashgit clone https://github.com/TON_USERNAME/Street-Art-Blog.git
- Ouvre index.html dans ton navigateur — aucune installation requise.

Auteur :
Philippe Kirstetter-Fender
Exercice d'intégration web — formation 3W Academy
