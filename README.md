# Solstice Architectes

Site vitrine d’un atelier d’architecture bordelais **fictif**, qui dessine ses bâtiments à partir de la course du soleil.

**En ligne :** https://anonyme-00152.github.io/solstice-architectes/

## Ce que contient le site

- **Étude d’ensoleillement 3D** : une maquette d’étude éclairée par la position réelle du soleil à Bordeaux (44,84° N) le 21 juin. Les ombres suivent l’heure choisie avec le curseur. Le soir, les fenêtres s’allument.
- **Planches de projets** dessinées en Canvas 2D : coupe solaire, toiture en sheds, façade, courbes de niveau et plan avec sa trame de poteaux. Chaque projet s’ouvre sur une fiche détaillée.
- **Indicateurs RE2020** (Ic construction, Cep,nr, Bbio, DH) comparés aux seuils réglementaires.
- **Planning type** d’une maison neuve sur 18 mois, de l’esquisse à la remise des clés.
- **Formulaire de demande** qui prépare un message à copier.
- Thèmes clair (jour) et sombre (nuit), affichage mobile, navigation au clavier et respect du réglage « réduire les animations ».

## Lancer le site en local

Le site tient dans un seul fichier, `index.html`. Pour l’ouvrir avec un petit serveur local :

```bash
python -m http.server 8000
```

Puis rendez-vous sur http://localhost:8000.

## Technologies

- [Three.js](https://threejs.org/) r128 pour la scène 3D
- [GSAP](https://gsap.com/) 3.12.5 et ScrollTrigger pour les animations au défilement
- [Lenis](https://lenis.darkroom.engineering/) 1.1.13 pour le défilement fluide
- Polices Google Fonts : Big Shoulders Display, Hanken Grotesk et IBM Plex Mono

Les bibliothèques sont chargées depuis cdnjs et jsDelivr : le site n’a pas d’étape de compilation.

## Avertissement

La marque, l’adresse, l’e-mail, les projets, les chiffres et les témoignages sont inventés pour la démonstration. Les seuils RE2020 sont donnés à titre indicatif.
