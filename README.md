# BcaTestTechnique
test technique pour  BCA


Installer les dépendances 

    pip install -r requirements.txt


Le projet contient en réalité deux petits projets : 

- Le premier est un fineTuning de Yolo. Ce n'est pas réellement un projet Pyhton, mais il m'a permis d'utilsier l'outil de labelling Labelimg pour ce modèle.

- Le second projet est également un finetuning mais cette fois ci de : fasterrcnn_resnet50_fpn


Je me suis dirigé vers cette logique car ce genre de modèle à déjà de très bonne performances et l'adapter sur nos données est à mon sens la bonne démarche. En effet l'exercice de détection (et eventuellement classification) est un exercice classique et ce genre de modèle répondent parfaitement au cahier des charges. 


Cependant les performances du modèle sont relativement faibles. En fonction des entrainements nous avons des performances assez faibles voire médiocres. 


Je n'avais encore jamais réalise de modèle de détection, mais j'ai trouvé ce projet intéressant ! 


En travaillant de manière assez régulière j'estime ma durée de travail à environ 8-10h