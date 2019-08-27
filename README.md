 Introduction to Source Control
## Module 1

###FRENCH
### Introduction

Welcome to the Aggie MakerSpace course on source control for software development!
Bienvenue dans le cours Kubernets Edu Github sur le contrôle de source pour le développement de logiciels!
Ce cours est conçu pour familiariser les étudiants universitaires avec le pouvoir de la collaboration, de la
contrôle de la source via git et GitHub. Le but de ce module est de préparer votre machine à
utilisez git et familiarisez-vous avec la terminologie git et gitHub.

### Le contenu des cours

Ce module peut être expérimenté de deux manières:
  1. Vidéo YouTube disponible [ici] (http://www.youtube.com/watch?v=Crp40qvuRSE).
  2. Le texte complet de la vidéo est disponible ci-dessous.

### Transcription du cours

#### Qu'est-ce que le contrôle de source?

Le contrôle de source est une technologie qui permet aux développeurs et autres professionnels de suivre
les modifications apportées à un projet au fil du temps et gérer les publications de données. Fondamentalement, cela permet
vous devez avoir une copie `master` ou` release` de votre projet et plusieurs copies de travail
appelé _branches_ auquel chaque membre de l'équipe peut contribuer et soumettre ces modifications pour révision.

#### Gestion du contrôle de source Git

Plus précisément, ce cours utilisera git pour contrôler nos projets. Git est un système source_ de contrôle source distribué,
ce qui signifie que l’ordinateur de chaque développeur possède une copie complète du projet, ce qui permet aux développeurs de
travailler en mode hors connexion et incapable de se connecter à un serveur central. Plusieurs copies complètes aident également à prévenir
perte de données.

##### Branchement

Git utilise un modèle appelé _branching_ pour aider à contrôler le code. Chaque branche est un ensemble séparé
des changements au fil du temps. La branche `master` est l'ensemble principal par défaut du projet affiné.
Pour une organisation logicielle, la branche `master` serait le code actuellement déployé pour
clients et disponible sur les magasins d'applications. Faire une nouvelle branche prend toute l'histoire de
la branche actuelle et en fait une nouvelle copie. Par exemple, créer `branch-1` à partir du` maître`
branch effectue une copie de toutes les modifications de la branche maître et l’enregistre sous la branche `branch-1`.
Maintenant, alors que `branch-1` est la branche active, toute modification sauvegardée ou _committed_ dans la terminologie git,
sont ajoutés à l'historique `branche-1` ** mais pas à l'historique des branches` maître` **.
Cette séparation permet aux développeurs d’implémenter de nouvelles fonctionnalités, de dépanner et de corriger des bugs,
et améliorez l'expérience utilisateur ** sans ** affecter le code envoyé aux clients.
Les branches doivent être adressées à une tâche ou à un changement spécifique. Ils ne devraient cibler qu'un seul bug
ou ajouter une seule fonctionnalité. Cela permet de revoir les modifications apportées à cette fonctionnalité spécifique
séparément de tout autre changement. En parlant de révision de code, discutons des demandes d'extraction.
##### Demandes d'extraction
Une fois qu'un développeur a terminé toutes les modifications pour sa branche spécifique, il est temps de demander une révision!
La révision du code est une étape importante du processus de développement logiciel. En collaboration
projet, aucune modification ne doit être fusionnée dans la branche `master` sans être vérifiée par un autre
membre de l'équipe. Même dans une équipe de deux personnes, le développeur A devrait toujours demander au développeur B de revoir ses
changements avant la fusion. De même, le développeur B demandera toujours au développeur A de vérifier ses
change avant de fusionner avec `master`. Ce processus peut être rapidement traité dans une demande de transfert.
N'oubliez pas que chaque développeur travaille sur une _working_ branche distincte qui contient uniquement le
changements pour leur tâche spécifique. Une requête_pull_ est une requête du développeur à _pull_ ceux
passe de la branche _working_ à la branche `master`. Dans une demande de tirage, les relecteurs peuvent voir
les modifications apportées et faire des commentaires, demander des éclaircissements ou suggérer des modifications. Cela garantit que le
seules les modifications permettant d’atteindre la branche `master` constituent le ** meilleur travail possible de toute l’équipe **, et non
juste un seul développeur. Le plus grand avantage du modèle de demande d’attraction est que ces commentaires sont
dans le contexte des changements eux-mêmes. Les réviseurs peuvent commenter la ligne ** exacte **
auxquels ils font référence, ce qui facilite la communication entre les membres de l’équipe sans
être au même endroit ou même travailler au même moment.
Une fois qu'une requête_pull_ est approuvée, elle peut être fusionnée dans la branche `master`, qui ajoute tous les
les modifications apportées depuis la création de la branche dans la branche `master`.
### Exercice
L’exercice pour ce module consiste à soumettre une demande de tir d’appel vous présentant au
Communauté NC A & T Makerspace. Depuis la [page du référentiel principal] (https://github.com/KubernetsEdu/Github-training-course), ouvrez le répertoire `submission`
et créez un nouveau fichier appelé `about.md` dans` Submissions / [your-github-username] / `.
Votre fichier `about.md` est un [Markdown] (https://guides.github.com/features/mastering-markdown/)
document pouvant être formaté en utilisant la syntaxe Markdown. Votre document devrait répondre aux questions suivantes:
* Qui es-tu? Quel est votre nom et que faites-vous sur le campus?
* Que fais-tu en dehors de l'école? Quels sont vos passe-temps et passions?
* Dans quoi avez-vous l'expérience? À quoi les autres peuvent-ils vous demander de l'aide? Cette communauté ne peut s'épanouir qu'avec les compétences et l'expérience cumulatives de chacun d'entre nous. ** Ces compétences et ces collaborations ** sont ce que nous utilisons GitHub pour améliorer.
Une fois que vous avez terminé votre `about.md`, sélectionnez" Créer une nouvelle branche pour cette validation et démarrer une demande d'extraction ". Suivez le modèle de requête _pull_ fourni lorsque vous cliquez sur «Valider un nouveau fichier».
### Introduction
Welcome to the Kubernets Edu Github course on source control for software development!
This course is designed to introduce university students to the power of collaborative, distributed
source control through git and GitHub. The purpose of this module is to prepare your machine to
use git and familiarize you with git and GitHub terminology.
@@ -84,3 +166,5 @@ document that can be formatted using Markdown syntax. Your document should answe

Once you have completed your `about.md`, select "Create a new branch for this commit and start a pull request". Follow the _pull request template_ provided when you click "Commit new file".
