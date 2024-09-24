# Authentication List

## Superset :

**Username** : arsenoferi

**Password** : admin354

## Jupyter Notebook :

**Token** : arfeal

## Postgress (Database) :

**POSTGRES_USER**: root

**POSTGRES_PASSWORD**: example

**POSTGRES_DB**: mydb

## PGadmin :

**Username** : admin@example.com

**Password** : admin

# How to used this repo :
1. Install Docker (https://docs.docker.com/engine/install/)
2. Open docker application
3. Open terminal in current directory
4. put command : docker-compose up -d
5. open : http://localhost:3000/ in your browser

# Services that we used to created this project :

### This project used docker with 4 services :
1. Jupyter Notebook -> Create ETL from excel file to Database
2. Pgadmin -> Manage postgress
3. Postgress -> Our Database
4. Superset -> Our BI Tools

![Workflow Superset](Image/Workflow_Superset.png)

# Dashboard Explanation

## Transaction Overview
![Transaction Dashboard](Image/Transaction.png)

We can conclude the sales value of this store group mostly stable but there is significant growth on October this is probably because the effect of Halloween. We can conclude also if you want to win make sure your product is low fat this indicate by great pumpkin bread had most product sales in this store group. great pumpkin bread is low fat product

## Customer Overview

![Customer Overview](Image/image.png)

Bronze membership is the most revenue contribute. The bronze most member had criteria :
1. Professional Job
2. Had yearly income $30K - $50K
3. High School

Top Brand that Bronze Member Love:
1. Hermanos
2. Tri-state
3. High Top
4. Ebony
5. Tell Tale

# Store Overview 
![Store Overview Dashboard](Image/Store.png)







