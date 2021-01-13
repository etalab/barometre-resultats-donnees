# Données ouvertes du Baromètre des résultats de l’action publique
Ce dépôt heberge les données sur lesquelles est construit le [baromètre des résultats de l’action publique](https://barometre-resultats.data.gouv.fr/). 

## Liens utiles : 
- [Jeu de données correspondant sur data.gouv.fr](https://www.data.gouv.fr/fr/datasets/barometre-des-resultats-de-laction-publique/)
- [Dépôt du code source de l'outil](https://github.com/etalab/barometre-resultats)
- [Dépôt de documentation des données](https://github.com/etalab/barometre-resultats-documentation)

## Qu'est-ce que le baromètre des résultats ?
Le [baromètre des résultats de l’action publique](https://barometre-resultats.data.gouv.fr/) concrétise un engagement présidentiel fort et inédit sous la Ve République : la transparence des résultats de l’action publique. Il démontre également la détermination du Gouvernement à améliorer la vie quotidienne des citoyens dans chaque territoire, à accélérer la mise en œuvre des réformes et à renforcer l’évaluation de l’action publique, grâce à un pilotage par les résultats et par la donnée.

Accessible en ligne sur le site [gouvernement.fr](https://gouvernement.fr) depuis janvier 2021, le baromètre permet à chaque citoyen de suivre l’action du Gouvernement, politique par politique, territoire par territoire.

Le baromètre des résultats de l’action publique est développé par [Etalab](https://www.etalab.gouv.fr/), au sein de la [direction interministérielle du numérique](https://www.numerique.gouv.fr/dinum/).Il fera l’objet de mises à jour régulières, à l’occasion desquelles il sera enrichi de nouvelles politiques prioritaires.


## Les données
Les fichiers suivants sont disponibles :

- `barometre-resultats-synthese` : synthèse des indicateurs avec leurs valeurs initiales, actuelles et cibles, ainsi que le pourcentage de progression et le taux d’avancement. Les fichiers sont déclinés à l’échelle nationale, régionale et départementale, en format csv et JSON.
- `barometre-resultats-detail` : détail des indicateurs avec l’historique des valeurs, à l’échelle nationale, régionale et départementale, en format csv et JSON.
- `barometre-resultats-data.xlsx` : ce fichier regroupe les tableaux barometre-resultats-detail et barometre-resultats-synthese pour toutes les mailles géographiques.

Les données sont aussi regroupées par département (dossier `departements`) et par thematique (dossier `secteur-action-publique`).
