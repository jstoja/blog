

##Et pourtant...##

Mais depuis quelques mois, je ne me sens pas aussi productif que je pourrais l'être.

Mais alors, si le langage est fait pour les développeur et qu'un plus il est agrémenté de tout ce que j'ai besoin, pourquoi je ne suis pas aussi productif que je le voudrais ?

Pour une raison simple, les choix de son design.

Ruby a choisis une voie qui lui permet d'être un plaisir à utiliser, mais une de ses plus grande force, est pour moi sa plus grande faiblesse.

Ruby est un langage dit **dynamique** et faiblement typé. Ce qui veut dire qu'il ne vérifiera votre utilisation des variables que lorsque celle ci sera interprété.

Le problème est que vu qu'il n'y a pas de moyen de vérifier les éventuelles erreurs de ce type, nous devons faire des tests unitaires, nous garantissant le bon comportement de toutes les parties de notre code.

Avec un langage comme OCaml, Haskell, Go, Rust, ... J'en passe, votre code est analysé avant d'être exécuté, et vous évite ce genre d'erreurs.
De plus, vos tests auront maintenant comme but, non pas de tester vos erreurs, mais de vous aider à avancer vers la prochaine fonctionnalité de votre programme.

##Conclusion##

Certes les langages fortement typé ne sont pas aussi agréable à utiliser que Ruby mais nous nous rapprochons de ce que Ruby est avec d'autres langages comme Go ou OCaml, qui sont des langages qui sont plein de bon sens et très agréable à utiliser.
À cette heure ci, le premier problème qui se dresse est le manque de communauté. Mais nous voyons déjà des développeurs Ruby du monde entier se mettre à Go comme [katrina londonien](http://), Matt Aimoneti, Thibault barrière ou encore à Rust comme [Steeve B](http://).

Avez vous testé ces autres langages ? Qu'en avez vous pensé ?