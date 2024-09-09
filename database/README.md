# Prérequis
> ```warning```
> Nom de la base de données **SIO1-projet1**


## Restauration de la base de données
```bash
mysql --user=root --password=12345 SIO1-projet1 < le_fichier.sql
```

# Structure de la base de données
![image](https://user-images.githubusercontent.com/101867500/195984853-4efbecab-a0e7-4b83-ad7a-5a0d91f9ee95.png)


Cette base de données contient un panel de 130 questions:
  - **qcm_id**: Clé primaire
  - **qcm_question**: Question
  - **qcm_r1_resultat** 1 si réponse1 vrai, 0 si faux
  - **qcm_r1_proposition** Réponse1 
  - **qcm_r2_resultat** 1 si Réponse2 vrai, 0 si faux
  - **qcm_r2_proposition** Réponse 2
  - **qcm_r3_resultat** 1 si Réponse3 vrai, 0 si faux
  - **qcm_r3_proposition** Réponse 3
  - **qcm_r4_resultat** 1 si Réponse4 vrai, 0 si faux
  - **qcm_r4_proposition** Réponse 4
