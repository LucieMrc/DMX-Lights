# DMX + Lights !

# 1. DMX ??

On controle la lumière en DMX, une norme de transmission de données qui permet de contrôler 512 canaux avec des valeurs de 0 à 255. On appelle "univers DMX" une ligne de 512 canaux, et on peux parfois contrôler plusieurs univers simultanément pour contrôler plusieurs lignes de 512 canaux.

DMX c'est donc un protocole de communication et un câble.

Chaque projecteur a un nombre de channels différents et les channels contrôlent différents éléments, et souvent il y a des options pour choisir le nombre channel DMX (et donc le nombre d'éléments controlés).

# 2. Adressage et branchements

On branche les projecteurs en série avec des câbles DMX et on les adresse en fonction du nombre de canaux qu'ils utilisent.

Par exemple, si on branche deux projecteurs RGB utilisant 3 canaux chacun (R, G et B) en série, on pourra adresser le premier projecteur avec la plage d'adresses allant de 1 à 3 et le second de 4 à 6. On utilise ainsi 6 canaux :

1 : R premier projecteur
2 : G premier projecteur
3 : B premier projecteur
4 : R second projecteur
5 : G second projecteur
6 : B second projecteur
On peux ensuite brancher d'autres projecteurs en série en continuant l'adressage selon le nombre de canaux utilisés par chaque projecteur.


# 3. Pixel Mapping

https://github.com/LucieMrc/Madmapper_PixelMapping

# 4. Contrôle DMX

## 4.2 Chataigne

https://github.com/LucieMrc/SalleFondVert_Controller

https://github.com/LucieMrc/Chataigne_2spi

## 4.3 Madmapper

## 4.4 Touchdesigner


# 5. Interaction

# 5.1 Arduino

# 5.2 Mediapipe


