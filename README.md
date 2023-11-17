Le but de ce projet est d'entraîner un modèle de réseau neuronal convolutionnel (CNN) à l'aide de la plateforme Edge Impulse. 
Edge Impulse est une plateforme qui permet aux développeurs de créer et de déployer des modèles d'apprentissage automatique sur des périphériques embarqués, tels que des microcontrôleurs et des appareils IoT (Internet des objets). Cette plateforme offre une interface conviviale pour la création, l'entraînement et le déploiement de modèles d'apprentissage automatique sans nécessiter une expertise approfondie en matière d'apprentissage automatique. Les principales étapes de ce projet sont: **la formation d'un CNN**, **l'utilisation du jeu de données**, **la conversion des images**, **le téléchargement du jeu de données**, **la création de l'impulsion**, **l'extraction des caractéristiques**, **l'entrainement du modèle** et **l'évaluation et l'ajustement**. 

1-La formation d'un CNN
   L'objectif principal est d'entraîner un réseau neuronal convolutionnel (CNN). Dans notre cas ici, au lieu d'utiliser un simple réseau neuronal dense, on opte 
   pour un CNN.

2- L'utilisation du jeu de données
    Le projet utilise un jeu de données, lié à des composants électroniques. Un jeu de données est fourni dans le projet disponible dans les fichiers joints. Ce jeu lié 
    à des composants électroniques est composé entre autre de résistances, diodes et leds.

3- Conversion des images
     Les images du jeu de données doivent être converties en formats acceptés par Edge Impulse, à savoir les formats .png ou .jpg. 

4- Téléchargement du jeu de données
    Les données d'image sont téléchargées directement sur Edge Impulse. Les étapes incluent la création d'un nouveau projet, l'accès à l'acquisition de 
    données, le téléchargement des données existantes pour chaque classe, et l'attribution des libellés appropriés.
    Ci-dessous une capture des données téléchargées:
    <img width="960" alt="image" src="https://github.com/Meryano/Projet-4/assets/148442282/2cb56a62-bd76-430d-af6d-e117058c1ed0">

5- Création de l'impulsion et extraction des caractéristiques
    On crée une impulsion sur Edge Impulse, en ajustant les paramètres des données d'image et en ajoutant des blocs de traitement d'image et d'apprentissage de 
    classification. Les caractéristiques des images sont ensuite extraites en modifiant la profondeur de couleur en niveaux de gris, puis en générant les 
    caractéristiques.

6- Entrainement du modèle
    On se rend sur le classificateur NN (Neural Network) pour entraîner le modèle. On suit les recommandations fournies pour le réglage du nombre de cycles 
    d'entraînement et des hyperparamètres du modèle.

7- Evaluation et ajustement
    Après l'entrainement, on évalue la performance du modèle. Des suggestions sont données pour ajuster les hyperparamètres, tels que le nombre de cycles d'entraînement, le nombre de filtres et les tailles de noyau, afin d'améliorer les performances du modèle.

En résumé, ce projet vise à entrainer un modèle CNN sur Edge Impulse. On met l'accent sur l'utilisation d'un jeu de données spécifiques lié aux composants électroniques. 
    
