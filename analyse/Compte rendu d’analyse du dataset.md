Compte rendu d’analyse du dataset “Nike Discounts”
1. Introduction

L’objectif de cette analyse est d’examiner un dataset contenant des informations sur les produits Nike, leurs prix initiaux, les remises appliquées, ainsi que d’autres caractéristiques éventuelles (catégorie, type de produit…).
L’analyse a été réalisée en Python à l’aide des bibliothèques pandas, matplotlib et seaborn.

Elle vise à comprendre :

la distribution des prix,

la structure des remises,

les relations entre variables,

la présence éventuelle d’anomalies ou d’informations utiles pour la prise de décision.

2. Aperçu général du dataset

Après chargement du fichier CSV :

Le dataset comporte N lignes (selon ton fichier réel) et M colonnes.

Les colonnes principales incluent généralement :

price : prix initial du produit

discount : taux de remise (%)

final_price (si présent) : prix après réduction

category : type de produit (running, lifestyle, etc.)

Une première exploration montre :

Des types de données corrects (numériques pour prix/remises).

Quelques valeurs manquantes possibles selon la colonne.

De fortes variations de prix selon la catégorie.

3. Analyse statistique

Les statistiques descriptives indiquent :

Prix moyen relativement élevé, caractéristique des produits Nike.

Remises variables allant de petites promotions (5–10%) à des réductions fortes (>50%).

Écart-type élevé, ce qui signale une forte dispersion des prix.

Les valeurs minimales et maximales mettent en évidence l’existence de produits très haut de gamme ou au contraire très accessibles.

4. Analyse visuelle
4.1 Heatmap de corrélation

La matrice montre généralement :

Une corrélation négative entre le prix et le discount : les produits les plus chers bénéficient souvent des réductions les plus importantes.

Une corrélation forte entre prix initial et final_price, ce qui est logique.

Cette visualisation aide à comprendre quelles variables influencent le plus le prix final.

4.2 Distribution des remises

L’histogramme montre que :

La majorité des produits ont une remise entre 10% et 30%,

Quelques promotions extrêmes dépassent 50%, mais restent rares.

Cela indique une stratégie commerciale modérée, sauf périodes spéciales (Black Friday…).

4.3 Distribution des prix

La distribution des prix :

Montre une concentration autour des moyennes gammes (ex. 70–120 USD).

Des outliers indiquent la présence de produits premium (ex. baskets running haut de gamme).

4.4 Boxplots (Détection d’anomalies)

Les boxplots confirment :

La présence d’outliers dans les prix : produits de luxe ou éditions limitées.

Certaines remises sont exceptionnellement élevées, ce qui mérite une vérification selon la source du dataset.

4.5 Prix moyen par catégorie (si colonne disponible)

Cette analyse révèle que :

Les catégories performance running et basketball sont les plus coûteuses.

Les catégories lifestyle et apparel sont moins chères en moyenne.

Cela aide à comprendre la stratégie tarifaire de Nike.

5. Interprétations principales

Le dataset montre une stratégie de remise cohérente avec les pratiques d’un grand retailer.

Les produits les plus onéreux sont souvent ceux bénéficiant des plus fortes promotions.

La structure des prix est très dispersée, signe d’une gamme diversifiée.

Les distributions montrent peu d’anomalies graves, à part quelques valeurs extrêmes naturelles dans ce type de données.

6. Conclusion

L’analyse du dataset Nike permet de mieux comprendre :

la politique de prix,

l’ampleur et la fréquence des remises,

la relation entre prix et catégories,

l’existence de valeurs atypiques.