**Application de Suivi des Performances Éducatives avec LLM et RDF Cube**

--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

Bienvenue dans notre projet qui combine des Modèles de Langage de Grande Taille (LLM) et des Cubes RDF pour offrir une solution innovante de suivi des performances éducatives. Ce projet permet de structurer des données éducatives et d'utiliser l'intelligence artificielle pour produire des analyses et des recommandations personnalisées en fonction des performances des étudiants.


-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
Contexte du projet
Dans le cadre de l'éducation, il est essentiel de suivre et d'évaluer les performances des étudiants pour identifier les domaines où des améliorations sont nécessaires. Ce projet se concentre sur l'utilisation de RDF Cube pour structurer les données éducatives et de LLM pour générer des réponses aux questions posées en langage naturel par les utilisateurs (enseignants, administrateurs).

-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
Fonctionnalités principales
Analyse des performances éducatives : Basée sur différents critères tels que les cours, la classe, ou l'année.
Recommandations personnalisées : Proposer des actions ciblées pour améliorer les performances des étudiants ou des classes.
Interface utilisateur intuitive : Les utilisateurs peuvent poser des questions en langage naturel pour obtenir des réponses sous forme de statistiques, tendances ou recommandations.
Architecture du système
L'application est constituée de trois composants principaux :

-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
Interface Utilisateur (UI) : Permet aux utilisateurs de poser des questions et de visualiser les résultats.
Module LLM : Interprète les questions posées en langage naturel et génère des réponses pertinentes à partir des données RDF Cube.
Cubes RDF : Stocker et organiser les données éducatives de manière multidimensionnelle, facilitant les requêtes complexes.
Installation et configuration
Prérequis
Python 3.10 ou plus récent
Poésie pour la gestion des dépendances
Clé API OpenAI pour interagir avec le modèle de langage
Important : Clé OpenAI
Pour cloner et utiliser cette application, vous devez avoir une clé API OpenAI valide. Vous pouvez obtenir cette clé en créant un compte sur OpenAI et en générant une clé via leur interface de gestion des API. Cette clé sera nécessaire pour interagir avec les capacités du modèle de langage intégré à l'application.

-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
Étapes d'installation
-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
1- Cloner le dépôt du projet :

git clone https://github.com/Desiree270122/Application_RDFCube-LLM_SP.git
cd Application_RDFCube-LLM_SP

----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
2-Créer un environnement virtuel et l'activer :

python -m venv .venv
source .venv/bin/activate

-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
3-Créez un fichier .env et ajoutez-y votre clé API OpenAI

OPEN_API_KEY=votre_cle_api
Lancer l'application dans Visual Studio Code : Ouvrez le projet dans VSCode

OPEN_API_KEY=votre_cle_api

-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
Auteurs
Marthe Désirée Olivia HABACK
Dieudonné BYAOMBE MWINDULWA, 
Priscile EBWALLA EBWALETTE, 
David Lutala Lushuli,

Encadré par : Dr. Tuong Nguyen
