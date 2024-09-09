# SIO1-Projet
**Objectifs**: réalisez un quizz en utilisant une base de données de questions
 1) Générez un quizz de 10 questions aléatoires
 2) Affichez le score à la fin
 3) Affichez les bonnes réponses
 4) Proposez de recommencer le quizz
 5) Temps limité à 3 semaines de développement(les cours seront utilisés pour l'organisation et la planification. Le développement à proprement parlé sera réalisé à en partie en classe en partie en dehors des cours).

> **Conseils:**
> - Gérez votre temps
> - Gardez le cap
> - Priorisez vos actions
> - Répartissez vous le travail
> - Ne favorisez pas le coté graphique
> - Concentrez vos efforts sur le développement PHP

> **Note**
> Pour réaliser un **git push** sans avoir à fournir votre TOKEN à chaque push, vous pouvez configurer votre dépôt local afin qu'il le fournisse automatiquement: **git remote set-url origin https://\<USER\>:\<TOKEN\>@\<URL\>**

## Comment utiliser GitHub pour la gestion de ce projet ?
 1) Constituez un groupe de 2 max
 2) L'un d'entre vous est le chef de projet
 3) Le chef de projet fait une copie de ce template en cliquant sur "Use this template"
 4) Le second récupére l'adresse https du dépôt créé par le chef de projet   
 ![image](https://user-images.githubusercontent.com/101867500/195951851-047ccbaf-407b-45cc-98e8-babc36ee0b6d.png)   
 5) Le chef de projet et le second font un git clone du dépôt du chef de projet sur sa propore machine à partir de l'URL récupérée
 ```bash
 git clone <URL>
 ```
 6) le chef de projet ajoute le professeur dans les collaborateurs: Depuis le dépôt > Settings > Collaborators > Add people
 7) Votre répertoire de travail local sera un dossier accessible par votre serveur Apache, PHP, Mysql.
 
> **Note**   
> **Pour rappel**   
> Si vous rencontrez des soucis avec la commande git ou l'utilisation des systèmes de gestion de version, reportez-vous au cours ou à la documentation très complète disponible ici en français: https://git-scm.com/book/fr/v2    

# Consignes
## Gestion des bugs
En cas de bug ou de problème détecté sur votre projet, rendez-vous dans le menu **"Issues"**
![image](https://user-images.githubusercontent.com/101867500/195944614-f7a3a4f1-7848-4d0f-80c0-333b8f077662.png)   
  a) Utilisez les **"Issues"** (problèmes) pour lister chaque problème que vous avez repéré ( un alignement de logo, un retour à la ligne qui manque, etc ...).   
  b) Utilisez les **"labels"** pour clarifier le type de problème ou de demande formulée

## Gestion des tâches
Rendez-vous dans le menu **"Projects"**
![image](https://user-images.githubusercontent.com/101867500/195948069-b449d949-e755-4265-91d0-9554eca8b541.png)
1) Ajoutez une tâche dans TODO (à faire) pour les fonctionnalités à coder ou tâche à réaliser
2) Glissez posez une tâche dans **IN PROGRESS** et assignez la à un quelqu'un lorsqu'elle est en cours de développement  
3) Glissez posez la tâche terminée dans **DONE** lorsque la push request a été validée par le chef de projet   

## Gestion des branches

> **Warning**   
> **Règles à respecter impérativement**   
> 1 ajout, 1 modification ou 1 correction = une tâche (Project > TODO > Add item)   
> 1 tâche = 1 branche   

## Règles de nommage
 - [bug]: Pour une branche dédiée à la correction d'un bug. Doit suivre le n° de l'issue et une description en 2 mots    
 - [dev]: Pour une branche dédiée à une fonctionnalité en cours développement   
 - Evitez les noms long
 - Utilisez les séparateurs _
 - Utilisez des noms uniques

Exemples:   
[bug]_Issue#12_alignement_logo   
[dev]_css_aligment_formulaire

Eviter les noms long

# Modalités d'évaluation
La note est individuelle et sera basée sur des critères suivants:
 1) Création et utilisation (par étudiants) des **Issues**, **tâches** et **commits** (5 pts)
 2) Respect des règles de nommage (2 pts)
 3) Respect de la règle **1 tâche = 1 branche** pour les modifications que vous avez proposées (5 pts)
 4) Qualité, cohérence et pertinence du travail en équipe (5 pts)
 5) Gestion des versions livrables (3 pts)


