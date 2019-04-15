# qhuaweiflash
Utilitaire graphique pour flasher les modems et les routeurs de HUAWEI et éditer les fichiers de firmware

Cet utilitaire est destiné à:

- Firmwares des modems huawei, supportant le protocole de firmware, similaires à ceux utilisés dans les modems sur Balong V7. Y compris le travail à part entière mis en œuvre avec les signatures numériques du micrologiciel.
- Édition des images du firmware. Vous pouvez afficher, ajouter, supprimer, modifier des sections individuelles, modifier les en-têtes de section.
Édition implémentée des images de partition en code HEX et, partiellement, en mode formaté (si la section a un format significatif).
- Démarrez l’usbloader des chargeurs de modem à l’aide de correctifs.

L'utilitaire est construit sur le package graphique Qt et constitue la version Windows des utilitaires balong_flash, balong-usbload, ainsi que l'éditeur de microprogramme.

Dépendances :

apt-get install qt5-qmake qtbase5-dev zlib1g-dev


Pour assembler cet utilitaire, utilisez les commandes:

export QT_SELECT=qt5

qmake

make
