# ML-DP_Differencier_arbres_fleurs
Utilisation de Machine Learning puis Deep Learning pour différencier les arbres des fleurs dans le cadre d'un projet ingénieur M2  

Date du projet : octobre 2022  

Auteurs :  
- Marie JOIGNEAU marie.joigneau@agrocampus-ouest.fr  
- Marion GUNDELWEIN marion.gundelwein@agrocampus-ouest.fr  
- Armelle LAJEUNESSE armelle.lajeunesse@agrocampus-ouest.fr  
- Laurence REN laurence.ren@agrocampus-ouest.fr

Documents à disposition :
- Le script, en .py et .ipynb  
- Notre présentation  

Ci-joint l’explication pour chaque dossier (les dossiers étant entre guillemet). Dû aux poids de ces fichiers, ils ne sont pas sur github. Cependant, le code parle de lui-même et ils ne sont pas nécessaires pour le comprendre. Néanmoins, je vous les explique dans l'ordre d'apparition dans le script, que vous puissiez comprendre ce que le code appelle si besoin :
- Les datasets bruts :  
    -	"arbres" = images brut des arbres  
    -	"fleurs" = images brut des fleurs  
- Les datasets converties (pré-traitement 1) :  
    -	"arbres_converties" = images des arbres converties en .jpg  
    -	"fleurs_converties" = images des fleurs converties en .jpg  
- Les datasets avec des images de même taille (pré-traitement 2) : "Arbres_fleurs". Les images des arbres et fleurs sont mises avec le même nombre de pixel (avec comme sous-dossiers "arbres_pixel" et "fleurs_pixel")  
- Les datasets convertis en noir et blanc (pré-traitement 3) :  
    -	"Arbres_fleurs_grey" = images des arbres et fleurs converties en noir et blanc (avec comme sous-dossiers "arbres_grey" et "fleurs_grey")  
    -	"Arbres_fleurs_zoom" =  images des arbres et fleurs zoomées (avec comme sous-dossiers "arbres_zoom" et "fleurs_zoom")  
-	Les dataframes en csv de tous les types d'images avec 3 colonnes = 1 pixel : "data" 
-	Les datasets pour tester le deep-learning  "Donnees_test", divisé en train/test (et plus tard validation) (avec comme sous-dossiers "couleur", "couleur_test", "grey", "grey_test", "zoom" et "zoom_test"  
-	Un dataset complètement différent, utilisé pour voir si notre modèle s’applique à d’autres jeux de données : "New_couleur_test" (avec comme sous-dossier "Arbre_test" et "Fleur_test")

Attention, ces scripts ont été créé sur google drive, plus précisement dans un "colab notebook". Pour les chemins de fichier, il vous faudra les adapter. Si vous voulez faire tourner le code sur google drive, il faut mettre le dossier du projet (“Colab_Notebooks) en raccourci dans le drive.   

Si vous avez besoin de plus de renseignement n'hésitez pas à me contacter,  
Marie
