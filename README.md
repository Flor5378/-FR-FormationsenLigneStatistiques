# Section Data & Humanités Digitales  
**Sciences-Po Saint-Germain-en-Laye**  
**CY Tech**  

## Regard sur les plateformes de MOOCS : le poids de l’HDI et du Genre dans l’Investissement des Apprenants  
*Florian Grolleau 3A-DD*  
*Sous la supervision de : Matthieu Cisel (Ph.D)*  
*Janvier 2025*

---

## Résumé  
Cette étude analyse l’impact du genre et de l’indice de développement humain (HDI) sur l’engagement des apprenants dans un MOOC nommé *MOOC Effectuation*. Nous mesurons l’investissement par le nombre de vidéos regardées et les quiz complétés.

Les résultats montrent que l’HDI du pays d’origine est un facteur clé influençant fortement la complétion du cours : les apprenants des pays à HDI élevé regardent nettement plus de vidéos et ont un taux de réussite supérieur. En revanche, l’effet du genre est faible et n’explique que peu les différences d’investissement.

L’étude souligne ainsi des inégalités d’accès et de réussite liées au contexte socio-économique des apprenants, tandis que le genre, bien que statistiquement présent, joue un rôle moins important.

---

## Méthodologie  
- Analyse statistique menée avec RStudio.  
- Données issues du MOOC *MOOC Effectuation*.  
- Tests utilisés : Student, Chi2, ANOVA, régression logistique.

## Exemple de résultats, en utilisant R:

Le forest plot ci-dessous illustre l’impact de différentes variables (HDI et genre) sur les chances de complétion des formations en ligne. Un odds ratio supérieur à 1 indique une probabilité accrue de complétion par rapport à la catégorie de référence, tandis qu’un intervalle de confiance recoupant la ligne de référence (OR = 1) traduit l’absence d’effet significatif. Par exemple, si HDI (I) a un OR ≈ 1,12, ça veut dire que: les apprenants venant de pays avec un HDI intermédiaire ont environ 12 % plus de chances de compléter la formation que ceux de la catégorie de référence, toutes choses égales par ailleurs.

---

<img width="700" height="432" alt="Image" src="https://github.com/user-attachments/assets/24ecdf75-1e56-4c30-8e20-c440ab7ce3b0" />

---

## Conclusion  
L’indice de développement humain est un facteur déterminant de l’investissement dans les MOOC, révélant des inégalités d’accès liées aux conditions socio-économiques des apprenants. Le genre, quant à lui, a un impact limité dans ce contexte. Ces résultats invitent à réfléchir sur l’accessibilité et l’adaptation des formations en ligne à des publics diversifiés.

---

## Contact  
Florian Grolleau – 3A-DD, Sciences-Po Saint-Germain-en-Laye  
Email : [f.grolleau@netc.fr]
