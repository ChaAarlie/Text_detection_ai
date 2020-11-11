# Text_detection_ai

Ce git est composé de deux parties: 

I- Classification de lettre de l'alphabet

II- Reconnaissance de zones de textes dans une images 

Pour un accès rapide, il est recommandé d'utiliser quick_test.ipynb, en utilisant le modèle déjà entrainé. 
Il faut ajouter le path de l'image à scanner dans la dernière cellule.

Bounding_box.ipynb est utilisé pour créer et entrainer le modèle soit même. 
Le dataset est disponible sur https://bgshih.github.io/cocotext/
Il est nécessaire de traiter les images en amont avec le fichier preprocess.py; qui va créer des numpy arrays.
