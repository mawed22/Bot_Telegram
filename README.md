# WalletWatchBot 

WalletWatchBot est un bot Telegram personnalisé que j'ai développé pour simplifier la gestion de mes dépenses quotidiennes. Pour créer ce bot je me suis inspirer de https://github.com/kevindegila. Ce bot utilise une combinaison de l'API Speech-to-Text de Google Cloud pour permettre l'entrée vocale des dépenses, l'API de Chat GPT pour interagir avec l'utilisateur de manière conversationnelle, et une base de données SQL (SQLite) pour stocker de manière sécurisée les informations liées aux dépenses.

## Fonctionnalités principales

- **Entrée Vocale :** Grâce à l'intégration de l'API Speech-to-Text de Google Cloud, le bot permet aux utilisateurs d'enregistrer leurs dépenses en utilisant simplement leur voix.

- **Interaction Conversationale :** L'utilisation de l'API Chat GPT offre une expérience utilisateur conversationnelle, permettant aux utilisateurs de dialoguer naturellement avec le bot pour gérer leurs dépenses.

- **Stockage Sécurisé :** Toutes les informations sur les dépenses sont stockées de manière sécurisée dans une base de données SQL (SQLite), assurant la confidentialité et la disponibilité des données.

## Configuration et Utilisation

1. **Clé API Google Cloud :** Obtenez une clé API Speech-to-Text depuis la console Google Cloud et ajoutez-la à votre configuration.

2. **Token Telegram :** Obtenez un token Telegram pour votre bot via le BotFather et configurez-le dans le fichier approprié.

3. **Dépendances Python :** Installez les dépendances nécessaires en utilisant le fichier `requirements.txt`.

4. **Base de Données :** Le bot utilise SQLite comme base de données par défaut. Assurez-vous que le fichier de base de données est configuré correctement.

5. **Exécution du Bot :** Exécutez le script Python principal pour lancer le bot. Vous pouvez commencer à enregistrer vos dépenses dès maintenant !

## Contributions

Les contributions sous forme de suggestions, de rapports de bogues et de demandes d'améliorations sont les bienvenues. N'hésitez pas à ouvrir une issue ou à soumettre une pull request pour enrichir ce projet.
