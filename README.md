# L2StructureDiscreteTP1

L2 Informatique, Université d'Aix-Marseille.

Embryon pour le TP1 du cours Structures Discrètes


# utilisation de gnuplot

Exemple de script à utiliser au début.

```gnuplot
plot 'divideNative.dat' using 1:2 with lines title "native time",\
     'divideNative.dat' using 1:3 with lines axis x1y2 title "native operations"

pause mouse

```

Explications succintes (voir la documentation pour plus de détails) :

- `using 1:3` : les données des colonnes 1 et 3 sont utilisées pour coordonnées x et y respectivement.
- `with lines` : connecte les points du graphe par des segments.
- `title "native time"` : ajoute la légende de cette courbe.
- `axis x1y2` utilise l'axe horizontal du bas (`x1`) et l'axe vertical de droite (`y2`), utile pour afficher deux courbes dont les valeurs n'ont pas le même ordre de grandeur.
- `pause mouse` : affiche le graphique et attend le prochain clic pour terminer.

