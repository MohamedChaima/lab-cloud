# 1.
Qu'est-ce qu'une instance Virtual Machine ?
Une machine virtuelle est un fichier informatique, qui se comporte comme un ordinateur réel (un ordinateur virtuel créé à l’intérieur d’un ordinateur). Elle s’exécute dans une fenêtre, comme un programme.
# 2.
Qu'est-ce qu'un VNET ?
VNET (virtual network) est un réseau physique dans le cloud utilisé par les entreprises. Il permet au réseau des centre de données de fournir une structure de réseau appropriée, performante et sécurisé pour les applications qu’il héberge.
# 3.
A quoi sert un NSG ?
Un NSG (Network Security Group) correspond aux matrices de flux. Il s’agit d’un pare-feu logiciel sur plusieurs éléments comme (Cartes réseaux/serveurs, Base de données, Passerelle VPN, Sous réseau, Tag/balise). 
# 4.
Quelles sont les 5 propriétés désirables du cloud ?
-Accès aux services par l’utilisateur à la demande : la mise en œuvre des systèmes est entièrement automatisée, c’est l’utilisateur qui met en place et gère la configuration à distance.
-Accès réseau large bande : centres de traitement généralement raccordés directement sur le backbone Internet pour bénéficier d’une excellente connectivité. 
-Réservoir de ressources (non localisées) : La plupart des centres comportent énormément de serveurs et de moyens de stockage pour permettre des montées en charge rapides. Il est souvent possible de choisir une zone géographique pour rapprocher les données des utilisateurs.
-Redimensionnement rapide (élasticité) : La mise en ligne d’une nouvelle instance d’un serveur est réalisée en quelques minutes, l’arrêt et le redémarrage en quelques secondes. Toutes ces opérations peuvent s’effectuer automatiquement. 
-Facturation à l’usage : La facturation est calculée en fonction de la durée et de la quantité de ressources utilisées. 

# 5.
Qu'est-ce que l'A/B Testing ?
L’A/B Testing est une technique qui consiste à mettre en comparaison deux versions d’une page web, d’une application, d’un e-mail ou même d’un formulaire, dans le but d’analyser les résultats et de déterminer la version la plus performante selon l’objectif fixé ou envisagé.
# 6.
Comment programmer le cloud ?
La programmation du cloud se fait sur 3 niveaux :
IaaS (niveau bas), il n’y a pas de pile logicielle prédéfinie, on peut y installer un Windows Server ou un Linux avec une base Oracle ou MySQL, et développer ses applications dans le langage de son choix. 
PaaS (niveau intermédiaire) est le plus intéressant pour les développeurs puisqu’il permet de créer ses propres applications en s’appuyant sur une plateforme logicielle.
SaaS (niveau élevé), il s’agit des solutions métier clés en main, hébergées sur le site de l’éditeur telles que les applications CRM de salesforce.com.

# 7.
Quelle est la technique pour faire un déploiement sans interruption de service ?
Pour faire un déploiement sans interruption de service, il faut isoler les machines de productions, découper les versions en plusieurs livraisons, automatiser les étapes de tests et passages en production d’une nouvelle la version terminer pour réduire les cycles.
# 8.
Qu'est-ce que le Canary release ?
Le canary release est un pattern qui permet de faire tester les dernières modifications réalisées à une tranche de population restreinte avant de réaliser un déploiement général de la version travaillé. Il permet d’améliorer considérablement la qualité des mises en production. 
# 9.
Comment changer de taille de machine virtuelle ?
Après avoir cloner notre machine virtuelle, on pourra effectuer ces deux lignes de commandes :
cd C:\Program Files\Oracle\VirtualBox\
VBoxManage.exe modifyhd C:\Users\Le Crabe\VirtualBox VMs\[Nom de la machine virtuelle]\[Nom du disque].vdi --resize [Nouvelle taille du disque en Mo]

# 10.
Qu'est-ce que le Blue/Green deployment ?
Le Blue Green deployment est un modèle de publication d'application qui permet de transférer progressivement le trafic utilisateur depuis la version antérieure d'une application ou d'un service vers une nouvelle version pratiquement identique. L'ancienne version représente l'environnement bleu, et la nouvelle version représente l'environnement vert.
# 11.
Citez deux avantages du PaaS sur le IaaS ?
Le développement et le fonctionnement des applications peut se faire sans aucune préoccupation concernant les mises à jour des plateforme ou logiciels qui fonctionnent dessus. 
L’exécution de l’application s’effectue sur la même plateforme, fournie à distance et par le biais d’une interface Web par votre hébergeur. 

# 12.
Quelle est la différence entre le PaaS et le Serverless ?
Les principales différences entre le PaaS et le Serverless sont l'évolutivité, la tarification, le temps de démarrage, l'outillage et la capacité de déploiement à la périphérie du réseau.
# 13.
Que veut dire Serverless ?
Serverless computing (l'informatique sans serveur) est un modèle de conception et de déploiement d'applications basé sur les événements dans lequel les ressources informatiques sont fournies sous forme de services cloud évolutifs.
# 14.
Citez les trois propriétés désirable du Serverless ?
-Facturation : les développeurs ne paient que pour ce qu'ils utilisent. 
-Rapidité : temps de lancement des applications Serverless est très rapide.

# 15.
Comment s'appelle la plus petite unité de compute déployable en Serverless ?La plus petite unité de compute déployable en serverless est une fonction de calcule.
