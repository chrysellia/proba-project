# proba-project
<!-- Package installé -->
pip install networkx matplotlib pandas scipy

On utilise networkx pour modéliser le graphe.

On suppose les durées estimées t_e comme temps d’exécution moyen de chaque tâche.

Le chemin critique correspond au plus long chemin du graphe (en termes de durée).

On suppose que la durée totale suit une loi normale (car il y a de nombreuses tâches).

Pour la probabilité, on utilise la loi normale centrée réduite (Z).

Q1 — Graphe du projet (PERT) :
les calculs de moyenne et écart-type à partir des valeurs optimiste, probable, pessimiste.
la construction du graphe (networkx.DiGraph)
l’affichage avec matplotlib.


