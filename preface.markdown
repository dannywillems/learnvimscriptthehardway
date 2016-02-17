Preface
=======

Les développeurs concrétisent leurs idées en texte.

Ce texte est transformé en nombre et ces nombres en autres nombres et *font
bouger les choses !*

En tant que développeurs, on utilise les éditeurs de texte pour développer nos
idées et créer ce qu'on appelle des "programmes". Les développeurs à plein temps
passeront des dizaines de milliers d'heures de leur vie dans leur éditeur de
texte, durant lesquelles ils feront différentes choses:

* Extraire de leur cerveau du texte brut pour les sauvegarder sur leur
  ordinateur.
* Corriger des erreurs dans ce texte.
* Restructurer le texte pour formuler un problème d'une manière différente.
* Documenter comment et pourquoi cette chose est faite de cette manière.
* Communiquer avec d'autres développeurs à propos de toutes ces choses.


Vim est incroyablement puissant, mais ce n'est pas totalement évident tant que
vous n'avez pas pris le temps de l'améliorer pour votre travail, vos habitudes,
vos droits.
Ce livre introduira Vimscript, le principal langage de programmation utiliser
pour améliorer et customiser Vim. Vous serez capable de modeler Vim en un
éditeur de texte entièrement personnel, à votre gout et vous pourrez passer le
reste de votre temps à utiliser Vim de manière plus effiace

Durant tout ce livre, je mentionnerai des choses qui n'ont strictement rien à
vous avec Vimscript mais qui vous serviront à apprendre plus sur Vim et être
plus efficace dans votre éditeur. Vimscript isn't
going to help you much if you wind up fiddling with your editor all day instead
of working, so it's important to strike a balance.

Le style de ce livre est un peu différent de la plupart des autres livres sur
les langages de programmation. A la place de simplement présenter les faits et
comment Vimscript fonctionne, il va vous inciter à taper les commandes pour
voir ce qu'elles font.

Parfois, le livre vous conduira dans des impasses avant d'expliquer la "bonne
manière". La plupart des autres livres ne font pas ça ou mentionnent les
problèmes *après* vous avoir montré la solution. Ce n'est pas comme ça que ça se
passe dans la vie réelle.  Often you'll be writing a quick piece of
Vimscript and run into a quirk of the language that you'll need to figure out.
En utilisant cette méthode dans le livre à la place de vous donner une simple
explication, j'espère que vous serez capable de comprendre les particularités de
Vimscript et que vous serez capable de résoudre vous mêmes les cas spécifiques.
La pratique rend parfait.

Chaque chapitre de ce livre est centré sur un seul sujet. Ils sont courts mais
contiennent beaucoup d'information, donc ne faites pas que les parcourir. Si
vous voulez vraiment comprendre et appréhender tout le contenu de ce livre, vous
devez tester en tapant chaque commande. Vous pouvez déjà être un développeur
expérimenté qui a l'habitude de lire et comprendre du code. Si c'est le cas:
cela importe peu. Apprendre Vim et Vimscript est une expérience différente
d'apprendre un langage de programmation normal.

Vous devez **tester en tapant *toutes* les commandes.**

Vous devez **réaliser *tous* les exercices.**

Voici deux raisons pourquoi c'est si important. Premièrement, Vimscript est
vieux et a beaucoup de points bizarres et sensibles. Une option de configuration
peut changer entièrement comment le langage fonctionne. En testant *tout* dans
*toutes* les leçons et en faisant *tous* les exercices vous découvrez des
problèmes sur des simples commandes de votre propre vim ou votre configuration
dont les solutions seront faciles à trouver et à implémenter.

Deuxièmement, Vimscript *est* Vim. Pour sauvegarder un fichier dans Vim, vous
tapez `:write` (or `:w` en simplifié) et appuyer sur retour. Pour sauvegarder un
fichier dans un script Vimscript, vous utilisez `write`. La plupart des
commandes Vimscript que vous apprendrez pourront tout aussi bien être utilisées dans vos
éditions quotidiennes, mais elles vous seront utiles seulement si vous les avez
bien mémorisées, ce qui nécessite également de pratiquer, et non seulement lire.

J'espère que vous trouverez ce livre utile. Il *n'est pas* conçu pour être un
guide complet à Vimscript et pouvoir développer rapidement de longs scripts.
Cela signifie que vous devez être assez à l'aise avec le langage pour modeler
Vim à votre gout, écrire des plugins pour d'autres utilisateurs, lire le code
d'autres personnes (avec des aller-retours réguliers à `:help`), et reconnaitre
la plupart des erreurs courantes.

Bonne chance !
