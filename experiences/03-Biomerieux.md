# Contexte

AES Chemunex, ensuite racheté par Biomerieux, est une société pionnière dans les analyses micro-biologique dans le domaine de l'agro alimentaire.

Date: Février 2012 / Janvier 2014

Localisation: Région de Rennes (France)

# Missions

Ce projet a pour but de piloter et collecter les données des machines d’analyses micro biologiques développées par AES Chemunex afin de permettre une large traçabilité des échantillons et des
événements du laboratoire.

Développeur principal d'une équipe de 2 développeurs et gestion de l'intégration avec les équipes 
en charge des développements du matériel :
- Réflexions et démonstrations autour de différentes architectures (SGBD relationnel / NoSQL, JAVA / .NET, Flex / HTML 5)
- Elaboration de l’architecture à partir des spécifications fonctionnelles
- Mise en place du protocole de communication entre les machines électroniques et le serveur (RESTFul)
- Mise en place de socle technique
- Mise en place de l'intégration continue (Jenkins, checkstyle, PMD, findbugs)
- Liste non exhaustive des composants développés / intégrés :
- Gestion des licences
- Scheduler (Quartz)
- Notification via email, sms, rsh
- Configuration des notifications via des modèles personnalisables
- Installation : izpack pour la partie windows / script shell pour unix
- Configuration Apache HTTPD, Tomcat, Postgres packagé dans la solution
- Authentification au travers d'un serveur LDAP
- Système de mise à jour du logiciel
- Système de mise à jour de la base de données (liquibase)
- Développement de Valves Tomcat pour aider au suivi des performances en production
- Compatible multi OS (Windows *, Linux)
- Compatible multi SGBD (postgresql, oracle, mysql, sqlserver)
- Interface Flex 4.10 (Granite DS / Swiz)

Mission réalisée chez un éditeur de solution.

Technologies: Java 7, Spring (IoC, AOP), Hibernate (Postgres, Oracle, MySQL, SQLServer), Liquibase, Flex (Granite DS / Swiz), Tomcat, JAX-RS (Apache CXF), Quartz, IZpack, LDAP, Maven, Jenkins