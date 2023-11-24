
# Laboratoire 3: Modélisation UML de l'application AppRoximité


## Entête
   
    Projet: 
        Laboratoire 3 - Modélisation UML de l'application AppRoximité
    Étudiants: 
        Mathieu Hatin (2296939) / Simon Turcotte (2395412) / Jean-Nicolas Tessier
    Cours: 
        Conception d’applications mobiles (420-295-AH)
    Date: 
        Novembre 2023


## LucidChart 

- Les diagrammes UML demandés pour le laboratoire et auquels le présent document fait référence sont disponible via les liens suivants:
    - Partager: https://lucid.app/lucidchart/invitations/accept/inv_84ddd9c0-a9d3-4085-9b3d-df4dc753b47b
    - Publier (lecture seule aucun compte LucidChart nécessaire): https://lucid.app/documents/view/8efaad6e-3c28-4737-be0e-46446927664c

- Les diagrammes UML ont été conçus avec le logiciel Drawio. 

- Étant donné que pour le laboratoire l'élaboration des diagrammes doit être fait via le service de diagrammes en ligne LucidChart, une conversion
des diagrammes Drawio en LucidChart a été faite.

- Deux problèmes mineurs du à la conversion dont les correcteurs du laboratoire doivent être au courant:
    - Les ronds de terminaison noirs cerclés pour les diagrammes d'activités sont remplacés par des carrés noirs.
    - Dans les diagrammes de classe, la ligne de séparation entre les attributs et les méthodes n'apparaît plus.


## Pdf

- Puisque des problèmes mineurs de conversion on un peu malmené les diagrammes sous LucidChart, une exportation pdf à partir de Drawio sera aussi jointe.


## Explication du README (aussi appelé Rapport explicatif)

- Ce fichier constitue le rapport explicatif des diagrammes demandé pour le laboratoire. 

- Le fichier README sert à préciser certains choix de modélisation.

- Il sera pratique pour justifier l'évolution du labo dans le cadre d'un travail d'équipe et pour le correcteur final.

- Oui, il peux décrire des évidences pour des modélisateurs d'expérience mais comme nous sommes à faire nos 
premières armes avec le modèle UML, tous les membres de l'équipe pourront bénéfier d'explication commune 
et de la logique sous-jacente à certain choix fait par des membres individuellement.

- Étant donné que ces informations n'ont pas a ce retrouver directement dans les diagrammes, on les met ici.


## Diagramme de cas d'utilisation

- Un diagramme de cas d'utilisation n'a pas vocation à entrer dans les détails. 
Par exemple, ne vous attendez pas à ce qu'il illustre l'ordre dans lequel les étapes sont exécutées.

-  Ici, il est important de se concentrer sur l'interaction entre l'utilisateur, le logiciel de réseau social, et d'autres acteurs potentiels. 
Les cas d'utilisation doivent illustrer comment l'utilisateur utilise les fonctionnalités pour :
    * Gérer et animer sa vie sociale en ligne
    * Se connecter avec des personnes et des événements locaux 
    * Partager des expériences
    * Personnaliser son expérience utilisateur.

- Les choix de conception pour les cas d'utilisation "Création de groupes", "Publication de contenus", "Messagerie", "Découverte", et "Gestion de profil" dans le contexte du réseau social basé sur la proximité ont été guidés par les principes fondamentaux des diagrammes de cas d'utilisation UML, tels que décrits sur la page web "Les diagrammes de cas d'utilisation UML | Lucidchart"​​ (https://www.lucidchart.com/pages/fr/diagramme-de-cas-dutilisation-uml)

- Voici les justifications pour les choix de conception de chaque cas d'utilisation :

    **Création de Groupes**

    - **Objectif** : _Représenter l'interaction des utilisateurs avec la fonctionnalité de création de groupes._
    - **Acteurs Impliqués** : _Utilisateur du réseau social._
    - **Actions Principales** : 
        - _Création de groupes._
        - _Ajout/retrait de membres._
        - _Suppression de groupes._
    - **Justification** : _Chaque action représente une interaction distincte et pertinente de l'utilisateur avec le système, conforme aux objectifs du diagramme de cas d'utilisation de fournir une vue d'ensemble des interactions._

    ---

    **Publication de Contenus**

    - **Objectif** : _Illustrer comment les utilisateurs partagent des contenus sur le réseau._
    - **Acteurs Impliqués** : _Utilisateur du réseau social._
    - **Actions Principales** : 
        - _Sélection et téléversement de photos/vidéos._
        - _Ajout de commentaires/hashtags._
    - **Justification** : _Ces actions détaillent les différentes façons dont un utilisateur peut interagir avec le système pour partager des expériences, alignées sur l'objectif de modéliser les flux d'interactions._

    ---

    **Messagerie**

    - **Objectif** : _Décrire les interactions liées à la messagerie._
    - **Acteurs Impliqués** : _Utilisateur du réseau social._
    - **Actions Principales** : 
        - _Envoi de messages privés._
        - _Création de conversations de groupe._
        - _Réception de notifications._
    - **Justification** : _Le diagramme capture les aspects essentiels de la communication entre utilisateurs, organisant les exigences fonctionnelles de la messagerie._

    ---

    **Découverte**

    - **Objectif** : _Montrer comment les utilisateurs découvrent et interagissent avec des personnes et événements locaux._
    - **Acteurs Impliqués** : _Utilisateur du réseau social._
    - **Actions Principales** : 
        - _Activation/désactivation de la localisation._
        - _Trouver à proximité_
        - _Inscription à des événements._
        - _Interaction avec des publications._
    - **Justification** : _Ces actions mettent en lumière les objectifs des interactions entre le système et les utilisateurs en matière de découverte et de participation communautaire. La décision a été prise de ne pas mettre "Trouver des utilisateurs à proximité" et "Trouver des événement à proximité" 
    comme extension à "Activer la localisation" pour permettre de pointer un endroit spécifique sur la carte et non seulement l'endroit où l'on ce trouve 
    actuellement._

    ---

    **Gestion de Profil**

    - **Objectif** : _Illustrer la gestion du profil personnel par l'utilisateur._
    - **Acteurs Impliqués** : _Utilisateur du réseau social._
    - **Actions Principales** : 
        - _Mise à jour des informations._
        - _Ajout de centres d'intérêt._
        - _Modification des paramètres de confidentialité._
        - _Gestion des abonnements._
    - **Justification** : _Ces actions représentent de manière exhaustive les interactions liées à la personnalisation et à la gestion du profil, en ligne avec la nécessité de définir et d'organiser les exigences fonctionnelles du système._

    ---

- Chacun de ces cas d'utilisation a été conçu pour donner une vue d'ensemble claire et concise des interactions possibles entre les utilisateurs et le système, sans entrer dans les détails opérationnels ou l'ordre d'exécution, conformément aux recommandations pour les diagrammes de cas d'utilisation UML.


## Diagramme d'activités

- Les choix de conception pour les diagrammes d'activités UML des scénarios "Un commerce envoie une notification", "Un utilisateur reçoit une notification de proximité", "Changer le rayon de proximité", et "Modéliser la création d’un nouveau commerce" peuvent être expliqués à la lumière du document de LucidChart sur les diagrammes d'activités UML​​ (https://www.lucidchart.com/pages/fr/diagramme-dactivite-uml)

    **Un Commerce Envoie une Notification**

    - **Conception** : _Processus impliquant plusieurs étapes et décisions, y compris le choix du type de notification, la sélection du public cible, la rédaction du contenu et la planification de l'envoi._
    - **Justification** : _Les diagrammes d'activités sont idéaux pour les processus complexes, illustrant clairement les flux de travail et les points de décision._

    ---

    **Un Utilisateur Reçoit une Notification de Proximité**

    - **Conception** : _Le diagramme suit le processus depuis la vérification des paramètres de localisation de l'utilisateur jusqu'à la réception et l'action sur une notification de proximité._
    - **Justification** : _Parfaits pour décrire les flux de processus et les comportements, ils montrent comment un utilisateur interagit avec un système de notification._

    ---

    **Changer le Rayon de Proximité**

    - **Conception** : _Détaille les étapes impliquées dans la modification des paramètres de localisation par l'utilisateur._
    - **Justification** : _Modélise efficacement un processus utilisateur spécifique, en montrant chaque étape et décision clairement._

    ---

    **Modéliser la Création d’un Nouveau Commerce**

    - **Conception** : _Visualise les étapes de la création d'un commerce, y compris la saisie des informations, la configuration des paramètres, et l'intégration dans le réseau._
    - **Justification** : _Adaptés pour décomposer un processus complexe en étapes plus simples, offrant une vue d'ensemble du processus de création._


## Diagrammes de classe
- Comme référence, nous avons utilisé la documentation LucidChart: https://www.lucidchart.com/pages/fr/diagramme-de-classes-uml
- Une ligne avec une flèche pleine pointant de GestionnaireDeCommerce vers Utilisateur montre qu'il s'agit d'une sous-classe
- La flêche avec le losange noir du côté Utilisateur et le 1 du côté Preferences indique que sans un utilisateur, il ne peux y avoir de Preference. 
Et qu'il n'y a qu'une seule instance de Preference par instance d'utilisateur
- La flèche en pointillés avec une pointe ouverte indique que GestionnaireDeCommerce dépend de Notification pour certaines de ses opérations.
