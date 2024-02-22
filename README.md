# Projet Tableau "Analyse de l'activite d'une entreprise specialisee dans la vente d'articles de sport"

## Synthèse


1. Situation actuelle :
    Le reporting  sur le ventes est la consolidation manuelle de fichiers Excel, de données issues de divers fichiers et des 3 systèmes opérationnels.  Les utilisateurs de reporting sont:  la direction des finances et  la direction client (DF et DCL) .

2. Besoins:
    Mettre en place un système de reporting pérenne et évolutif  (souple) à destination des différents métiers.
  La  premier étape consiste en  la réalisation de suivi des ventes ‘vacances et de l’activité’. 

3. Source de données:
    Systèmes opérationnels (CRM, Annuaire produits/Référentiel Produits,…).  
Consiste en:
- Les données de référence : données clients, données produits, axe temps, …
- Les données de production (ou de fait) :  les données de ventes enregistrées par le système source SURF.

4. Les prestations attendues pour la mise en œuvre de la solution:
La conception et la réalisation de l’architecture fonctionnelle et technique; Les tests unitaires et d'intégration;  La documentation et  cahier de recette; La conception et réalisation des autorisations et d'une partie des requêtes par l'équipe projet;  Le transfert de compétences et formation; L’assistance durant VABF, du démarrage, et durant les phases de vérification au service régulier, technique complémentaire.

5. Planning d'exécution : 6 mois
    - Lancement du projet :  01/07/2018 premier
- Production :  02/01/2019 deux


## Présentation d’analyse d’activité

A partir de  Dashboard d’overview des ventes qui j'ai réalisé,  je souhaite vous présenter l'analyse d’activité  SPORT-UP, l’entreprise spécialisée dans les articles de sport.

Tout d'abord je voudrais préciser que j'ai modifier la modèle de données que vous avez proposé, à savoir, j'ai changé la jointure en fusion. Parce que les jointures créent des données en double. 
Et aussi a cause de valeurs manquent dans les BusinessEntityID  d’onglet  SalesOrderHeader et le TerritoryID
 d’onglet SalesPerson  il y a des informations incorrectes.

1. A partir du premier graphique ( l’évolution des ventes) , on peut voir que le volume des ventes est en croissance constante, le saut (croissance) a été particulièrement important en 2012. Je note que les données de ventes de 2014 ne comprennent que 6 mois. Et ici, au cours des 6 derniers mois, nous voyons une croissance et prévoyons une tendance à la croissance pour les 6 prochains mois.
on peut également voir qu’il y a une tendance à la croissance en 6 mois par rapport aux années précédentes.

2. En termes de ventes par produit et par pays, le plus haut niveau de ventes de nos produits se situe aux États-Unis, en Espagne, en Angleterre et en Inde . 
Concernent les catégories, les vélos représentent une part légèrement plus importante du volume total des ventes , puis le volume des ventes est presque proportionnellement réparti entre les vêtements et les composants selon les pays.

3. Si on compare les évolution des ventes en montants versus quantité on constate un écart en 2011 et 2012 . Cela peut être du à la vente de produits plus chers au début de l’activité de l’entreprise. Puis d’autres catégories de produits ont été ajoutées, moins chères.

4. En ce qui concerne les ventes par catégorie et par continent, l’Europe occupe la première place, suivie de l’Asie et de l’Amérique du Nord. 

5. Si vous regardez des informations plus détaillée sur la vente de vélos en Europe, les plus vendus en Allemagne et en Espagne. Malgré le fait que l’activité en Espagne a commencé plus tôt, en 2011, l’Allemagne l’a dépassé en termes de ventes.

6. On a aussi une analyse plus détaillée des ventes par sous-catégories. Les vélos de route sont en première place dans la catégorie vélo ,  dans la catégorie des accessoires c'est les casques (helmets).

7. Dans les graphiques suivants, nous pouvons voir les  Indicateurs sur des articles à plus d’un million d’euros de CA.
Notamment la différence  en % du totale des ventes par article et des quantité vendu par article.

8. Le graphique suivant nous montre l’analyse des ventes par commerciaux  et pays . En raison de valeurs manquantes, il existe des informations incorrectes. C’est une informations pour tout la période depuis le début de l’activité. Carson (Central North Amer)), Prakit (India) , Moreno ( Spailn), Radclife (Angleterre) ont les plus gros volume de ventes. 

9. L’objectif des ventes annuelles des commerciaux est 250 000 . et pour l’India, le Portugal et la Chine 300 000, ce qui est nettement inférieur aux résultats des ventes.

10. Les volumes de commandes des Top 20 clients sont de 679 000 à 990 000 

11. Concernant les tailles les plus populaire ce sont le 44, puis le 48 et le 40.
