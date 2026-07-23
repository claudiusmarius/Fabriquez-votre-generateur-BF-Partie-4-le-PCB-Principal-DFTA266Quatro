# Fabriquez-votre-g-n-rateur-BF-Partie-4-le-PCB-Principal-DFTA266Quatro

Vidéo YouTube : https://youtu.be/D2XhKlnVvlU
 
Générateur BF - Carte DDS AD9833
Présentation

Ce projet constitue la première étape de la réalisation d'un générateur BF modulaire.

Cette première carte a pour objectif de piloter un DDS AD9833 à l'aide d'un Seeeduino XIAO tout en proposant une interface utilisateur simple et évolutive.

Le projet est volontairement découpé en plusieurs cartes afin de valider chaque fonction indépendamment avant l'intégration finale.

Caractéristiques
Seeeduino XIAO

DDS AD9833

ATtiny85 pour le décodage des modes

Alimentation +12 V

Convertisseur RECOM +5 V

Écran OLED I²C

Deux potentiomètres

sélection des gammes de fréquence

sélection des formes d'onde

Deux boutons poussoirs

fréquence +

fréquence –

Sorties :

DDS

+12 V

+5 V

PB0

PB1

PB2

Formes d'onde :

Sinus

Triangle

Carré
Gammes de fréquence

1 Hz
10 Hz
100 Hz
1 kHz
10 kHz
100 kHz

La fréquence est ensuite ajustée finement grâce aux boutons UP et DOWN.

Logiciels utilisés
KiCad
Arduino IDE
Bibliothèque MD_AD9833

Évolutions prévues

Cette carte constitue la base du projet.

Les prochaines réalisations porteront sur :

alimentation à zéro virtuel
traitement analogique du signal
réglage de l'amplitude
offset continu
filtrage
étage de sortie
protection contre les courts-circuits
génération de dents de scie
wobulation
interface utilisateur évoluée


