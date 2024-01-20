Objectif : Résoudre le trillemme

![[1684927262092.png]]

Le soucis de **Ethereum** c'est la scalabilité **Eth 2.0** sers a cela , on avait avec le **POW** une seul blockchain qui permettait de valider **15 a 45 transactions par secondes** dorénavant on a **64 blockchain fragmenté**
 
Pour rendre Eth encore plus **scalable** on peut soit 
- augmenter la taille des block mais les ressources nécessaires à la validation d'un block rendrait le réseau moins décentralisé 
- Le sharding  ( fragmentation a 64 blockchain )


### Le sharding 

Pour ce faire on va implémenter des smarts-contracts sur le réseau eth qui vont surveiller les transactions qui vont venir désengorger le réseau eth sur les layers 2.

Les contrats vont surveiller les dépôts et retrait et également que les règles établis correspondent a celle de ETH 


#### Différents types de L2 

**States Channel**

On accumule les transactions pour venir les regrouper en une que l'on envoie sur le réseau en une fois mais pas compatible avec EVM.

**SideChain**

Compatible avec EVM mais pas la sécurité d'ETH (polygon) on a des validateurs qui diffère donc moins sécurisé , ça fonctionne avec un mécanisme de burn/mint qui permets de burn un eth sur ethereum et d'en mint un sur polygon quand j'en envoie un sur polygon.

**Plasma**

Mix entre SideChain et StateChannel, un plasma va profiter de la sécurité eth.


#### Les rollups

L'analogie est simple pour me rendre de Paris a Bordeaux si j'utilise le réseau eth c'est passé par les petites routes seul sur un scooter.

Si j'utilise un rollups c'est prendre un bus rapide qui consomme beaucoup mais les frais sont partagés entre chaque passager et qui va très vite 


On distingue **2 types de rollups** qui ce distingue par leur manière de valider les transactions que l'on amène au réseau eth 

**Optimistic Rollups** : Basé sur l'optimisme toute les transactions sont bonnes il y a un délais de 7 jours pour que quelqu'un viennent prouver que la transaction est fausse donc on a du délais.

**Zk Rollups** : 





