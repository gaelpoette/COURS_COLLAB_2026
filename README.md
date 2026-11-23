# COURS_COLLAB_REAC
Un petit code de cinétique chimique résolu par méthode MC volontairement imparfait mais que vous allez améliorer
# COURS_COLLAB_2026

TODO:
- [Mehdi] les pas de temps etc. dans param.py = bof bof
- [Lanusan] les len(?): remplacer par une variable qui contient la valeur 
- éviter les append si possible
- [Raphaël] devoir lire list_reac et list_type pour construire les réactions = bof bof: pour palier à ça => mettre la liste des réactions sous la forme e^-+Ar->B+C
- [Gael] test: qd vol >>1, la solution du code doit coincider avec la solution d'un jeu d'ode=> coder euler explicite dans une situation 'simple' et comparer les résultats des codes
- [Raphaël] unaire = pas du français
- [Mélanie] réaction 'unaire" avec solution analytique A->B+C
- solution analytique cas nonlinéaire? Si oui la mettre dans un cas test et se comparer
- [Sylvain] "ATTENTION! LES LISTES DOIVENT AVOIR LA MEME TAILLE!" on ne sait de quelles listes il s'agit
- [Roméo] h maj et H minuscule = bof bof
- [Jacques] on a des variables qui servent une fois, pour pas vraiment grand chose en termes d'apport (ex. de reac)
- [Valentin] structuration: encapsulation
   raisons: - test unitaire sur fct encapsulée
            - nom explicite
            - fichiers différents = moins de chance de générer des conflits
            - lecture du code (reconnaitre facilement les étapes)
            - moins de lignes par fichiers 
   la fonction init des particules
   la fonction tirage du temps de choc
   la fonction tirage de la reaction
- variables dont le nom = une seule lettre ou le nom n'est pas explicite
- ex: not(a==b) <==> a!=b etc. Eviter 12000 façons différentes de faire la même chose et qui génère des difficultés de lisibilité 
- [Mathis] beaucoup de variables qui servent pas vraiment (nmc qui est traitre car dans le nom de variables)
- [Mathias] plot avec matplotlib?  
- [Adrien] boucle "for cg ":
    -  4 if au même niveau  
    -  binaire et unaire , quid de A+B+C->Z: le code préviens que pas possible?
                                             veut-on la fonctionnalité? 
    - else pour +=0 ne sert à rien
- dictionnaire par des listes?
- 
