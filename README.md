# Kafka Streaming Application

Ce projet implémente une application de streaming basée sur Apache Kafka et PySpark pour simuler et analyser les consultations de produits en temps réel. Deux scripts principaux sont fournis : 

- `producer.py` : Génère des messages Kafka simulant les consultations de produits (avec un `client_id` et un `produit_consulter_id`).
- `consumer.py` : Traite ces messages en temps réel et affiche des graphiques dynamiques des consultations et recommandations de produits.

---

## Technologies clés
- Kafka : Gestion des flux de données.
- PySpark : Traitement des données en temps réel.
- Matplotlib : Visualisation des données.

---

## Instructions
1. Configuration : Configurez Kafka et préparez le fichier `client.properties` avec vos informations de connexion.
2. Exécution :
   - Lancez le producteur avec : `python producer.py` pour générer des messages Kafka.
   - Démarrez le consommateur avec : `python consumer.py` pour traiter les messages et afficher les graphiques.

Les graphiques affichent en temps réel :
- Consultations totales des produits.
- Recommandations pour des produits similaires.

---

## Installation
1. Clonez ce dépôt dans votre environnement local : 
   ```bash
   git clone https://github.com/Maodo400/projet-kafka.git