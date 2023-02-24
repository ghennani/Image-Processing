# traitement-d-image
the language that i used is python
the file of EXO2_TI contain a code of stretched image
the file of EXO3 contain a code equalized image
the file of EXO2ET3_TI contain a code of the two last method with a diffrent implementation 
and contain more detail 
Exercice 2 : 
Problème: on veut effectuer un étirement d’histogramme 
Solution: voici les étapes :
1.Lire l'image :  en utilisant OpenCV 
2.Construire l'histogramme : L'histogramme de l'image est construit en comptant le nombre de pixels ayant une intensité de chaque niveau de gris. Cela peut être fait en utilisant la fonction d'histogramme de la bibliothèque utilisée.
3.Trouver le min et le max : Le minimum et le maximum de l'intensité de l'image peuvent être trouvés en parcourant tous les pixels de l'image et en trouvant les valeurs minimum et maximum.
4.Étirement de l'histogramme 
5.Sauvegarder la nouvelle image : utilisant  imwrite
6.Mesure du contraste : La mesure du contraste peut être réalisée en utilisant deux méthodes : la mesure de Michelson et la mesure RMS.
  
Code :https://colab.research.google.com/drive/1IQ2T-771f-vUnXBKbEIb_16e49fxBZ70#scrollTo=bej8w2_n6eOQ 


Commentaires : 

- L'égalisation d'histogramme augmente le contraste de l'image. Cependant, elle peut également avoir des inconvénients, tels que la surexposition de certaines parties de l'image et la perte de détails dans les zones de faible contraste.

Conclusion :
L'égalisation d'une image est une technique de traitement d'images qui permet     d'optimiser la répartition des niveaux de gris dans l'image.
Elle consiste à transformer l'histogramme de l'image originale en un histogramme plus uniforme, c'est-à-dire en répartissant les niveaux de gris de manière équitable.
Exercice 3 : 
 
Problème: on veut effectuer une égalisation d’histogramme pour une image en niveaux de gris.
 
Solution: La solution consiste à :
1) calculer l'histogramme de l'image originale.
2) calcule des histogrammes cumulées (le cumul de cet histogramme),
3) Normaliser le cumul pour obtenir la nouvelle intensité de chaque pixel de l'image. 
4) Appliquer cette nouvelle intensité à chaque pixel pour obtenir l'image égalisée. 
 Code : https://colab.research.google.com/drive/1Cl4O0FFONg5JgbGxq7FMOgqNC1FyFWnC#scrollTo=U6xNLwH2C34-
Commentaires :
L'effet de l'égalisation de l'histogramme d'une image est d'augmenter le contraste global de l'image, en répartissant les niveaux de gris plus uniformément sur l'ensemble de l'histogramme. Cela peut rendre l'image plus nette et plus claire, avec des détails plus visibles dans les zones sombres et claires de l'image.
conclusion: 
L'égalisation d'histogramme est une technique de traitement d'image qui permet de répartir uniformément les niveaux de gris d'une image, en modifiant son histogramme pour améliorer son contraste. Elle consiste à appliquer une transformation non linéaire à l'image, de manière à obtenir un histogramme qui soit uniforme, c'est-à-dire où chaque niveau de gris apparait le même nombre de fois. 

De plus : Voici le lien d’un code détailler d’exercice2+3 avec un affichage détailler
https://colab.research.google.com/drive/1ZH4HojWV0fPhO3e4mU3xIfhO7IkhAgjP#scrollTo=_cfhXTl0Sv1l
