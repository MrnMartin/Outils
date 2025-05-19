# Outils

## TP1: P1 CoNLL 2003 

- Quelle type de tâche propose CoNLL 2003 ?
  
CoNLL 2003 est conçu pour la reconnaissance d'entités nommées Named Entity Recognition (NER).

- Quel type de données y a-t-il dans CoNLL 2003 ?
  
Les données sont textuelles, ce sont des articles de presse annotés par mot,avec des étiquettes pour indiquer le rôle grammatical, son groupe syntaxique et son type d'entité nommée.
  
- A quel besoin répond CoNLL 2003 ?
  
Il va développer, évaluer et comparer des systèmes de NER et faire progesser la technique d'analyse
  
- Quels types de modèles ont été entraînés sur CoNLL 2003 ?
  
Ils existent différent type de modèles:  

. Statistiques avec CRF (Conditional Random Fields)  
. Transformers comme BERT  
  
- Est un corpus monolingue ou multilingue ?
  
CoNLL 2003 contient des données pour deux langues : l'anglais et l'allemand.
On ne peux pas le considérer comme monolingue mais plus comme bilingue.

---

##TP1: P1 Projet 

- Dans quel besoin vous inscrivez vous ?

Ma recherche est de comprendre et analyser le contenu émotionnel des chansons

- Quel sujet allez vous traiter ?

J'aimerais détecter les émotions exprimées dans les chansons.
  
- Quel type de tâche allez vous réaliser ?
  
Je vais réaliser une tâche de classification automatiquement visant à attribuer une émotion à chaque chanson 
  
- Quel type de données allez vous exploiter ?

Les données utilisé seront textuelle.
  
- Où allez vous récupérer vos données ?
  
Les données récupérer sont sur internet

---

##TP2: 

Tout d'abord, mon corpus est composé de 10 textes (paroles de chansons).  
Pour le TP2, deux scripts on était réalisés. Le premier, scrape_lyrics.ipynb, me permet de récuperer les données (Texte) à partir des pages URLs que j'ai sélectionnées.    
Le second script, scrape_clean.ipynb, nettoie les textes extraits en supprimant les éléments comme les balises [Chorus] ou autre.

---

#TP3:  

Pour visualiser mon corpus et effectuer des statistiques, j'ai adopté une approche différente. J'ai d'abord crée un script MoyenneELyrics.ipynb qui permet d'obtenir un pourcentage des différentes émotions présentes dans les textes, grâce à un modèle.  
Ensuite, avec Visualisation.ipynb j'ai généré trois graphiques: une moyenne, un diagramme en barre empiliées et une heatmap.

---

#TP4:

A partir des données récupérées, le script Csv_Augmentation.ipynb, me permet d'augmenter mon jeu de données.  En plus de la version originale, je génère deux variantes différentes grâce au texte puis j'enregistre les résultats dans un fichier .csv.
--- 

#TP5 - TP6:  

Le script Finetune.ipynb me permettra de Finetuner le modèle que j'ai utilisé précédemment, sachant qu'il correspond bien aux caractéristiques de mes données.   



