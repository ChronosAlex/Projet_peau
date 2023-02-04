# **Projet_Final_TinyML**

## Problèmes rencontrés
<br />Il m'est impossible de me connecter à ma carte pour essayer de prendre des données avec celle-ci depuis edge impulse.
<br />J'ai le dernier firmware, ma carte est bien flashée et j'arrive bien à me connecter sur edge impulse.
![Capture d’écran 2023-02-04 174038](https://user-images.githubusercontent.com/84152339/216779109-e6e0216d-1985-442f-b557-72ab5e4fd8f5.png)
<br />
<br />Puis lorsque je veux essayer j'obtiens le message suivant que je ne comprends pas :
<br />
![2023-02-03 (3)](https://user-images.githubusercontent.com/84152339/216778178-98f6c3bc-ecb4-45db-9a36-3ff55bbd08a6.png)
<br />
<br /> Second problème qualité des images de la caméra
<br />
## Edge Impulse
<br />Base de données utilisé : https://www.kaggle.com/datasets/nodoubttome/skin-cancer9-classesisic 
<br />J'ai utilisé celle concernant l'actinic keratosis.
<br />Pour les photos normales j'ai utilisé mon téléphone. J'ai pris 8 photos pour l'entrainement et 2 pour le test.
<br />
![2023-02-04 (1)](https://user-images.githubusercontent.com/84152339/216779382-a7946efc-0d8f-4fa9-94fd-6b624b958e43.png)
<br />On réalise ensuite le modèle d'entrainement 
<br />
![2023-02-03 (1)](https://user-images.githubusercontent.com/84152339/216779495-c54f8805-1e20-471b-ac6b-fc1cb6d38393.png)
<br />
<br />Voici les résultats du modèle :
![2023-02-04 (2)](https://user-images.githubusercontent.com/84152339/216779589-095c50d9-20d3-486c-b4a9-cbb77b5e3fa4.png)
<br />
### Arduino
<br /> Edge impulse nous gènère ensuite un code qui peut permettre d'essayer de tester le modèle avec la caméra.
<br /> Malheuresement le modèle est beaucoup trop large pour la mémoire de l'arduino. 
<br /> J'obtiens le résultat suivant :
![fe4c57e4-fd8c-41f6-96e0-69f595019669](https://user-images.githubusercontent.com/84152339/216779886-c8bfb1af-feac-4dab-af71-b88ac5eb73a4.jpg)

