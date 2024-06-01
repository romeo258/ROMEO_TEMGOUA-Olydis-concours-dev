# ROMEO_TEMGOUA-Olydis-concours-dev
webservice de gestion d'employees


####### Gestion des Employés - API REST #######
Description
Ce projet est une API REST de gestion des employés, développée avec Spring Boot 3.2.2 et Angular 15. L'application permet de gérer les informations des employés et inclut toutes les fonctionnalités demandées. La base de données utilisée se trouve dans le répertoire resource du projet, et les informations de connexion à la base de données sont situées dans le fichier application-dev.yml.

Utilisation
Connexion
Pour accéder à l'application, utilisez les informations de connexion suivantes :

Email : romeo@gmail.com
Mot de passe : 12345678

### vous avez egalement la possibiliter de creer votre propre compte et l'activer d'utilisateur avec un email real et si l'ordinateur est connecter a internet pendant l'execution de ce programme. a defait activer votre compte manuellement dans la base de donnees a fin de mieux gerer les employes.

Exécution de l'Application
L'application est prête à être exécutée dans un conteneur Docker. Pour ce faire, assurez-vous d'avoir Docker installé sur votre machine. Voici les étapes pour exécuter l'application dans un conteneur :

Construisez l'image Docker :  SECRET=Wilson82629274* ./start.dev.sh

Documentation
Pour faciliter l'utilisation de l'API, une documentation Swagger - OpenAPI est intégrée. Vous pouvez accéder à la documentation en ouvrant votre navigateur et en accédant à l'URL suivante après avoir démarré l'application :
        http://localhost:8080/swagger-ui.html

Tests
Les tests peuvent être effectués en utilisant Postman. Vous pouvez importer la collection Postman fournie dans le projet pour faciliter les tests des différentes fonctionnalités de l'API.

Sécurisation
Pour assurer la sécurité des données, le schéma de la base de données a été étendu. Les détails de cette extension se trouvent dans le fichier de migration de la base de données dans le répertoire resource.

Conclusion
Cette API de gestion des employés offre une solution complète et sécurisée pour la gestion des informations des employés. Grâce à l'intégration de Docker, elle peut être facilement déployée dans différents environnements. La documentation Swagger et les tests avec Postman garantissent une utilisation facile et une bonne compréhension de l'API.

Pour toute question ou support supplémentaire, n'hésitez pas à consulter la documentation ou à contacter l'équipe de développement.
