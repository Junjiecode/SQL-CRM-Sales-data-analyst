# SQL-CRM-Sales-analyst-

![fashion!](https://github.com/Junjiecode/Python-CRM-sales-data-analyst-/blob/main/1000_F_334796865_VVTjg49nbLgQPG6rgKDjVqSb5XUhBVsW.jpg)

In this project, I am going to analyze the CRM sales data of a prestigious female fashion brand, I will use both Python and SQL to analyze it: 

* to check my python answer worksheet, please click on:
* to check my SQL answer worksheet on big query, click on: 

## Instruction 

Contexte : vous êtes Data Analyst et l’équipe CRM de la marque X vous contacte car elle a besoin d’obtenir certains KPIs dans le cadre d’une étude qu’ils sont en train de réaliser.

Leur périmètre est le suivant :
- les clients français uniquement (variable NATIONALITE_CLIENT dans la table CLIENTS)
- les achats uniquement s’ils ont été réalisés en France, Belgique, Espagne, Pologne ou Suisse (variable PAYS_ACHAT dans la table VENTES)

Vous disposez des données suivantes :
- Les ventes allant de 2021 à 2023
- Un référentiel client
- Un référentiel produit

![schema!](https://github.com/Junjiecode/Python-CRM-sales-data-analyst-/blob/main/image.png)

Pour rappel :
- 1 achat = 1 NUM_ACHAT unique (un ticket de caisse en magasin ou sur le WEB)
- 1 article = 1 MCVT unique (un soutien-gorge, un t-shirt…)
- 1 client = 1 RCUCRM unique

1 achat est réalisé par 1 client et contient 1 ou plusieurs articles.

NUM_ACHAT est l’ID de l’achat. MCVT est l’ID du produit. RCUCRM est l’ID du client.
