# Les Design Patterns expliqués aux non-développeurs (partie 3/3)


Voici la dernière partie sur les exemples d'utilisations de Design Patterns dans les logiciels que vous utilisez tous jours. ça a pour but d'expliquer les Design Patterns via des exemples à (presque) Monsieur Tout-le-Monde ;)

# La correction orthographique dans Outlook / Thunderbird (Strategy)

Avec un logiciel de mailing, on peut utiliser un correcteur d'orthographe dans la langue désirée. Jusqu'ici rien d’anormal. Le soucis est chaque langue est différente et possède ses propres règles spécifiques. Les équipes travaillant sur la version anglaise et française ne sont pas les mêmes en générale et on n'a pas de traducteur générique et paramétrable (je suis pas expert). L'idée est d'avoir la possibilité de changer d'algorithme à la volé (correction en anglais, correction en français, correction en chinois, ...) en utilisant le Design Pattern Strategy.

# La généricité des codecs vidéos dans Windows Media Player / VLC (Adapter)

Dans le monde des players vidéos, vous aurez sans doute remarquer qu'il existe une multitude de formats de fichier (MP4, Divx,WMV, ...). Le problème c'est qu'ils sont pas fait par la même société et sont trop différents pour fonctionner de la même manière. Du coup, comme un adaptateur de prise de courant 110v vers 220v, l'idée est d'avoir un adaptateur générique pour utiliser un format qui ne serait pas compatible avec le player. On a appel ce Design Pattern : Adapter.

#Traiter plusieurs fichiers comme un seul (Composite)

Sur votre PC ou Mac, vous pouvez déplacer/copier un répertoire contenant N fichiers comme si c'était qu'un seul fichier. Bein le fait de traiter plusieurs éléments comme un seul élément est le principe du Design Pattern Composite.

# Décorer une image sur une page Facebook (Decorator)

Sur une image sur un site comme Facebook, vous pouvez avoir pas mal informations ajoutées. On a : une image avec des rectangles de reconnaissance faciale, une image avec des commentaires, une image avec des "j'aimes", une image avec une description, ... Et on sait pas l'avance quelles nouvelles informations va être ajoutées dans le futur (Image + ???). C'est là que le Design Pattern Decorator (décorateur) intervient. Il permet d'ajouter de nouvelles fonctionnalités sans tout casser.


C'est la fin de ma première série d'articles que je mets sur LinkedIn. C'est très simplifié et ça s’adresse aux débutants.

J’espère que vous serez indulgent sur les fautes d'orthographes :)
