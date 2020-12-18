# movies-spinoff-mongodb

# Prérequis pour de README: 
* Python3
* Git

# Différentes étapes pour installer et lancer le projet: 


### Commençons par copier le repository de travail floupics
> git clone https://github.com/cosmicblues/movies-spinoff-mongodb

### Allons dans le repository spinoff3 floupics
> cd movies-spinoff-mongodb

### Créons son environnement virtuel
> python3 -m venv nomDeEnv

### Activons notre environnement (sous Windows seulement)
> nomDeEnv\Scripts\activate.bat

### Activons notre environnement (sous Mac OS seulement)
> source nomDeEnv/bin/activate

### installons jupyter lab
> pip install jupyterlab

### Afin d'acceder aux scripts lançons jupyter lab: 
> jupyter lab

### Créons notre BDD via mongo:
> télécharger mongodb https://www.mongodb.com/try/download/community?tck=docs_server
> lancer le .exe
> Après installation en local, créer la variable path "C:\Program Files\MongoDB\Server\4.4\bin\" dans windows

### Nous pouvons maintenant lancer dans git bash
(serveur local)
> mongod

(puis)
> mongo

### Nous sommes maintenant sur mongo, créons notre bdd
> use db_spinof3

### installation de pymongo (librairie) pour les scripts : 
> pip install pymongo

## En conséquence, nous pouvons désormais actionner les cellules de code dans l'ordre dans Jupyter Lab afin de créer la base de données et insérer les données en son sein.
