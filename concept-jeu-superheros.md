# Concept — Jeu de super-héros coopératif asynchrone

## Pitch

Jeu navigateur, type RPG lite thème **super-héros**, jouable en **asynchrone** : les joueurs préparent des actions puis reviennent plus tard consulter les résultats. Chaque joueur crée son propre **ville privée**, invitable entre amis, collègues, etc.

## Principes fondateurs

- **Asynchrone assumé** : pas besoin d'être connecté en même temps que les autres. La double vie du super-héros (identité civile / masquée) justifie narrativement l'absence du joueur — ce n'est pas un vide, ça fait partie du personnage.
- **Villes
-  privés** : chaque groupe joue dans son propre monde, séparé des autres. Favorise la coopération plutôt que la compétition anonyme.
- **Coopération via le Super QG** : les joueurs se regroupent en équipes autour d'une base commune (le QG), lieu de coopération concret sans obliger à jouer simultanément.

## Personnages

- Chaque joueur crée son super-héros avec des **pouvoirs spéciaux**.
- Progression du personnage : débutant → héros expérimenté.
- **Jusqu'à 3 personnages par joueur**, mais **un seul actif à la fois**.
  - Permet de gérer un héros indisponible (blessé, identité compromise, popularité négative...) en basculant sur un autre.
  - Pistes à creuser : héros "brûlé" mis en retrait, rôle de mentor/senior en soutien d'un rookie, "death spiral" douce sans jamais bloquer le joueur.
- **Déblocage de pouvoirs** en progressant, permettant de créer de nouveaux héros avec de nouvelles capacités.
  - Fonctionne comme un arbre de progression *partagé* entre tous les futurs héros du joueur.
  - Donne une raison de continuer à jouer même quand le héros actif est déjà fort.

## Activités

Deux boucles de contenu principales :

1. **Missions officielles**
   - Rapportent expérience, popularité, etc.
2. **Activités annexes**
   - Ex. : gala de charité, fréquentation du monde de l'illégalité, etc.

### Deux axes de progression possibles (piste à approfondir)

- **Popularité / image publique** : missions officielles, galas → accès à des sponsors, ressources légales, statut de héros modèle.
- **Réseau souterrain / pègre** : contacts illégaux, marché noir → accès à des infos ou équipements que la voie légale ne permet pas.

Ces deux voies ne sont pas jugées moralement : chaque joueur optimise son propre style de jeu (héros exemplaire vs héros aux méthodes zone grise).

## Points forts identifiés

- Le thème super-héros colle naturellement au format asynchrone (double vie).
- Le système 3 persos / 1 actif est un bon levier de gameplay et de flexibilité.
- Le déblocage de pouvoirs comme "méta-progression" est un fort levier de rétention.
- Le Super QG donne un ancrage coopératif concret sans exiger de synchronisation.

## Points de vigilance à creuser plus tard

- **Rythme des ticks** : fréquence de résolution des actions (horaire ? quotidien ?) — influence fortement la sensation de jeu (actif vs contemplatif).
- **Équilibrage des rythmes de jeu entre joueurs** d'une même équipe (joueur quotidien vs occasionnel) pour éviter la frustration au sein du QG commun. Piste : contributions individuelles à un pot commun plutôt que partage strict de niveau.
- **Taille des univers privés** : mécaniques fines pour petits groupes (3-6) vs systèmes qui scalent pour groupes plus larges (guildes, sous-groupes).
- **Infra technique** : l'asynchrone permet de se passer de temps réel — un système de jobs planifiés (cron/queue) + notifications (email, webhook Discord) peut suffire pour un premier prototype.

## Questions ouvertes

- Que prépare-t-on exactement à chaque tour ? Actions individuelles ou décisions collectives ?
- Les ressources du QG sont-elles partagées entre tous les membres, ou chacun a-t-il son perso avec des croisements ponctuels ?
- Quelle est la fréquence de connexion visée (plusieurs fois par jour, une fois par jour, quelques fois par semaine) ?
