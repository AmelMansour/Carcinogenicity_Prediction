# Carcinogenicity_Prediction

Ce projet, créé lors d'un hackathon, se concentre sur la prédiction de la carcinogénicité des composés organiques en se basant sur leur structure chimique. Il vise à contribuer à l'identification rapide des effets toxiques potentiels des nouvelles molécules. Les données proviennent du fichier CSV "Carcinogenicity_Carcinogenicity.csv" de la base de données toxric, comprenant les valeurs de toxicité cancérigène (1 ou 0) pour 1021 molécules. Les descripteurs chimiques ont été calculés à partir des formats SMILES à l'aide du module RDKit de Python.

![Hackathon](https://github.com/AmelMansour/Carcinogenicity_Prediction/assets/141269604/12820dc5-7e74-4a4d-8389-1a562493eed4)
![cap1](https://github.com/AmelMansour/Carcinogenicity_Prediction/assets/141269604/29bd6178-3cea-4da4-b039-a1a99fb597f5)
![cap2](https://github.com/AmelMansour/Carcinogenicity_Prediction/assets/141269604/e717b864-3f1d-4358-b88d-7ce01f1a6491)
![cap3](https://github.com/AmelMansour/Carcinogenicity_Prediction/assets/141269604/a5da9ed3-4211-4e02-94e3-cb9c5abad225)
![cap4](https://github.com/AmelMansour/Carcinogenicity_Prediction/assets/141269604/e9544d94-1f6e-49ab-8d55-bb2c872e952f)
![cap5](https://github.com/AmelMansour/Carcinogenicity_Prediction/assets/141269604/c3019f61-3e15-4324-87ea-364673058837)
![cap6](https://github.com/AmelMansour/Carcinogenicity_Prediction/assets/141269604/f7e50bd1-cd29-487e-b8bf-4a5e54fbb46c)
![cap7](https://github.com/AmelMansour/Carcinogenicity_Prediction/assets/141269604/8bb7d044-a20d-4671-b6fb-5bf6e95928b9)
![cap8](https://github.com/AmelMansour/Carcinogenicity_Prediction/assets/141269604/0992a1ba-b241-4db8-aee2-603d9d737b74)


Méthodologie et Évaluation de la Prédiction de Carcinogénicité

Différents algorithmes de classification binaire, tels que la régression logistique, les machines à vecteurs de support (SVM) et les réseaux de neurones artificiels (ANN), ont été employés pour construire le modèle de prédiction de carcinogénicité. Ces choix sont basés sur leur aptitude à gérer les problèmes de classification et à prédire avec précision la carcinogénicité des composés organiques.


L'évaluation des performances s'est appuyée sur des métriques usuelles telles que l'exactitude, la précision, le rappel et la courbe ROC. Ces indicateurs ont permis d'évaluer l'efficacité du modèle dans la prédiction de la carcinogénicité et de comparer les approches.
