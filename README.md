### Bienvenue sur votre espace Workshop Kafka


### Connexion à votre instance Linux :

Vos Credentiels et IPs respectives vous seront envoyés sur le chat.    
Une clé SSH .pem vous sera transmise sur le chat.  


#### Si vous êtes sur Linux/Mac :

- Telecharger la clé au format PPK : [KEY.ppk](https://raw.githubusercontent.com/mehdi-lamrani/kafka-workshop/master/res/bin/SAP-KEY.pem)  
  ("Sauvegarder sous"... extenstion pem)
  
- Se connecter en SSH à votre serveur :

```console 
ssh -i ./NOM-DE-VOTRE-CLE.pem ec2-user@ICI.ADRESSE.IP.FOURNIE
```

#### Si vous êtes sur Windows :

- Installation de Mobaxterm :
https://download.mobatek.net/2022020030522248/MobaXterm_Portable_v20.2.zip

- Vous pouvez également utiliser Putty (moins pratique pour le multi-fenetrage toutefois)

- Telecharger la clé au format PPK : [KEY.ppk](https://raw.githubusercontent.com/mehdi-lamrani/kafka-workshop/master/res/bin/SAP-KEY.ppk)  
  ("Sauvegarder sous"... extenstion ppk)

- Se connecter en SSH à votre serveur :

  - NE RECOPIEZ PAS LES VALEURS DANS LA COPIE D'ECRAN CI-DESSOUS
  - Veillez à mettre le bon user ec2-user  
  - renseigner l'IP qui vous a été fournie  
  - rentrer le chemin du fichier de clé PPK 

![alt text](https://i.ibb.co/tYL7W8y/Annotation-2020-05-08-135954.png)
