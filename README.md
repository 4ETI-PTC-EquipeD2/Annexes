### Annexes

# Sujet : Jeu pokémon. 
  Visualisation via une interface WEB  du plateau virtualisé sur lequel se déplcace le robot. Chaque obstacle fixe rencontrer par le robot équivaudra sur l'interface virtuel à un ennemi à combattre ou à fuir. 

![](DiagramRobotPCT.png)

# Etape 1 : se déplacer
  -	Moteur, STM32 .
  - Alix Galiléo
# Etape 2 : détecter les obstacles
  - Capteur ultrason, STM32 .
  - Balayage 180-180

# Etapes simultanées :
-	Map/repérage/trajet
-	Interface WEB/Communication WEB-RasberryPi	
-	Lecture QRCode (Demander caméra)
-	Adaptation lumière
-	Attaque pokémon : 
    - Tourner 360
    - Allumer LED
    - Avancer reculer
    - Son de combat
-	Un son de démarrage
-	Détecteur de mouvement => son de détection(suivi de mouvement avec le pointeur).
-	Odométrie (Inspiration github Galileo)
-	Rst du robot position zéro

Support : STM32(C) et Raspberry (Python)
