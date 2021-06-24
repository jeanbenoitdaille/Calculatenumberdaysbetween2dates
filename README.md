# Calculatenumberdaysbetween2dates
Calculer le nombre de jours entre deux dates 
Ici, on veut calculer le nombre de jours entre deux dates. Pas besoin de se compliquer la vie avec des calculs compliqués puisque Python nous fournit le module datetime qui permet justement de faire des calculs avec des dates.

À la première ligne, on importe la classe date depuis le module datetime :

    from datetime import date

On créé deux instances à partir de la classe date avec deux dates différentes (2014/07/02 et 2018/07/11).

On peut ensuite récupérer ce qu'on appelle un delta tout simplement en soustrayant les 2 dates :

    delta = l_date - f_date

L'objet delta récupéré contient une propriété "days" qui permet de récupérer le nombre de jours entre les deux dates que l'on a soustrait :

    >>> print(delta.days)
    1470

Il y a donc 1470 jours entre 2014/07/02 et 2018/07/11
