Système de Contrôle Qualité et Détection de Défauts par Vision Industrielle (AOI)
Module d'inspection optique automatisée (Automated Optical Inspection - AOI) conçu pour les lignes de fabrication et de tri industriel. Le système traite et analyse les flux d'images pour détecter, segmenter et classifier les anomalies de surface et défauts dimensionnels en temps réel (Contrôle Qualité 4.0).

Architecture Logicielle & Outils
Langage de développement : Python 3.10+

Traitement d'images : OpenCV (Filtrage spatial, seuillage adaptatif Otsu, détection morphologique de contours)

Calcul matriciel & analyse : NumPy

Visualisation des résultats : Matplotlib

Environnement d'exécution : Google Colab / Jupyter Notebook (compatible déploiement Edge AI / Raspberry Pi 4)

Pipeline Algorithmique de Traitement
Prétraitement d'image : Conversion en niveaux de gris et atténuation du bruit par filtre Gaussien (5x5).

Segmentation morphologique : Binarisation automatique par seuillage adaptatif pour extraire les zones d'intérêt.

Extraction géométrique : Calcul précis de l'aire, du périmètre et de la circularité des pièces inspectées.

Prise de décision industrielle :

Comparaison automatique avec les tolérances géométriques de référence.

Classification instantanée : PASS (Conforme) ou FAIL (Non-conforme avec boîte englobante sur le défaut).

Démonstrateur Interactif en Ligne (Google Colab)
Accédez à l'environnement d'exécution complet et testez l'algorithme sur les jeux de données :

👉 https://colab.research.google.com/drive/1oEev2nWk6UoqN5sL3LvH-zDVXgJa2YZF
Auteur
Ahmed El Ayachi

Ingénieur en Informatique Industrielle et Systèmes Embarqués
