Introduction

Depuis 2014, on constate une multiplication de survols de zones sensibles par des drones. Ceci révèle par voie de conséquence que les drones sont de plus en plus présents dans l’espace aérien. Ces survols ont d’ailleurs mis en évidence les difficultés rencontrées par les services des États pour faire respecter les interdictions de vol. Les modes opératoires des drones, furtifs et télépilotés, rendent difficile la sanction des infractions. Ces survols sont porteurs de risques et de menaces. Ainsi, le survol de propriétés privées peut porter atteinte au droit au respect de la vie privée et le survol de zones urbaines peut nuire à la protection des personnes et des biens en cas de chute. L’utilisation des drones peut également menacer le transport aérien, les installations et les sites sensibles. La sécurité des personnes et la crédibilité des pouvoirs publics, des institutions ou des entreprises peuvent être engagées et menacées. Heureusement, les forces de l’ordre peuvent procéder à la neutralisation des drones par différents moyens pour faire cesser ces usages illicites dangereux, parfois malveillants. Plusieurs sociétés ont mis au point des technologies permettant de détecter la communication entre un drone et sa télécommande pour remonter jusqu’aux télépilotes et, le droit des pays s'adapte, afin d’identifier les auteurs de ces survols illicites.



Notre problématique

Le marché des drones (véhicules aériens sans pilote) grand public a connu une croissance importante au cours des dernières années. Malgré son énorme potentiel pour stimuler la croissance économique en soutenant diverses applications, l'augmentation des drones grand public présente des risques potentiels pour la sécurité publique et la vie privée. Pour minimiser ces risques, il est urgent de détecter et d'identifier efficacement les drones envahisseurs. Étant donné que les drones grand public sont généralement utilisés dans un environnement civil, les méthodes de détection physique existantes (telles que le radar, la vision et le son) peuvent devenir inefficaces dans de nombreux scénarios. Pour éviter ces problèmes, les enregistrements de données cryptées du trafic WiFi des drones peuvent être une source très prometteuse pour détecter les intrus. Par conséquent, pour la détection de drones intrus, chaque entrée est un enregistrement de trafic WiFi crypté que nous surveillons, tandis que la sortie est de savoir si le trafic actuel provient d'un drone ou non. Cependant, en plus de la précision, le temps d'exécution de la prédiction de la méthode de détection est également très important car les drones intrus volent à des dizaines de mètres par seconde et il est important d'obtenir la prédiction aussi vite que possible. Par conséquent, nous devrons optimiser conjointement la précision et le temps d'exécution de la prédiction. Par conséquent, l'élagage et la simplification du modèle sont très importants.


PB1: Reconnaître un drone via les flux wifi récoltés.

PB2: Déterminer la marque du drone.
 
 
 
Présentation des datasets

Pour les enregistrements du trafic WiFi de chaque type de drone, nous considérons deux types de modes : 1) Le mode de flux bidirectionnel. Ici, on considère i) le flux montant, ii) le flux descendant, et iii) le flux total du trafic. Pour chaque type de flux, la taille des paquets et le temps d'inter-arrivée des paquets sont les sources de données brutes. Pour chaque source, 9 mesures statistiques ont été calculées. Nous bénéficions d'un dataset d'entrainement avec les labels nous informant de l'origine du flux wifi (drone ou pas) et nous avons ajouté le label correspondant à la marque du drone.
