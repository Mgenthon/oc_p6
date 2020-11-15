# oc_p6

L'idée est ici d'étudier la faisabilité d'un moteur de classification automatique d'articles. Pour ce faire, nous avons à disposition des images et des descriptions textuelles des articles en question.
Nous avons utilisé des algorithmes de classification textuelle (Bags of Word suivie d'une LDA, TF-IDF suivie d'une NMF) pour classer les articles dans les bonnes catégories en fonction des 
descriptions.
Nous avons utilisé la méthode ORB et des CNN (réseau de neurones convolutionnels VGG 16 et Resnet50) pour classer correctement les articles à partir des images associés aux articles.
