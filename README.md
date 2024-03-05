# Projet Transversal

Cette branche est dédiée à la conception d'un module RF pour la détection de tags RFID + Localisation du robot par télémètre/LiDAR/Emetteur-Récepteur 

Projet Transversal

## Objectifs RF (Pas très dur et pas très long)

- Matériel probable : RC522 + STM32
- Détecter les badges RFID et leur attribuer un type de plante, à retourner à la STM32 principale
- Tests à effectuer: RC522 fonctionnels, Correspondance entre un badge RFID et un type de plante

## Objectifs "GPS" (Je vais suer sa mère)

- Matériel probable : STM32 + Télémètre ou RF (2.4GHz ou LoRa 800Mhz)
- Utiliser un module RF pour permettre une localisation (par triangulation)
- Tests à effectuer: Module LoRa fonctionnel, tests de base pour vérifier le bon fonctionnement, algorithme de triangulation sur le module RF, dans un premier temps à part puis intégré au robot

## Planning

WIP