Fables Informatiques
====================

Les Fables Informatiques sont un recueil collectif de fables dont la morale
traite de l'informatique, ou d'un sujet apparenté.

Quel est le but ?
-----------------

Ces fables ont avant tout un but divertissant : il faut que leur lecture
soit agréable, voire amusante. Elles doivent aussi avoir une morale ayant
un rapport avec l'informatique.

Commencez par lire [l'article Wikipedia](http://fr.wikipedia.org/wiki/Fable)
sur les fables, et relisez
[celles de La Fontaine](http://www.lesfables.fr/).

Comment proposer une nouvelle fable ?
-------------------------------------

L'écriture est ouverte à tous. Si vous souhaitez écrire et proposer une
nouvelle fable, il vous suffit de :

* forker le dépôt (bouton `Fork` en haut à droite);
* dans votre fork, d'ajouter un nouveau fichier contenant le texte de votre
  fable;
* ne pas oublier de faire un `commit` et un `push`;
* et bien entendu, de nous envoyer une `pull request`, afin que nous
  ajoutions votre contribution !

Si vous ne souhaitez pas écrire, mais avez l'idée d'une fable, utilisez le
système d'[issues](https://github.com/fables-informatiques/fables/issues).
Il vous permet aussi de commenter les fables existantes afin de les
améliorer.

Y a-t-il des contraintes à respecter ?
--------------------------------------

La première contrainte, et la plus importante, est que votre fable doit être
écrite par vous-même. Pour être intégrée au recueil, vous devez aussi
accepter qu'elle soit diffusée sous la
[licence du recueil (CC-BY-SA)](LICENSE).
Le mécanisme de soumission utilisé permet de conserver l'historique de
ce que chacun écrit, en utilisant les informations des commits. Vous serez
donc évidemment crédité pour votre travail.

La seconde contrainte est que votre fable doit être écrite en utilisant
une syntaxe [Markdown](http://fr.wikipedia.org/wiki/Markdown).
Le titre de la fable doit être présenté comme titre de niveau 1.

La troisième contrainte est plus souple. Si possible, écrivez en vers.
Si vous ne le souhaitez pas, ou ne pouvez pas, nous acceptons aussi les
fables en prose.

Comment construire un document avec toutes les fables ?
-------------------------------------------------------

Il vous suffit de lancer la commande `./construire`. Elle construit le
recueil sous différents formats : PDF, epub, ...
Nous utilisons l'outil [pandoc](http://johnmacfarlane.net/pandoc/)
pour créer ces documents. Veillez à l'installer !
