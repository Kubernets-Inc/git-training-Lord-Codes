# Github-training-course
This repository provides the instructional materials for GitHub training hosted by Kubernets Edu
# Introduction to Source Control
## Module 1

###FRENCH
### Introduction

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

### Course Content

This module can be experienced in one of two ways:
  1. YouTube video available [here](http://www.youtube.com/watch?v=Crp40qvuRSE).
  2. Full text of the video is available below.

### Course Transcript

#### What is Source Control?

Source control is a technology that allows developers and other professionals to track
changes to a project over time, and manage releases of data. Basically, this allows
you to have a `master`, or `release` copy of your project, and multiple working copies
called _branches_ that individual team members can contribute to, and submit these changes for review.

#### Git Source Control Management

Specifically, this course will use git to control our projects. Git is a _distributed source control system_,
meaning that each developer's computer has a full copy of the project, which allows developers to
work when offline and unable to connect to a central server. Multiple full copies also helps prevent
data loss.

##### Branching

Git uses a model called _branching_ to help control code. Each branch is a separate set
of changes over time. The `master` branch is the main, default set of the refined project.
For a software organization, the `master` branch would be the code currently deployed to
customers and available on app stores. Making a new branch takes all the history from
the current branch and makes a new copy of it. For example, making `branch-1` from the `master`
branch makes a copy of all of the changes in the master branch and saves it under the `branch-1`.
Now, while `branch-1` is the active branch, any changes that are saved, or _committed_ in git terminology,
are added to the `branch-1` history **but not the `master` branch history**.
This separation allows developers to implement new features, troubleshoot and fix bugs,
and enhance the user experience **without** affecting the code shipping to customers.

Branches should be address one specific task or change. They should target only one bug
or add only one feature. This allows the changes for that specific feature to be reviewed
separately from any other changes. Speaking of code review, let's discuss pull requests.

##### Pull Requests

Once a developer has completed all changes for his or her specific branch, it is time to request a review!
Code review is an important step of the software development process. In a collaborative
project, no changes should be merged to the `master` branch without being checked by another
team member. Even in a two person team, Developer A should always have Developer B review his or her
changes before merging. Likewise, Developer B will always ask Developer A to check his or her
changes before merging to `master`. This process can be quickly handled in a _pull request_.

Remember that each developer is working on a separate _working branch_ that contains only the
changes for their specific task. A _pull request_ is a request by the developer to _pull_ those
changes from the _working branch_ into the `master` branch. In a pull request, reviewers can view
the changes made and make comments, ask for clarification, or suggest changes. This ensures that the
only changes to make it to the `master` branch are the **best possible work of the whole team**, not
just a single developer. The largest benefit of the pull request model is that these comments are
made within the context of the changes themselves. Reviewers can comment on the **exact** line
that they are referring to, which makes it easier to communicate between team members without
being in the same place or even working at the same time.

Once a _pull request_ is approved, it can be merged into the `master` branch, which adds all
changes made since the creation of the branch to the `master` branch.

### Exercise

Your exercise for this module is to submit a pull request introducing yourself to the
NC A&T Makerspace community. From the [main repository page](https://github.com/KubernetsEdu/Github-training-course), open the `submissions` directory
and create a new file called `about.md` in `submissions/[your-github-username]/`.
Your `about.md` file is a [Markdown](https://guides.github.com/features/mastering-markdown/)
document that can be formatted using Markdown syntax. Your document should answer the following questions:
* Who are you? What is your name and what do you do on campus?
* What do you do outside of school? What are your hobbies and passions?
* What do _you_ have experience in? What can others ask you about for assistance? This community can only thrive with the cumulative skills and experience of all of us. **Those skills and collaborations** are what we are using GitHub to enhance.

Once you have completed your `about.md`, select "Create a new branch for this commit and start a pull request". Follow the _pull request template_ provided when you click "Commit new file".



