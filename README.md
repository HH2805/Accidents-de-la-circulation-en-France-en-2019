# Les accidents de la circulation en France : modèle de prévision de la gravité des accidents corporels
Hélène / Orphée
![eiffel.jpg](https://raw.github.com/HH2805/{Accidents-circulation-France-en-2019/})
Mini-projet Ironhack Data Analytics DAPT printemps 2021

En France (métropole et DOM-TOM), les forces de l'ordre relèvent des informations sur chaque accident de la circulation si :
- au moins 1 véhicule impliqué
- et au moins 1 victime ayant nécessité des soins. 
---> Bases de données Annuelles des Accidents corporels de la Circulation routière (BAAC), mises à disposition du public sur www.data.gouv.fr et libres d’utilisation. 

Notre étude : la BAAC de l’année 2019, un jeu de données de 132977 lignes / 54 colonnes, ramené après nettoyage à 130064 lignes / 33 colonnes.
Chaque ligne correspond à l'une victime des 130064 victimes de la route en 2019, et fournit des données sur les caractéristiques de l'accident, son lieu, le véhicule impliqué, la victime et la gravité de l'atteinte corporelle.

Cette gravité est codifiée comme suit :
- Indemne
- Blessé Léger
- Blessé Grave (plus de 24h d'hospitalisation)
- Décès sous 30 jours

Le jeu de données est téléchargeable sur data.gouv.fr : https://www.data.gouv.fr/fr/datasets/bases-de-donnees-annuelles-des-accidents-corporels-de-la-circulation-routiere-annees-de-2005-a-2019/

Un repository github a été créé pour ce projet : https://github.com/HH2805/Accidents-circulation-France-en-2019
Il inclut :
- un référentiel du projet et du jeu de données ("codebook")
- un notebook Jupyter.
- un classeur Tableau dont la présentation est également consultable en ligne : https://public.tableau.com/app/profile/h.l.ne.hill/viz
- le Pandas Profile Report du jeu de données.
