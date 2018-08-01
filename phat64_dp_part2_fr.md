# Les Design Patterns expliqués aux non-développeurs (partie 2/3)

Après avoir fait une présentation rapide de ce que sont les Design Patterns. Voici la première partie de quelques exemples d'utilisation des Design Patterns dans les logiciels grand publique. (J'ai pas dit que c'est forcement fait avec des Design Patterns mais il y a de grande chance que ça soit le cas.)

# La fonctionnalité CTRL-Z de Word ou OpenOffice (Memento)

Lors que vous voulez revenir en arrière dans votre logiciel de traitement de texte favori, votre programme a besoin de sauvegarder les états précédents des informations saisies. C'est là que le Design Pattern Memento devient utile pour les développeurs.

# Les calculs rapides sous Excel (Observer)

Lorsqu’on utilise un logiciel comme Excel ça arrive d'avoir besoin de travailler sur un document avec 10000 ou 100000 cellules/cases (voir plus sur des gros projet). Dans les années 80-90, les PCs/Mac étaient peu puissant pour pouvoir recalculer toutes les cellules lors qu'on en modifiait seulement une. La solution pour résoudre ce problème de performance est d'utiliser le Design Pattern Observer. En gros, il permet de recevoir la notification d'une modification effectuée à celui qui observe la cellule. Du coup, les cellules qui dépendent/observent la cellules modifiée sont seulement mise-à-jour et ainsi de suite pour la cellule qui observe une cellule qui observe une cellule. Bref, plus besoin de devoir mettre tout à jour et d'avoir son PC qui rame.

# La lecture de plusieurs formats de fichier comme Paint ou PhotoShop (Factory)

Lors de l'ouverture d'un fichier image dans votre logiciel de CAO, au lieu d'avoir un(e) bouton/fonction différent(e) pour ouvrir différents formats d'image (BMP, JPEG, PNG, TGA, ...), vous pouvez lire tous les formats en passant par la même fonctionnalité (même bouton). C'est la même fonction qui permet lire une image de n'importe quels formats. Ici, c'est le Design Pattern Factory qui permet ça.

# La gestion des boutons dans une page Web dans Chrome / Edge / Firefox (Command)

Lorsque vous voulez passer d'une page web à une autre vous utilisez des boutons ou des liens. En gros, c'est le Design Pattern Command qui permet d'attacher une action à un bouton ou à un élément graphique tout simplement. Pratique non ?





Dans le prochaine article, je parlerai de manière (plus technique) de Design Patterns comme l'Adapter, le Strategy, le Composite et Decorator.
