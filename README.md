# TP1_Analyse_Numrique
Dans le TP1 d'analyse numérique on étude la résolution d'une fonction f(x)=0. Au cours de ça, on utilise les trois méthodes pour chercher la valeur approcher à l'erreur.  1) La méthode de dichotomie: est une méthode pour trouver une solution approchée à une équation f(x)=0. Précisément, supposons que la fonction f est continue sur l'intervalle [a,b] avec f(a)≤0 et f(b)≥0. On sait donc qu'il existe au moins un réel c dans l'intervalle [a,b]tel que f(c)=0.   L'idée est alors d'évaluer ce que vaut f au milieu de [a,b], et de distinguer les deux cas suivants :  si f(a+2b)&lt;=0, alors on sait qu'on a une racine dans l'intervalle [a+2b,b].  sinon, f(a+2b)>0 et on sait qu'on a une racine dans l'intervalle [a,a+2b].  Ainsi, dans les deux cas, on a trouvé un intervalle de longueur moitié dans lequel est située une racine de l'équation f(x)=0. On recommence alors avec cet intervalle, et ainsi de suite jusqu'à ce qu'on trouve une approximation qui nous convienne.  2) La méthode de point fixe:   Soit E un ensemble et f : E->E une application. On dit que x est un point fixe de f si f(x)=x. Si l'application va de R dans R, cette propriété se traduit graphiquement par le fait que la courbe représentative de f et la première bissectrice du repère se coupent en le point (x,x).   3) La méthode de Newton:   Newton a proposé une méthode générale pour obtenir une telle approximation. L'idée est de remplacer la courbe représentative de la fonction par sa tangente. On part d'un point x0 de l'intervalle de définition de f, et on considère la tangente à la courbe représentative de f en (x0,f(x0)). Soit x1 l'abscisse de l'intersection de la tangente avec l'axe des abscisses. Puisque la tangente est proche de la courbe, on peut espérer que x1 donne une meilleure estimation d'une solution de l'équation f(x)=0 que x0.
Dans le TP2 d'analyse numérique, l'interpolation polynomiale est une technique d'interpolation d'une fonction par un polynome. Etant donnés une fonction f : [a,b]->R et N >= 1 un entier naturel. Soient x0,x1,...,xN (N+1) points deux à deux distincts dans [a,b]. Le but est de chercher à trouver un polynome p vérifiant le système suivant:
             f(xi) = p(xi), pour tout i = 0,1,...,N
             deg(p) <= N
Il y a deux formules qui étudent l'interpolation polynomiale:
* Formule de Lagrange
* Formule de Newton
             


TP1:
[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/Gada98/TP1_AnalyseNum-rique/main?labpath=TP1.ipynb)


TP2:
[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/Gada98/TP1_AnalyseNum-rique/main?labpath=TP2_analyse.ipynb)
