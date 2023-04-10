---
title: "Conseils pour les débutants à Tumbleweed"
---

Ceci est une traduction du document "[Advice for Tumbleweed beginners](/beginner-advice/)" écrit par Tellorion. Traduction également faite par Tellorion.

# Conseils pour les débutants à Tumbleweed

L'idée de ce guide est de vous permettre d'éviter des erreurs communes chez les débutants au jeu de Tumbleweed, et de vous aider à structurer votre réflexion durant vos parties. Certaines de ces erreurs peuvent être des coups qui ont l'air corrects mais qui vous font perdre une pile, ou des "mauvaises habitudes" induises par d'autres jeux auxquels vous jouez (particulièrement le Go). La plupart des points suivants ont été choisis car ils apparaissent souvent dans des parties de débutants sur Board Game Arena. Les sections traitant de ces erreurs sont complétées par d'autres sections sur des principes généraux de Tumbleweed. Celles-ci devraient vous être utiles pour avoir un meilleur ressenti du "flot des coups" et trouver des buts à atteindre dans une position.

Avant la lecture de ce guide, il est recommandé d'avoir joué quelques parties, et d'avoir regardé la vidéo suivante expliquant les boucliers et parades: [Basic defense strategies in Tumbleweed](https://www.youtube.com/watch?v=b1q3ZtuE-cc)

Autre chose: une petite observation sur la terminologie française. En anglais, une pile se traduit par "a stack" et les termes utilisés pour les pièces du jeu sont donc "a 1-stack", "a 2-stack", etc... Puisque c'est un peu lourd en français, je choisis d'enlever le mot "pile" et d'écrire "un 1", "un 2", etc au lieu de "une pile de 1", "une pile de 2", etc.

## Jouer un 1 au contact d'une pile adverse est souvent mauvais

Jouer un 1 au contact d'une pile ennemie est généralement mauvais, si ce 1 n'est pas une menace directe. Par exemple, dans le diagramme de gauche, Rouge vient de jouer E5. Blanc peut répondre en E6, attaquant E5 immédiatement, et Rouge n'a aucun moyen de sauver sa pile.

{{< columns >}}
![Diagram 1](1.png)
<--->
![Diagram 2](2.png)
{{< /columns >}}

Il faut se souvenir que _les 1 sont faibles au moment de leur placement_. Il est possible de les solidifier par la suite, en ajoutant des lignes de vues sur eux, mais initialement ils sont très vulnérables. Généralement, les piles de 2 ou plus sont meilleures pour les coups agressifs au contact (mais attention, les 2 peuvent aussi vite tomber si l'attaque n'est pas assez forte). Cependant, comme mentioné ci-dessus, cela ne veut pas dire qu'il ne faut jamais placer un 1 au contact. Si vous jouez un 1 au contact qui menace directement une capture par exemple, votre adversaire devra gérer la menace avant de pouvoir contre-attaquer (voir le diagramme ci-dessous, où Rouge joue E6).

{{<figure src="3.png" alt="Diagram 3">}}

La pile rouge en E6 attaque D5. Blanc n'a pas le temps de jouer D6 ou E5 pour attaquer E6, puisque dans ce cas Rouge pourrait simplement capturer D5. Donc pour Rouge, jouer cette pile de 1 en E6 est ici un bon coup.

## Faites attention aux piles "mortes" de votre adversaire

Lorsque la fin de partie arrive, il reste souvent quelques piles de l'adversaire isolées dans votre territoire, que vous pouvez capturer à tout moment. Cela peut avoir l'air lent de prendre le temps de les capturer, mais il est parfois crucial de s'en débarasser. Il ne faut pas sous-estimer les dégâts qu'elles peuvent faire. Cela vient des règles de Tumbleweed, qui font que _toute pile sur le plateau donne un certain nombre de coups possibles au joueur à qui elle appartient_. Cette idée est liée à l'importance des captures dans le jeu de Tumbleweed (contrairement par exemple au Go où il n'est en général pas nécéssaire d'enlever des pierres du plateau pour qu'elles soient considérées comme mortes). Capturer une pile réduit le nombre de coups que votre adversaire peut jouer! Regardons la position suivante, où une pierre qui n'a aucune chance de vivre peut être utilisée pour faire de gros dégâts.

{{< columns >}}
![Diagram 4](4.png)
<--->
![Diagram 5](5.png)
{{< /columns >}}

Après le coup de Blanc en K10, Rouge doit mettre un bouclier en J9, ou Blanc pourrait capturer I8 et créer une brèche dans le mur. Mais après ce bouclier de Rouge en J9, Blanc peut jouer H10 ou I10 pour une double attaque puissante.

{{<figure src="6.png" alt="Diagram 6">}}

## L'intersection de deux liens est un point crucial

Comme expliqué au début du document [Fundamental Shapes in Tumbleweed](/fundamental-shapes/#link), les liens sont les segments entre deux piles de la même couleur qui se voient (autrement dit, qui sont alignées). Les liens sont les "briques fondamentales" du jeu et doivent être au centre de votre stratégie. Le diagramme suivant montre un type de position où les débutants manquent souvent un coup important, quand l'un de leurs liens croise un lien adverse.

{{<figure src="7.png" alt="Diagram 7">}}

Les deux liens se croisent en D4. Le contrôle de ce point est urgent pour les deux joueurs. Une possibilité est de jouer directement un 2 en D4, une autre est de jouer en B2 ou en F6 pour ajouter une troisième ligne de vue sur D4 (et donc interdire ce coup à l'adversaire). Regardons un exemple de partie où ce thème apparaît dès les premiers coups ([Tumblebot](http://34.233.90.87:8000/api/analysis/site) contre lui-même), après 1. B2 G8 2. E5 G3 3. E9 B3.

{{<figure src="8.png" alt="Diagram 8">}}

Les hexagones C3 et E6 sont tous deux à l'intersection d'un lien rouge et un lien blanc, donc ce sont des coups à considérer pour les deux joueurs. Le raisonnement pour choisir lequel des deux coups est le mieux est un peu plus avancé. Mais pour résumer, E6 est plus au centre, et si Rouge jouait C3 et laissait Blanc jouer E6, Rouge pourrait être trop concentré sur le haut du plateau, le mettant dans une position défavorable. La suite de coups préconisée par Tumblebot depuis cette position est donc Rouge en E6, Blanc en C3.

## Renforcer est mauvais sauf s'il n'y a pas d'autre option

Renforcer une pile est généralement mauvais, sauf s'il n'y a aucun autre moyen de défendre une attaque et si vous ne voulez pas sacrifier la pile. Par exemple, dans l'ouverture suivante, la pile rouge en E5 est attaquée, et renforcer le 1 en un 2 serait mauvais. Renforcer défend contre l'attaque de Blanc, mais ne fait rien d'autre. C'est un coup très passif. Un bien meilleur coup pour Rouge est de jouer une parade en C5 comme dans le diagramme ci-dessous, ce qui défend E5 et ouvre de nouvelles lignes de vue, par exemple la ligne C5-I11 qui peut aider Rouge à se développer vers le bas. Cela ajoute aussi un défenseur sur l'hexagone C3, ce qui pourrait être utile si Blanc joue B3 par la suite.

{{< columns >}}
![Diagram 9](9.png)
<--->
![Diagram 10](10.png)
{{< /columns >}}

Une bonne règle pour savoir comment gérer les attaques: au lieu de renforcer un 1 en 2, il vaut mieux jouer une parade (ajouter une troisième ligne de vue sur le 1). Et avant de jouer un 2, essayez de vérifier que vous ne devrez pas le renforcer en un 3 bientôt, car ce n'est en général pas très efficace. En fin de partie cependant, il est normal de devoir renforcer des piles.

## L'équilibre du développement

Cette section est moins une erreur de débutant qu'un thème central du jeu de Tumbleweed (et un idée que l'on retrouve dans beaucoup de jeux abstraits, surtout les jeux territoriaux). En tant que joueur, vous essayez constamment de trouver le bon équilibre entre étendre votre territoire et le rendre plus solide. Chose intéressante, Tumbleweed a un bon indicateur pour mesurer cela: la hauteur d'une pile, puisque le nombre sur la pile que vous voulez placer indique par définition le nombre de lignes de vues que vous avez dessus. Par exemple, jouer un 4, un 5 ou un 6 n'est pas efficace du tout, puisque cet hexagone/case était déjà à l'intérieur de votre territoire de façon solide. Et cette pile ne vous ouvre pas beaucoup de nouvelles lignes de vue, pour développer votre influence sur le plateau.

Il faut décider, à chaque coup du jeu (mis à part les coups forcés), quelle est la manière de procéder. Est-ce que le 1 que vous voulez jouer est trop risqué ou est-ce juste un coup de développement rapide et efficace? Est-ce que jouer un 3 ailleurs serait lent et peu efficace, ou bien un coup solide qui sécuriserait votre position? La réponse dépend de l'état de la partie. Ce sont de bonnes questions à vous poser, et vous y répondrez de mieux en mieux en jouant plus à Tumbleweed.

## Préparez vos formes à l'avance

Pour la dernière section de ce guide, nous aborderons le sujet un peu plus avancé de la forme des groupes et plus précisément, des angles. Il y a beaucoup de subtilités et de cas particuliers, mais c'est un concept important à garder en tête pour mieux comprendre le "flot" du jeu.

Délimiter un territoire en ligne droite d'un bout à l'autre du plateau serait idéal, mais en général votre adversaire ne sera pas très coopératif. Par conséquent, vos zones d'influence auront des angles/coins. Si vous avez joué un certain nombre de parties, vous avez peut-être remarqué qu'un type d'angle est le plus commun: les angles obtus, qui sont plus efficaces que les angles aigus.

{{< columns >}}
![Diagram 11](11.png)
<--->
![Diagram 12](12.png)
{{< /columns >}}

Dans les deux diagrammes ci-dessus, sept piles sont dans la frontière rouge (sans compter le 1 en F7), mais l'angle obtus à gauche délimite du territoire rouge de manière beaucoup plus efficace que l'angle aigu à droite (autrement dit, il permet de faire plus de points). De plus, un hexagone sur un angle obtus comme le 3 en C4 peut être placé de manière très naturelle: Rouge a seulement besoin des lignes de vues C6-C5 et D4-G4 (qui sont présentes pour construire les murs) et d'une pile de support en F7. Tandis que le 4 rouge en D4, dans le diagramme de droite, ne peut pas être construit naturellement à partir de la forme de territoire que Rouge obtient à la fin (il faut utiliser des lignes de vue venant de l'extérieur du triangle rouge). Un angle obtus doit pouvoir être renforcé au moins en un 3 , et un angle aigu doit pouvoir être renforcé au moins en un 4. Il n'est pas toujours nécéssaire de jouer exactement sur les angles, il suffit de les contrôler en ayant assez de lignes de vue sur eux.

Ceci explique pourquoi il est en général préférable de jouer des angles obtus plutôt qu'aigus. Une autre idée très importante est que _les angles de votre forme sont des points clés_. Il ne vaut mieux pas les oublier pendant la partie, et c'est une bonne idée de décider à l'avance quels emplacements vous souhaitez utiliser pour vos angles. Bien sûr, il faudra souvent changer de plans suivant ce que votre adversaire fait, mais garder cela en mémoire permet de donner plus de structure à votre jeu.

La position suivante provient d'une partie entre testing_qwerty (Rouge) et komacchin (Blanc) ([lien vers la partie](https://tumbleweed.games/log/4160/15/)).


{{< columns >}}
![Diagram 13](13.png)
<--->
![Diagram 14](14.png)
{{< /columns >}}

Rouge vient de jouer en H4, attaquant le 1 blanc en H7. Et Blanc a répondu en H5, un bouclier qui protège H7 de l'attaque rouge. C'est un coup qui remplit aussi d'autres fonctions. D'abord, le coup de blanc en H5 ouvre de nouvelles lignes de vue pour Blanc le long de la ligne D1-K8. De plus, il met une troisième ligne de vue sur G5. Ainsi, si le prochain coup de Rouge est en G4 pour essayer de limiter l'accès de Blanc au haut du plateau, Blanc a un angle solide en G5 qui peut être renforcé en un 3.


