### Stage 2021

Ce stage a été effectué pour le M1 Linguistique Informatique à l'Université de Paris, dans le [Laboratoire de Linguistique Formelle](http://www.llf.cnrs.fr/) du CNRS. Il a été encadré par Mmes H. Burnett et J. Abbou.

Ce stage a pour sujet l'étude du genre dans le Corpus du Grand Débat.

[Corpus](https://granddebat.fr/pages/donnees-ouvertes) : Données ouvertes du Grand Débat section "Débat et Citoyenneté"

Tâches effectuées :
- Récupération des données au format csv ;
- Nettoyer les données ; 
- Faire de l'étiquetage morpho-syntaxique (POS-Tagging) sur les données pour relever les noms, pronoms et adjectifs ;
- Récupérer les lemmes des formes relevées.
- Faire des statistiques sur les noms communs taggués (fréquence et occurence).
- Extraire de la liste des noms communs les référents humains.



J'ai travaillé avec les notebooks Jupyter pour avoir une meilleure annotation et évolution de mon travail.
Pour le POS-Tagging, j'ai utilisé l'outil de POS-Tagging de la bibliothèque de TAL [SpaCy](https://spacy.io/usage/linguistic-features#pos-tagging)
Pour l'extraction des référents humains, j'ai utilisé la [méthode de calcul de similarité](https://spacy.io/usage/linguistic-features#vectors-similarity) de SpaCy

