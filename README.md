# FCSC 2022 Mommy Morse

On vous demande d’envoyer un message en Morse avec une modulation de fréquence à deux états. Le codage choisi est que les . et - sont représentés par une porteuse pure à une fréquence de 5kHz, et les espacements sont représentés par une porteuse pure à une fréquence de 1kHz.

Vous devez envoyer ```CAN I GET THE FLAG```.

Vous avez le code du serveur ainsi qu’un exemple de message à disposition.

Les paramètres de transmission sont les suivants :

- fréquence d’échantillonnage : 24kHz,
- envoi d’un . : porteuse pure de fréquence 5kHz pendant 1 milliseconde,
- durée d’un - : porteuse pure de fréquence 5kHz pendant 5 millisecondes,
- espacement entre deux lettres : porteuse pure de fréquence 1kHz pendant 5 millisecondes,
- espacement entre deux mots : porteuse pure de fréquence 1kHz pendant 20 millisecondes.

Cette épreuve a été découpée en trois étapes :

- Baby Morse.
- Daddy Morse.
- **Mommy Morse**.


Fichiers :
- [mommy-morse.py](mommy-morse.py) 
- [client.py](client.py) 
- [signal.iq](signal.iq) 




Auteurs : ElyKar

Origine : [Mommy Morse](https://hackropole.fr/fr/challenges/hardware/fcsc2022-hardware-mommy-morse/)

-----------

## Connectez vous en WEBSSH
> http://localhost

#### tentez 
> nc mommy-morse.cyrhades.fr:4000

-----------

## Ou directement avec netcat
> nc localhost:4000


-----------

## Installation manuel
Vous n'utilisez pas l'application **les CTFs de Cyrhades** ? C'est dommage !
Mais voici comment installer ce CTF manuellement :

> git clone https://github.com/Hack-Oeil/fcsc2022-hardware-mommy-morse.git

> cd fcsc2022-hardware-mommy-morse


-----------

## Sur le site officiel hackropole.fr
> https://hackropole.fr/fr/challenges/hardware/fcsc2022-hardware-mommy-morse/