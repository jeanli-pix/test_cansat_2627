# Document de pré cadrage CANSAT
Equipe:
Iftene CHERFI
Jean-Bosco LINOT
Lou-jane HARTMANN
Lucie Panossian
Florence Jin
	
## Date : 
*21 septembre 2026*

## Introduction : 

Le principe du CanSat repose sur l'idée de concevoir dans un volume réduit correspondant à une Canette de soda, une charge utile similaire à celle embarquée dans un Satellite. 

Originellement de 33cL, ce volume peut être augmenté jusqu’à 1L. Tous les principaux systèmes d’un satellite, tels que l'alimentation, le dispositif de mesures et la télémesure, doivent être conçus et intégrés dans le volume réduit du CanSat.

Le CanSat est largué à l'aide d'un drone ou autre dispositif similaire et réalise ses missions à partir du largage, pendant la descente et à l'atterrissage.

L'objectif de la compétition CanSat France est de réaliser un CanSat capable d'exécuter les missions principales et secondaires définies chaque année


## Mission principale (obligatoire)
### Mission 1 : Ouverture et Atterrissage
Intégration : Intégration d’un « astronaute » à l’intérieur de votre Cansat.
Ouverture : Sortie véhiculaire de l’astronaute après environ 3 secondes de vol.
## Missions secondaires (optionnelles)
### Mission 2 : Rétrécissement
Réduire le CanSat au format 33 cl vous permettra de multiplier votre score par 2 sur la partie technique (voir grille de notation en annexe).
### Mission 3 : Biomimétisme
Mettre en place un principe de biomimétisme dans la conception du Cansat.
### Mission 4 : Technologie historique
Conception du timer de largage de l’astronaute avec un système entièrement analogique.
## Mission libre
Lors de la descente ou suite à l'atterrissage, votre CanSat peut effectuer une mission supplémentaire. Sa notation sera à l'appréciation du jury (voir grille de notation en annexe).
Une validation de la mission libre doit être effectuée par les contrôleurs lors de la RCE1 pour vérifier la conformité au présent document.
 


## Lots :

### Hardware : 
Dans le cadre de notre projet on aura donc à charge de concevoir un PCB. Une station sol sera développée, elle sera composée d’un écran et ainsi que d’un écran annexe de configuration.

### Software : 
Notre PCB, conçu et fonctionnel, a donc comme objectif de programmer celui-ci en langage C. De plus, on devra programmer les deux écrans en python .

### Mécanique : 
Afin de respecter les contraintes de la compétition, nous devons concevoir un fuselage aérodynamique et respectant le volume de 33 cl .

## Tâches :
Concevoir le PCB : choisir les composants, faire le schéma KiCad
Concevoir le fuselage du cansat : imprimer en 3D pour respecter l’objectif de rétrécissement 
Effectuer plusieurs largages tests 
Concevoir le timer du largage
Configurer la mallette avec l’écran et l’écran annexe de configuration 

## Durée :
La durée totale du projet est de 11 mois (Septembre 2026-Juillet 2027)
Les durées entre les deadlines sont : 
	2 mois : novembre 2026 (rce1, formation et rencontre avec les suiveurs du projet)
	1 mois : 30 novembre 2026  (inscription et envoie du dossier de définition)
	1 mois : décembre 2026  (réunion de mi projet à l’école)
	2 mois : février 2027 (rce2, revue de conception)
	1 mois : mars 2027 (présentation finale du projet à l’école)
	3 mois : juin 2027 (rce3, revue de qualification)
	1 mois : juillet 2027 (largage des cansats)



## Contraintes : 

N°


1 Réalisation de la mission en moins de 5 min


2 Masse du cansat inférieure à 1kg 


3 Le cansat est dans un volume de 80 mm sur 200 mm de haut 


4 Pas de déploiement ou d’émission radio avant l’ouverture du largueur


5 Pas d’élément tranchant


6 Pas de pyrotechnie ni de matière dangereuse 


7 Pression des systèmes pneumatiques limités à 10 bars 


8 Tension des systèmes électriques limitée à 30 V 


9 Autonomie électrique d’au moins 45 min 


10 En cas d’utilisation d’un fil résistif, celui-ci de ne doit pas pouvoir enflammé une feuille de papier 


11 Le cansat doit avoir un interrupteur d’alimentation générale accessible 


12 Le cansat doit avoir un interrupteur dédié et accessible pour le module télémétrie


13 En cas de présence d’un séquenceur  celui-ci doit être indépendant de l'expérience 


14 Les fréquences utilisables et les puissances HF émises autorisées sont :

  ● La bande 433MHz avec une puissance max de 10mW

  ● La bande 868.5MHz à 869.2MHz avec une puissance max de 25mW

  ● La bande 869.4MHz à 869.65MHz avec une puissance max de 500mW

  ● La bande 2.4GHz avec une puissance max de 100mW

  ● La bande 5.8GHz avec une puissance max de 25mW

  ● La bande 144-146MHz peut être utilisée sous réserve qu’un radioamateur licencié soit
présent lors des émissions.

  ● Les émetteurs GSM du commerce et conformes à la réglementation sont autorisés.

  ● La bande 868.0-868.5MHz est interdite car elle est allouée à la liaison entre le largueur et
le sol.


15 Le CanSat et éléments largués doivent descendre entre 3m/s et 15m/s
Tout élément éjecté doit être solidement relié à la fusée ou ralenti lors de sa chute dans les
mêmes conditions que le Cansat.
La vitesse de descente est obtenue par calcul à l’aide de la formule suivant


16 La chaîne de récupération doit être capable de résister à une force de 20N


17 Le CANSAT doit être compatible avec le largueur le jour J


18 Ressources limitées donc nombre de prototypes limité.


## Risques: 

Risque d’écrasement lors des lancements de tests (limité à un seul voire 2 prototypes) 
 Délais de commandes des composants et des PCB
Changement du cahier des charges en cours de projets par les porteurs du projet (les professeurs et les membres jury de SCAE)
Problème de conception PCB détecté tard après la conception (ajoute un nouveau retard)
Soufflerie pas prête pour les tests 




