# Jeu 1D sur bande DEL

Un tir à la corde à deux joueurs sur une bande de 60 DEL. Chacun martèle son bouton pour pousser la lumière vers le camp adverse. Programmé en nodal dans TouchDesigner.

## Contexte

Projet réalisé dans le cadre du cours de Médias interactifs (Techniques d'intégration multimédia, Cégep Édouard-Montpetit).

Le mandat : concevoir une expérience interactive sur une bande DEL 1D.

## Mon rôle

Projet solo : conception du jeu, direction visuelle et programmation.

## Technologies

- **TouchDesigner** : logique de jeu et contrôle de la bande de DEL
- **Simulation clavier** : les touches remplacent les boutons physiques pour tester le jeu

## Le jeu

Deux joueurs, un bouton chacun. Chaque appui fait avancer la lumière vers l'adversaire. Le premier qui pousse la lumière jusqu'au bout de la bande gagne.

Le jeu suit trois états :

1. **Intro** : écran d'attente et présentation
2. **Jeu** : le tir à la corde
3. **Conclusion** : affichage du gagnant

L'identité visuelle est inspirée des dragons.

## Démarche

1. **Idéation** : choix d'un jeu simple à comprendre en quelques secondes
2. **Logique de jeu** : position de la lumière selon les appuis de chaque joueur
3. **États du jeu** : enchaînement intro, jeu, conclusion
4. **Identité visuelle** : thème des dragons
5. **Tests** : simulation des boutons au clavier sur les 60 DEL

## Limites connues

- Le jeu est simulé au clavier(Touches 1 et 2) ou boutons physiques
- Conçu pour une bande de 60 DEL précisément

## Crédits

- Conception, design et programmation : Yoan Robitaille
- Éléments : 
- Ai utiliser pour généré les son de victoire : Rouge a gagner, ainsi que Bleu a gagner : https://www.minimax.io/audio/text-to-speech
- Son de jeu à été trouvé sur Pixabay - Tense Drum Loop par DRAGON-STUDIO : https://pixabay.com/sound-effects/search/intense-loop/
- Son d'intro à été trouvé sur Pixabay - Soft-piano-loop par Ncone : https://pixabay.com/sound-effects/search/game-loop/

## Auteur

**Yoan Robitaille** · Dev média interactif / Dev web