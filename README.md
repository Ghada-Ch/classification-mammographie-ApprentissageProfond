# classification-mammographie-ApprentissageProfond
## Objectif :
Construire un modèle d’apprentissage profond pour la classification des
images de mammographie en trois catégories (Normal, benign, malignant).
Nous aurons une interface graphique à partir de laquelle nous pourrons tester
différentes images pour savoir la pertinence du système.
## Étape 1: Définition de l’architecture du modèle:
Nous devons définir à quoi ressemblera notre modèle et cela nécessite de
répondre à des questions telles que :
● Combien de couches convolutives voulons-nous ?
● Quelle doit être la fonction d’activation de chaque couche ?
● Combien d’unités cachées doit avoir chaque couche ?
## Étape 2 : Entraînement du modèle:
Nous allons décomposer notre base de données en des images
d’entraînement et leurs étiquettes vraies correspondantes et Des images de
test avec leurs étiquettes vraies correspondantes
Nous définissons également le nombre d’époques dans cette étape. Pour
commencer, nous allons exécuter le modèle pendant 10 époques (vous
pouvez changer le nombre d’époques plus tard).
## Etape 3 : Prédiction des images:
Nous chargeons les données de test (images) et passons par l’étape de
prétraitement ici aussi. Nous prédisons ensuite les classes pour ces images
en utilisant le modèle entraîné.

## Etape 4 : Estimation des performances du modèle
Enfin, vous générez un matrice de confusion ainsi qu’afficher l’accuracy de
votre modèle
Environnement :
Vous pouvez utiliser l’environnement et le langage de programmation de votre
choix.
### Base de données :

Il faut utiliser une base généraliste d'au moins 1000 images.
Voici le lien de la base de données DDSM qui contient des mammographies
"normal", "benign", "malignant" et que vous pouvez télécharger gratuitement :
https://drive.google.com/file/d/10bJ75CJnSQSgya0HXKP3difeiKChxfYi/view
