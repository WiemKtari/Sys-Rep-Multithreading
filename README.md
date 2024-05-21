# Sys-Rep-Multithreading

## Introduction

Ce projet Java implémente un serveur TCP multithread capable de gérer simultanément jusqu'à 10 clients. Chaque client peut envoyer une chaîne de caractères au serveur, qui inverse la chaîne et la renvoie. Le serveur utilise des threads pour gérer les connexions simultanées des clients et assurer un traitement efficace.

## Objectifs

Créer un serveur TCP multithread capable de gérer jusqu'à 10 connexions simultanées.

Implémenter une logique de traitement simple consistant à inverser une chaîne de caractères.

Utiliser Thread.sleep() pour simuler un temps de traitement.

Gérer les flux d'entrée et de sortie avec BufferedReader et PrintWriter.


## Fonctionnalités

Gère jusqu'à 10 connexions client simultanées en utilisant des threads.

Inverse les chaînes de caractères reçues des clients.

Fournit des messages d'information pour indiquer l'état de la connexion et les données reçues/envoyées.

## Structure du Code

multi_thread_server.java:
Ce fichier implémente la logique du serveur, y compris la création de sockets, la gestion des connexions clients, la gestion des threads, l'inversion des chaînes et la communication.

Client.java:
Ce fichier implémente la logique du client, y compris la création de sockets, l'établissement de la connexion, l'envoi et la réception de chaînes, et la fermeture de la connexion.
