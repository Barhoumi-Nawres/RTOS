## RTOS (real time operating system )est un système d'exploitation conçu a executer des taches dans un delais precise et deterministe .
# Les caractéristiques :
### Kernel(noyou):
coeur du système ,gère la planification  et l'éxecuter des taches .
### Priorité :
chaque tache a son priorité  ,et la plus tache la plus priorotaire ,s'execute en premier.
### Scheduler (ordonnaceur):
decide quelle la tache elle va s'executer .


## Interrupt:
l'interruption est un siganl envoyé au processeur pour lui  dire d'arreter  momentanément ,ce qu'il en train de faire  pour traiter un evenement important ,par exemple 
si un capteur detecte un mouvement ou bien si un boutton est appuyé 
-----------interrupt service Routine (ISR):fonctions qui gèrent les interruptions matériels .--------
# Explication du Code 
ce code permet d'envoyer trois tache  de meme priorité vis le protocole UART (Universal asynchronous receiver transmitter)
