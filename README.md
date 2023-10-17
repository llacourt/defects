# Évaluation de python-numérique

Lisez bien ce document jusqu'au bout ! 

## **Informations importantes**

Ce projet constitue l'évaluation de la partie python-numérique de l'ECUE PE.

Le sujet se trouve dans le fichier `notebook.py`. Vous devez compléter ce notebook avec vos implémentations et remarques. 


**Réalisation, condition et date de rendu du projet**  
* le projet doit être réalisé **individuellement**
* il doit être rendu sous la forme d'un notebook (*vous complétez le notebook initial avec votre code et vos explications*)
* vous devez pousser votre code sur github **avant le `2 décembre minuit`**
  
Sans vouloir le moins du monde être désagréables, nous vous prévenons que les projets non envoyés à cette date, envoyés à une mauvaise adresse, réalisés à plusieurs, identiques ou fort ressemblants (oui nous savons c'est très subjectif), ne seront pas notés et les élèves concernés ne valideront pas le module Python-numérique (donc pas PE).

**Des questions ?**  
* les questions concernant le sujet, doivent être posées à laurent.lacourt@mines-paris.org 

**Attendus sur votre code**
* le code doit être écrit en anglais
* les commentaires et les explications peuvent rester en français 
* le code doit être propre, lisible et commenté aux endroits adéquats
* vos fonctions doivent contenir une `docstring`
* le code doit s'exécuter sans erreur

## Installation des modules nécessaires

Afin de visualiser une partie des données qui vous sont mises à disposition pour ce projet, vous devez installer un module spécifique. Pour ne pas surcharger votre environnement de base, nous vous conseillons de créer un environnement spécifique à l'évaluation et d'y installer les modules nécessaires: 

```bash
conda create -n eval-pe python=3.9
conda activate eval-pe
pip install -r requirements.txt
jupyter notebook
```

**Dans la suite, vous devrez taper la commande suivante avant de commencer à travailler sur le sujet :**

```
conda activate eval-pe
```
