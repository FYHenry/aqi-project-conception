# aqi-project
## Projet Pureté de l’air

### Initialisation

Ce projet débute par sa conception via :
* Un diagramme de cas d’usage en UML ;
* Un diagramme de classe en UML ;
* Un modèle conceptuel de données en Merise ;
* Un modèle physique de données en Merise ;
* Une maquette des pages Web pour l’interface Web.

Un document, le dossier de spécification générale, est complété à
l’attention du client.
Il précise une maquette sur les interactions de l’utilisateur avec
l’interface.
Il est consultable dans `/conception/dossier_de_specification.pdf`.

Un second document, le dossier de conception, indique la stratégie
à suivre par l’équipe pour développer l’application.
Il est consultable dans `/conception/dossier_de_conception.pdf`.

### Évolution

Un diagramme de paquets est apparu pour présenter l’évolution du
projet lors des débuts du serveur HTTP côté _backend_.

![Diagramme de paquets](conception/resources/uml/PackageDiagram.svg)

Il illustre une architecture en couches entre le client HTTP et
le serveur de base de données.

S’ajoute un premier diagramme de séquences pour illustrer le mécanisme
de requête HTTP du JSON émis au JSON reçu.

![Diagramme de séquence](conception/resources/uml/SequenceDiagram.svg)

Plus exactement ici il s’agit de lire un compte utilisateur en JSON.
