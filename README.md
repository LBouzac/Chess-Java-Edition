# Chess-Java-Edition

## Présentation
Chess : Java-Edition est un jeu d'échecs développé entièrement en Java. Ce projet propose une implémentation complète du jeu d'échecs avec possibilité de jouer contre un autre joueur (mode JcJ) ou contre une intelligence artificielle.

## Fonctionnalités prévues
- Interface graphique
- Déplacement des pièces selon les règles officielles des échecs
- Mode joueur contre joueur (sur le même ordinateur)
- Mode joueur contre IA avec différents niveaux de difficulté
- Sauvegarde et chargement de parties
- Historique des coups joués
- Détection automatique des situations spéciales (échec, échec et mat, pat)
- Possibilité de revenir en arrière (annuler un coup)

## Technologies utilisées
- Java 17+
- Gradle pour la gestion des dépendances et la construction du projet
- JavaFX pour l'interface graphique
- JUnit pour les tests unitaires

## Installation et exécution

### Prérequis
- JDK 17 ou supérieur
- Gradle 7.0 ou supérieur

### Étapes d'installation
1. Cloner le dépôt
   ```
   git clone https://github.com/votre-username/Chess-Java-Edition.git
   cd Chess-Java-Edition
   ```

2. Compiler le projet
   ```
   gradle build
   ```

3. Exécuter l'application
   ```
   gradle run
   ```

## Structure du projet (MVC)
Le projet suit le pattern d'architecture MVC (Modèle-Vue-Contrôleur) :

```
com.chess/
  ├── model/       # Données et logique du jeu
  │   ├── Board.java
  │   ├── Piece.java
  │   ├── Game.java
  │   └── ...
  ├── view/        # Interface utilisateur
  │   ├── ConsoleView.java
  │   ├── GUIView.java (si applicable)
  │   └── ...
  ├── controller/  # Gestion des entrées et coordination
  │   ├── GameController.java
  │   └── ...
  └── Main.java    # Point d'entrée
```

## Règles du jeu
Le jeu respecte toutes les règles officielles des échecs, notamment :
- Déplacements spécifiques à chaque type de pièce
- Règles du roque (petit et grand)
- Prise en passant
- Promotion des pions
- Détection des situations d'échec, d'échec et mat et de pat

## Feuille de route
- [x] Mise en place de la structure du projet
- [ ] Implémentation du modèle (pièces, échiquier, règles)
- [ ] Développement de l'interface en ligne de commande
- [ ] Mise en place des contrôleurs
- [ ] Ajout de l'interface graphique
- [ ] Développement de l'IA
- [ ] Fonctionnalités avancées (sauvegarde, historique)
- [ ] Tests et optimisations

## Developpeur
- [LBOUZAC](https://github.com/LBouzac)