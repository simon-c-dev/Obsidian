### Concilier Outils, Développement, Conception, et Agileté

Hedgedoc - Outils de documentation par collaboration en MarkDown (Similaire a Google docs mais MD)
SonarQube -  Analyse de code qui peut etre intégré dans l'Intégration continue de GitLab.
Gitlab -  Gestionnaire de source avec intégration continue.
Méthodologie #GitFlow : Devra être utilisé
	- Chaque branche = 1 issue -> Créer une branche a partir d'un issue
	- Feature branching

Flow a respecter: 
- Créer un projet
- Créer un issue
- Créer une branche à partir d'un issue
- Clone projet 
- Modif + git add
- git commit -> URL de l'issue + titre de l'issue 
- git push déjà tracker donc pas de upstream

**Maven**: 
Gestionnaire de dépendances
Utilisé des convention de maven au lieux de configuration complexe
Garantie un processus de constructio -> Une uniformité a travers tout les membre de lequippe, un standard est imposé par maven.
Fichier POM: Centralisé les dépendance pour maven -> Cest loutil de communication avec maven.


**GitLab-C**I:
Détection de fautes rapide et identifiable à un commit.
Fichier de git-lab.ci: Détermine un processus de build a exécuter pour chaque commit a distance.
- Roule dans un sandbox/VM/Conteneur
- Doit spécifier certaines dépendance a installer

**Tests**:
Test unitaire pour CI
Test fonctionnel -> Ils vérifient uniquement la sortie d'une action et non les états intermédiaires du système lors de l'exécution de cette action.







