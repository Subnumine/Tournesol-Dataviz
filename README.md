# Tournesol-Dataviz

En tant qu'utilisateur, nous nous sommes interrogé sur le genre d'informations que nous aimerions avoir et voici quelques propositions de visuels qui pourraient être, pourquoi pas, ajoutés sur le site de Tournesol.

## Premièrement sur la page "Mes recommandations"
La première chose qui nous a semblé "contre-productive" c'est l'accumulation des comparaisons qui peut vite devenir décourageante. Nous avons donc imaginé que sur cette page nous pourrions présenter un graphique du nombre de comparaisons que nous avons effectué en fonction du temps. Nous pourrions sélectionner par exemple l'année (ou toutes), si nous souhaitons afficher les semaines ou les mois, selectionnable en cliquant sur la courbe directement. A droite du graphique seraient alors affichées les vidéos comparées dans cette semaine/mois/année, ou bien les thématiques/tags qui sont le plus revenus.
En fonction de la contribution des utilisateurs, nous souhaitions également proposer une sorte de "badge" pour motiver à la régularité. Dans notre exemple ici celle-ci est définie arbitrairement et est considéré comme contributeur régulier tout utilisateur ayant comparé au moins 10 vidéos dans les 4 dernières semaines.

## La page d'accueil
En plus du nombre total de comparaisons et de vidéos notées qui est effectivement très intéressant (nous pensions que des graphiques pour montrer les évolutions pourraient être plus percutant peut-être ?), nous souhaitions proposer un "écart" supplémentaire pour montrer l'évolution des utilisateurs. Nous avons donc réalisé un graphique montrant le nombre de nouveaux utilisateurs en fonction du temps, mais montrant également le nombre d'utilisateur régulier dans cette période. Pour accompagner ce graphique, pourquoi pas ajouter une visualisation de la répartition des thème ou tags des premières vidéos comparées par les nouveaux utilisateurs !

## Le système de notation des vidéos
Actuellement le chiffre affiché pour chaque vidéo nous semblait un peu trop abstrait. Nous souhaitions donc pour finir proposer un visuel que l'on espère plus "concret". Le tournesol se tournant vers la source lumineuse, nous avions pour idée de noter les vidéos en fonction du niveau d'ensoleillement que celles-ci génèrent. Nous aurions donc toujours ce nombre visible mais positionné sur une sorte de thermomètre allant de l'obscurité à la lumière du soleil (-100 à 100). Les valeurs négatives remplissant la jauge d'obscurité et les valeurs positives la jauge de lumière.
Fichier associé : 'Data_viz_score_vidéo.pdf'

Les différents graphiques sont représentés sur des maquettes montées "à la main" à partir des graphiques réalisés à partir de l'exploration du dataset. Le code python, ainsi que le dataset utilisé, sont disponibles sur ce repository.
