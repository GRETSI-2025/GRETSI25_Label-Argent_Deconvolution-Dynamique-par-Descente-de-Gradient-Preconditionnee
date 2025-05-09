# README

Ce dépôt contient deux notebooks Jupyter utilisés dans le cadre du projet scientifique présenté à GRETSI 2025.

## Prérequis

Assurez-vous d’avoir installé les éléments suivants :

- Python 3.8 ou supérieur
- [Jupyter](https://jupyter.org/) (par exemple via Anaconda ou avec `pip install notebook`)
- Les bibliothèques suivantes :
  ```bash
  pip install numpy matplotlib scipy
  ```

> Vous pouvez également utiliser un environnement virtuel si vous préférez isoler les dépendances.

## Installation des dépendances

Ce projet utilise quelques bibliothèques Python pour le calcul scientifique, les statistiques et la visualisation.  
Les dépendances nécessaires sont listées dans le fichier `requirements.txt`.

Pour installer toutes les dépendances, utilisez la commande suivante :

```bash
pip install -r requirements.txt
```

## Exécution

1. Ouvrez un terminal et placez-vous dans le répertoire du projet.
2. Lancez le serveur Jupyter avec la commande :
   ```bash
   jupyter notebook
   ```
3. Ouvrez les notebooks dans l’ordre indiqué (s’il y a une dépendance d’un notebook vers l’autre).
4. Exécutez **chaque cellule dans l’ordre** (de haut en bas) pour garantir le bon fonctionnement.

## Structure du projet

- `comparaisons.ipynb` : expériences de la partie 4.1
- `dynamique.ipynb` : expériences de la partie 4.2

## Remarques

- Aucune donnée externe n’est requise en dehors de ce qui est généré dans les notebooks.
- Le code est fourni sous licence open source (voir fichier LICENSE).

---

**Auteur :** 
- Joseph Gabet — joseph.gabet@centralesupelec.fr
- Maxime Ferreira Da Costa — maxime.ferreira@centralesupelec.fr
- Charles Soussen — charles.soussen@centralesupelec.fr


