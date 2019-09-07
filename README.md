# Ruleset Hexagon

*Version 1.0 (07/09/2019) - Document sujet à changement*

---

## Introduction
Ce document sert à représenter / exposer les règles qui seront suivies dans l'intégralité des tournois Hexagon ainsi que les tournois voulant adhérer à ce ruleset. Il est inspiré en grande partie par les rulesets utilisés aux Etats-Unis d'Amérique (ex: MIOM Recommended Ruleset, Apex, EVO, Genesis).

## Glossaire

- **TO** : Tournament Organizer. C'est la ou les personnes en charge de l'organisation du tournoi.
- **Bracket** : Organigramme indiquant le déroulement d'un tournoi et la progression des joueurs au sein de ce dernier. Le bracket est la plupart du temps sous forme d'une double elimination (Upper/Winner
bracket et Lower/Loser bracket, et élimination à l'issue d'une défaite en lower bracket).
- **Poules** : Phase de qualification prenant place avant le Bracket.
- **Set** : Rencontre entre 2 joueurs au cours d'un bracket/poules. Le set peut prendre 2 formes principales en fonction de l'avancée dans le tournoi et de son format, à savoir Best Of 3 ou Best Of 5 (Bo3/Bo5). Dans le cas d'un Bo3, le premier avec 2 matches gagnés remporte le set. Dans le cas d'un Bo5, le premier à 3 matches gagnés remporte le set.
- **Match** : Match individuel au sein d'un set. Le match se termine lorsque l'un des joueurs perd tous ses stocks ou que la limite de temps est atteinte.
- **Setup** : Ensemble Console + TV.
- **RPS** : Pierre, Feuille, Ciseaux.
- **Stock** : Un stock équivaut à une vie. Les matches se déroulent en 4 stocks.
- **Stage** : Niveau sur lequel un match se déroule.
- **Stage Striking** : Phase de banissement à tour de role des différents stages au début d'un set.
- **DQ** : Disqualification.
- **UCF** : Universal Controller Fix. Une modification logicielle ou matérielle permettant de corriger des défauts inhérents à la plupart des manettes, rendant celles-ci compétitivement viables dans un très grand nombre de cas.
- **Vanilla** : Version originelle du jeu, non modifiée
- **Coaching** : Acte de recevoir un ou des conseils de la part d'un autre joueur

---

## Matériel

Version jouée : **Super Smash Bros. Melee NTSC v1.02 + UCF v0.73**

Note : Étant donné que la France est un territoire originellement PAL, il convient d'appliquer si nécessaire la sauvegarde de modification PAL vers NTSC.

Lien: [https://smashboards.com/threads/pal-to-ntsc-memcard-save-v2-1.467853/](https://smashboards.com/threads/pal-to-ntsc-memcard-save-v2-1.467853/)

Autre avantage, cette sauvegarde contient UCF 0.73, ce qui évite d'appliquer les deux modifications.

**Cette sauvegarde qui permet de transitionner entre les régions sera nommée "PAL2NTSC Save" dans la suite du document.**

### Consoles

Les configurations de consoles présentes aux tournois utilisant le ruleset Hexagon sont les suivantes

- les GameCube avec jeu originel PAL + PAL2NTSC Save
- les Wii avec jeu originel PAL + PAL2NTSC Save
- les Wii avec Nintendont ou Slippi Nintendont
    - Option "Native Control" obligatoirement activée dans Nintendont
    - UCF activé obligatoirement
    - ISO NTSC non modifié

### UCF

Les tournois seront joués dans la mesure du possible sur UCF (*Universal Controller Fix*). Cependant, en cas
d'impossibilité, le TO peut à sa discrétion décider de ne pas utiliser UCF, en cas de souci de logistique. Dans
tous les cas, il faut que la décision soit entière : soit tout le tournoi se déroule sur UCF, soit il se déroule sur
Vanilla.


Version d'UCF utilisée: **v0.73**

### Ecrans

- CRT 4/3
- CRT 16/9, toléré mais non encouragé car déforme l'image
- Ecran LCD Lagless avec adaptateur Wii2HDMI
    - Adaptateurs Wii2HDMI Recommandés
        - Neoya Wii2HDMI
        - Sewell Wii2HDMI
    - Ecrans LCD Recommandés (*input lag entre parenthèses*)
        - Asus VH238H (2ms)
        - BenQ RL2455HM (2ms)
        - Asus VG428QE (0,7ms)
        - Asus PA238Q (2,2ms)
        - BenQ RL2450HT (4,2ms)
        - BenQ XL2430T (~4ms)


### Manettes

Chaque joueur doit amener sa propre manette. Aucun prêt ne sera effectué par les organisateurs.
Les manettes suivantes sont **autorisées**

- Manette Nintendo GameCube Officielle **filaire**
- Manette type B0XX

Tout autre type de manette est **interdite**. (ex : Wavebird, manettes non-officielles, SmashBox, ect)

Il est possible d'autoriser sur une base individuelle les manettes uniques de certains joueurs sous reserve inconditionnelle qu'ils se conforment au [MIOM Controller Addendum](https://docs.google.com/document/d/1EfQeX64iJLM8wXHaZMyH_gC2Zpw3Tk-QSrEBe7RUM1s/view) ([https://docs.google.com/document/d/1EfQeX64iJLM8wXHaZMyH_gC2Zpw3Tk-QSrEBe7RUM1s/view](https://docs.google.com/document/d/1EfQeX64iJLM8wXHaZMyH_gC2Zpw3Tk-QSrEBe7RUM1s/view)). A cet effet, les joueurs concernés devront fournir une description précise de leur matériel et fournir le code embarqué sur le matériel afin qu'une décision puisse être prise. A noter que tout changement du dit code entraine une disqualification du matériel et provoque une nouvelle mise en examen.

###### Modifications de manettes

Sont **autorisées** les modifications de manettes suivantes

- Encoches corrigeant des défauts inhérents à la manette
    - Shield Drop
- Modifications des gachettes
    - Lubrification
    - Modification du point d'actuation (*Trigger trick permanent*)
    - Baisse de la tension du clic digital
- Modifications des boutons
    - Baisse du niveau du bouton
    - Baisse de la tension d'activation du bouton
- Ajout de MOSFETs (Transistor d'amplification) pour corriger les défauts de backdash/snapback d'une manette
- Encoches facilitant l'entrée de certaines valeurs précises (ex : Kadano Hybrid Gate)

Sont **interdites** les modifications de manettes suivantes

- Création de macros
    - Suite de pressions de boutons enregistrée
    - Enregistrement d'une valeur analogique précise (ex : "Bouton Shield Drop")
- Installation d'un microcontrolleur programmable (ex: Arduino)
- Création de tout nouveaux boutons
- Encoches facilitant l'entrée de certaines valeurs précises (ex : Kadano Hybrid Gate)
- Re-wiring de boutons (ex : Appuyer sur B pour sauter)
    - **Mesure pouvant être levée en cas d'handicap manuel avéré.**

---

## Réglages du mode VS

- 4 vies
- Limite de temps : 8 minutes
- Objets désactivés
- Pause désactivée
- Tir allié activé
- Handicap désactivé
- Ratio de dégats 1.0

## Règles générales des matches

- Le premier joueur ou équipe qui perd toutes ses vies perd le match
- Si la limite de temps est atteinte, le joueur avec le plus de vies restantes gagne le match. En cas d'égalité de nombre de vies, c'est le joueur avec les % de dégats les moins élevés qui remporte le match. En cas d'égalité parfaite, un match sera joué avec une seule vie chacun et 2 minutes de temps.
- Si la désactivation de la pause a été omise, un joueur qui appuie sur pause lors d'un match doit sacrifier sa stock courante sauf accord mutuel (clause du *Gentleman*) ou circonstances exceptionnelles, qui seront approuvées par un TO (dysfonctionnement du matériel par exemple)
- Quitter un match avec la combinaison L + R + A + Start équivaut à un abandon et comptera donc le match comme perdu.
- Ne pas commencer un set 15 minutes après que votre set ait été appelé provoque une disqualification complète du joueur absent.
- En cas de désagrément quelconque (port manette, couleur du personnage, tag utilisé...), un *RPS* sera utilisé entre les joueurs pour désigner qui est prioritaire sur la décision.

### Règles spécifiques aux doubles / teams (2vs2)

- Un joueur a le droit de prendre des vies à son partenaire lors d'un match de doubles (en appuyant sur start). Il est donc indispensable d'enlever la pause en doubles afin de ne pas causer d'interruptions.
- Interdiction de jouer à la place de son coequipier.
- **Il n'y a jamais de bans (*Bo3* ou *Bo5*) lors des doubles**.


### Personnages
Tous les personnages sont **autorisés** excepté

- Master/Crazy Hand
- Giga Bowser
- Les personnages Wireframe

Le **Color Glitch** (permettant de selectionner la même couleur de personnage que son opposant) est **interdit**.

### Stages
Sont **admis** comme stages légaux les stages suivants

##### Simples (1v1)

- Starter Stages
    - Yoshi’s Story
    - Fountain of Dreams
    - Final Destination
    - Battlefield
    - Dream Land 64
- Counterpick Stages
    - Pokémon Stadium

##### Doubles (2v2)

- Starter Stages
    - Yoshi’s Story
    - Final Destination
    - Battlefield
    - Dream Land 64
    - Pokémon Stadium
- Counterpick Stages : Aucun

### Clauses de *stalling*

Le non-respect des clauses ci-dessous entraînera automatiquement la perte du Set entier et provoque la disqualification du tournoi.

- Le wobbling est autorisé. Cependant, si le wobbling dure au delà de **300%**, la sanction ci-dessus sera appliquée.
- Les bogues de Freezing des personnages et les pratiques de *stalling* infini sont strictement interdites.

### Clause de Double Blind Pick

Un des joueurs peut demander un double blind pick.
Il se déroule de la façon suivante, et requiert un TO sous la forme de partie neutre et tierce

- Chaque joueur annonce, en secret, à la partie neutre le personnage qu'il souhaite utiliser
- La partie neutre annonce les choix de chaque joueur et veille à ce qu'ils soient respectés

### Color blind Clause / Daltonisme

Dans le cas où l'un des joueurs est *daltonien* (impossibilité de différencier certaines couleurs), il peut demander à son adversaire de changer la couleur de son personnage afin qu'il puisse le distinguer de son propre personnage.

De la même façon, lors d'un set de doubles, une équipe peut demander le changement de couleur de l'équipe adverse afin de prendre en compte le daltonisme d'un des joueurs impliqués. Dans la plupart des cas, les équipes seront respectivement rouge et bleue.

## Déroulement d'un set

Un set se déroule soit en Best of 3 ou bien en Best of 5

- Dans le cas d'un Best of 3, c'est le joueur qui arrive en premier à 2 matches gagnés qui est désigné gagnant du set.
- Dans le cas d'un Best of 5, c'est le joueur qui arrive en premier à 3 matches gagnés qui est désigné gagnant du set.

- **Il n'est pas possible de retourner sur un stage sur lequel on a déjà gagné** (DSR Winner's variation).
- La *Gentleman's Clause* est effective : Il est possible de choisir n'importe quel stage du moment qu'un accord mutuel existe, et cette règle est prioritaire sur la règle ci-dessus.
- Le joueur qui gagne le *RPS* de stage striking décide qui des deux joueurs commence à bannir les stages, il y gagne donc la liberté de décider de pick en premier ou en second et non pas automatiquement le droit de pick en premier.

Un set commence de la façon suivante

1. Les joueurs s'installent sur le *setup* désigné
2. Les joueurs branchent leur manette sur le port de leur choix
    - En cas de conflit, un match de *RPS* sera utilisée pour départager
3. Les joueurs annoncent le personnage qu'ils utilisent
    - Si un des joueurs le veut, ils peuvent utiliser la clause de Double Blind Pick
4. Un match de *RPS* désigne qui pourra entamer le stage striking (*désigné par P1, le perdant sera désigné par P2*) qui opère uniquement sur les Starter Stages (voir ci dessus)
5. P1 bannit un des stages
6. P2 bannit 2 stages
7. P1 bannit un dernier stage et verrouille donc le choix final
8. Un échauffement optionnel d'une minute maximum peut être demandé. Il prend place sur le stage défini à l'étape précédente.
9. Le premier match commence et se finit
10. Dans le cas d'un Bo3, le gagnant du match précédent annonce le stage qu'il bannit
11. Le perdant du match annonce le stage qu'il choisit
12. Le gagnant du match annonce le personnage qu'il utilise
13. Le perdant du match annonce le personnage qu'il utilise
14. Le match commence puis se finit
15. Répéter 10 - 14 jusqu'à ce que le set soit fini

## Autres clauses

- Coaching interdit pendant le déroulement d'un set. Il peut en revanche prendre place entre les sets (y compris lors d'un reset d'une Grande Finale par exemple).
- Lorsqu'un match ou un set est terminé, il n'est pas possible de le rejouer; il appartient au joueur de refuser de jouer sur un environnement qu'il juge inadapté, sauf demande expresse des organisateurs du tournoi.
- Si plusieurs écrans sont libres, un joueur devra jouer sur l'une d'elles si il doit faire son match. L'attente d'un écran en particulier ne sera pas acceptée.
- En cas d'abus, le TO est libre de disqualifier le joueur à l'origine des abus. Enfreindre ces règles entraînera une sanction qui ira de l'avertissement au ban en passant par la disqualification d'un set ou du tournoi entier.


## Comportement

La tenue attendue des participants aux tournois utilisant le Ruleset Hexagon est identique à ce qui est attendu par le Code de Conduite de la communauté internationale de SSBM.
Les TOs utilisant le Ruleset Hexagon sont libres d'être ou ne pas être signataires du dit Code de Conduite et d'appliquer les sanctions recommandées.

Il est cependant **fortement recommandé**, dans un effort de cohésion internationale de garder un environnement compétitif sain, que les TOs utilisant le Ruleset Hexagon soient signataires du Code de Conduite.
