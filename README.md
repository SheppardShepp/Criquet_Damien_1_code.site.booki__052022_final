<h1 align="center">Projet-01-OC-Site_Booki-</h1>

<div align="center"><img height="200" src="https://user.oc-static.com/upload/2022/06/20/16557256333819_FR_1155_P3_Banner-Booki.png"></div>

## 📝 Sommaires

- [Présentation du projet](#présentation)
- [Aperçu du projet](#projet)
- [Spécification du projet](#specification)

## 💭 Petit mot de présentation <a name = "présentation"></a>

Pour débuter ma formation, dans le cadre de ma reconversion, j'ai dû convertir une maquette en une page web en utilisant uniquement HTML et CSS.

---

## Scénaro du projet

J'ai trouvé mon premier stage en tant que développeur web chez Booki, une petite entreprise proposant un outil de planification de vacances ! Son site permet aux usagers de trouver des hébergements et des activités dans la ville de leur choix. Les hébergements peuvent également être filtrés par thématique, par exemple leur budget ou leur ambiance.
Avant de valider définitivement le design, l’entreprise a décidé de réaliser un prototype. Je suis chargé de créer ce prototype en intégrant la maquette en HTML et CSS.

---

### Langages utilisés

- <img height="30" src="https://img2.freepng.fr/20180503/cee/kisspng-web-development-html-css3-the-ohana-code-logo-2cpaper-projection-shaded_1660937-html-dropdown-js-5aebd5631cd291.7591600015254050271181.jpg"> HTML/CSS

---

## ⛏️ Aperçu du projet <a name = "projet"></a>

#### [Bookie](https://sheppardshepp.github.io/Projet-01-OC-Site_Booki-/) <a name = "bookie"></a> : site internet d'hébergement et d'activité sur une localité

Objectif : Transformer une maquette en HTML & CSS.

Utilisation : <img height="30" src="https://img2.freepng.fr/20180503/cee/kisspng-web-development-html-css3-the-ohana-code-logo-2cpaper-projection-shaded_1660937-html-dropdown-js-5aebd5631cd291.7591600015254050271181.jpg">

Aperçu :

<div align="center"><img height="300" src="https://i.servimg.com/u/f31/13/52/99/79/bookie10.png"> <img height="300" src="https://i31.servimg.com/u/f31/13/52/99/79/bookie11.png"> <img height="300" src="https://i.servimg.com/u/f31/13/52/99/79/bookie12.png"> <img height="300" src="https://i31.servimg.com/u/f31/13/52/99/79/bookie10.jpg"></div>

---

## Les Spécification du projets <a name = "specification"></a>

- Spécifications fonctionnelles :

  - Les usagers pourront rechercher des hébergements dans la ville de leur choix. Le champ de recherche est un champ de saisie, le texte doit donc pouvoir être édité par l’utilisateur. Il faut englober ce champ dans un formulaire pour que ce dernier soit valide auprès du W3C. La partie recherche ne doit pas être fonctionnelle.
  - Chaque carte d’hébergement ou d’activité devra être cliquable dans son intégralité (pas uniquement le titre). Pour l’instant, les liens sont vides. L'utilisation d'un attribut `href=”#”` pour simuler la présence d’un lien est possible.
  - Les filtres doivent changer d’apparence au survol. Le choix de l'effet est libre. Par contre, ils ne doivent pas être fonctionnels.
  - Les textes “Hébergements” et “Activités”, situés dans l’en-tête, sont des liens. Ils doivent mener respectivement vers la section “Hébergements à Marseille” et “Activités à Marseille”.

- Spécifications techniques :

  - Deux maquettes ont été réalisées : l’une desktop et l’autre mobile. Le site devra être également adapté aux formats tablette. Pour les tablettes, il est libres de faire les adaptations nécessaires. Il est important qu’aucun élément ne soit coupé, et que le texte ait une taille suffisante.
  - Concernant les breakpoints, il est convenu avec le designer UI d’utiliser 992 px et 768 px. 992 px pour les écrans d’ordinateurs et 768 px pour les tablettes, et tout ce qui est en dessous de 768 pour les téléphones portables.
  - Il faut d’abord réaliser l’intégration pour les ordinateurs (autrement dit, en desktop first), puis les tablettes et enfin les téléphones. L’utilisation des Media Queries permettra de réaliser l’intégration pour les différents supports.
  - Plusieurs formats et tailles d’images ont été exportés. Il faudra choisir le format le plus adapté par rapport à la résolution et au temps de chargement.
  - Les icônes proviennent de la bibliothèque Font Awesome. Le passage par un CDN est possible pour faciliter le chargement des icônes.
  - Les couleurs de la charte sont le bleu (#0065FC), une version plus claire de ce bleu (#DEEBFF) et le gris pour le fond (#F2F2F2).
  - La police du site est Raleway. Le passage par Google Font est possible pour importer facilement cette police dans le code : https://fonts.google.com/specimen/Raleway.
  - Il est important d’utiliser les pixels et les pourcentages plutôt que les REM et les EM.
  - Il est important d’utiliser Flexbox plutôt que Grid car c’est la techno que l’équipe maîtrise le mieux.
  - Aucun framework CSS (type BootStrap ou Tailwind CSS) ou préprocesseur CSS (type Sass ou Less) ne doit être utilisé.
  - Il est important d’utiliser des balises sémantiques (type `main`, `header`, `nav`, etc.).
  - Le code doit être valide aux validateurs W3C HTML et CSS.
  - La maquette doit être compatible avec les dernières versions de Google Chrome et de Mozilla Firefox. Il faudra tester le prototype sur ces deux navigateurs.
  - Il n’est pas nécessaire de versionner le code.
