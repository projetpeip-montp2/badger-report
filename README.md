PROJET PEIP SEMAINE DU NUMERIQUE
================================

Description
-----------

Projet Polytech Montpellier PEIP  

Ce repository contient le rapport ainsi que la présentation du projet.  

Rapport et présentation sont écris en Latex, et nécessitent donc d'avoir une
plateforme Latex complète.

Le rapport estavec la classe 'book'. Cela explique entre autre que les chapitres
et parties commencent sur une page impaire ("belle page"), mais aussi que jusqu'au 
premier chapitre, la numérotation des pages est en chiffre romain ainsi que 
l'absence de numérotation à partir des appendices.  


Compiler le rapport
-------------------

Pour compiler le rapport:

    cd report/  
    pdflatex badger-report.tex  
    pdflatex badger-report.tex  
    bibtex badger-report.aux  
    pdflatex badger-report.tex  
    pdflatex badger-report.tex  
