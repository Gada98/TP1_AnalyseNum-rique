# TP_Analyse_Numrique
Dans le TP1 d'analyse numérique, on étude la résolution d'une fonction f(x)=0. Au cours de ça, on utilise les trois méthodes pour chercher la valeur approcher à l'erreur. 

1) La méthode de dichotomie: est une méthode pour trouver une solution approchée à une équation f(x)=0. Précisément, supposons que la fonction f est continue sur l'intervalle [a,b] avec f(a)≤0 et f(b)≥0. On sait donc qu'il existe au moins un réel c dans l'intervalle [a,b]tel que f(c)=0.   L'idée est alors d'évaluer ce que vaut f au milieu de [a,b], et de distinguer les deux cas suivants :  si f(a+2b)&lt;=0, alors on sait qu'on a une racine dans l'intervalle [a+2b,b].  sinon, f(a+2b)>0 et on sait qu'on a une racine dans l'intervalle [a,a+2b].  Ainsi, dans les deux cas, on a trouvé un intervalle de longueur moitié dans lequel est située une racine de l'équation f(x)=0. On recommence alors avec cet intervalle, et ainsi de suite jusqu'à ce qu'on trouve une approximation qui nous convienne. 

2) La méthode de point fixe:   Soit E un ensemble et f : E->E une application. On dit que x est un point fixe de f si f(x)=x. Si l'application va de R dans R, cette propriété se traduit graphiquement par le fait que la courbe représentative de f et la première bissectrice du repère se coupent en le point (x,x).  

3) La méthode de Newton:   Newton a proposé une méthode générale pour obtenir une telle approximation. L'idée est de remplacer la courbe représentative de la fonction par sa tangente. On part d'un point x0 de l'intervalle de définition de f, et on considère la tangente à la courbe représentative de f en (x0,f(x0)). Soit x1 l'abscisse de l'intersection de la tangente avec l'axe des abscisses. Puisque la tangente est proche de la courbe, on peut espérer que x1 donne une meilleure estimation d'une solution de l'équation f(x)=0 que x0.

https://github.com/Gada98/TP1_AnalyseNum-rique/blob/main/TP1.ipynb

Dans le TP2 d'analyse numérique,l'interpolation polynomiale est une technique d'interpolation d'une fonction par un polynome. Etant donnés une fonction f : [a,b]->R et N >= 1 un entier naturel. Soient x0,x1,...,xN (N+1) points deux à deux distincts dans [a,b]. Le but est de chercher à trouver un polynome p vérifiant le système suivant:
             f(xi) = p(xi), pour tout i = 0,1,...,N
             deg(p) <= N
Il y a deux formules qui étudent l'interpolation polynomiale:
* Formule de Lagrange
* Formule de Newton


Dans le TP3, l'intégration est un des problèmes les plus importants que l'on rencontre en analyse. En effet, on rencontre souvent des intégrales dont le calcul par des méthodes analytiques est très compliqué ou meme impossible. Dans ce cas, on peut appliquer des méthodes numériques pour évaluer la valeur de l'intégrale données:

* Méthode des rectangles:
Cette méthode utilise le polynôme de degré le plus bas à savoir le polynôme constant. Cette intégrale numérique nécessite une unique évaluation de la fonction f (en x0 = a) et représente donc ce qu’on peut faire de plus rapide. L’erreur peut être estimée en utilisant les développements en série de Taylor ou le théorème des accroissements finis.
l
* Méthode du point milieu:
Cette méthode utilise également le polynôme constant pour approximer la fonction f. Cependant, elle exploite mieux les symétries du problème en choisissant la valeur milieu. Cette méthode nécessite une unique évaluation de la fonction f (en x0 = (a + b)/2) et correspond donc aussi à ce qu’on peut faire de plus rapide.
L’erreur peut être estimée en utilisant les développements en série de Taylor, ou le théorème des accroissements finis.

* Méthode des trapèzes:
Cette méthode nécessite deux évaluations de la fonction f (en a et en b). Elle est donc en gros deux fois plus lente que les méthodes précédentes.
L’erreur peut être estimée en utilisant les développements en série de Taylor, ou le théorème des accroissements finis.

* Méthode de simpson:
Cette méthode nécessite trois évaluations de la fonction f (en x0 = a, x1 = (a + b)/2 et x2 = b). Elle est donc en gros 3 fois plus lente que les méthodes à 1 point.
L’erreur peut être estimée en utilisant les développements en série de Taylor, ou le théorème des accroissements finis.
             






[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/Gada98/TP1_AnalyseNum-rique/main)
