L’objectif du projet est de prédire le jour t, les prochaines escales (identifiant de port et fenêtre temporelle) de l’ensemble des cargos dans une fenêtre allant de t+5 jours à t+20 jours. A cette prévision devra être associé un niveau de pertinence (valué entre 0 et 100). Il est important d’éviter les prédictions de type « faux positifs ».
Une extension de ce travail est de se placer dans un contexte « dynamique » où la prédiction effectuée le jour t sera affinée le jour suivant t+1 (prédiction sur l’horizon t+8 à t+21).
L’ensemble des données fournies devra être partitionné à un niveau temporel pour permettre de rejouer les situations passées. Pour évaluer les méthodes proposées, il est possible, en se plaçant à une date dans le passé, de faire des prédictions et de vérifier si elles ont bien eu lieu ou non.
La validation de la qualité / performance d’une méthode peut se faire selon différentes mesures :   
Qualité de la prédiction spatiale (l’escale prévue a eu lieu dans l’intervalle t+5, t+20).
Qualité de la prédiction temporelle (écart entre fenêtre prévue et fenêtre réalisée).

[DEMO](https://youtu.be/2_aME2iuRw4?si=HTbv9qV65DGAvXK9)
