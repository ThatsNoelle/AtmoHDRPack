# AtmoHDRPack
Salut !
Le but de cette page est de fournir des tutos complets pour débutants *et surtout j'ai pas envie d'avoir mes DMs Discord saturés*, pour permettre à tous de mettre à jour HDR, ainsi que leurs Switch.
Vous trouverez le pack dans les [releases] (https://github.com/ThatsNoelle/AtmoHDRPack/releases) (si je fais pas de la merde). 
Notez que SSBU n'est pas compris dans ledit pack, achetez-le, ou ayez-le à vos propre risques.
Si vous avez des problèmes, n'hésitez pas à ouvrir une issue sur la page GitHub ou à venir me contacter directement sur Discord (thatsnoelle).
Sur cette page, vous n'apprendrez pas comment hack une Switch. Pour ça il existe des pages, des serveurs Discord, des forums déjà spécialisés.

Ce pack contient :
- La dernière version de Atmosphere (Version actuelle :`1.6.2`)
- La dernière version de Hekate (Version actuelle : `6.1.0`)
- La dernière version de HDR (Version actuelle : `v0.42.5-beta`)
- Quelques Homebrews plus ou moins utiles
- Des protections contre le online de Nintendo, pour ne pas vous faire ban du Online bêtement (*si vous voulez désactiver ces protections, un mini-tuto sera disponible plus bas*)
- La dernière version de ARCropolis et de Skyline, ainsi que la dernière version des plugins requis par HDR.

### Comment accéder facilement à votre SD via Hekate
1. Sur votre switch en CFW (hackée), allez dans le homebrew menu (l'album).
2. Sur ce menu, allez trouver le Homebrew `Reboot to payload`, il devrait déjà être inclus dans le pack.
3. Sur votre manette, appuyez sur le bouton `-`.
4. Si tout à bien fonctionné, votre Switch devrait afficher un écran avec des boutons en bleu marquant "Launch", etc...
5. Allez ensuite dans l'onglet `Tools`, présent en haut. Vous pouvez naviguer en utilisant les Joy-Cons ou le tactile.
6. Cliquez après sur `USB Tools`, et ensuite sur `SD Card`, tout en branchant votre Switch à un ordinateur.
7. Bien joué à vous, vous pouvez accéder à votre SD !
8. Pour retourner sur votre Switch, retournez sur l'onglet `Home`, appuyez sur `Launch`, et ensuite, suivant si vous avez une EmuNAND ou non, appuyez sur `EmuNAND - CFW` ou sur `SysNAND - CFW`. (pour savoir si vous avez une EmuNAND, un dossier `emuMMC` devrait être présent à la racine de votre SD). Votre Switch s'allume maintenant en CFW (en hacké)

### Comment accéder facilement à votre SD (et même plus) via DBi :
1. Branchez votre Switch à un ordinateur. Lancez le homebrew dans le homebrew menu (l'album), un écran bleu devrait apparaître. Utilisant votre manette, déplacez le curseur sur "Run MTP Responder", et cliquez dessus.
2. Acceptez sur votre ordinateur le fait de pouvoir explorer les fichiers du périphérique.
3. Pour accéder à votre SD, cliquez sur `1: SD Card`.
4. Pour retourner au menu Home, il suffit juste de spammer B jusqu'à votre menu Home.

### Comment mettre à jour Atmosphere :
1. Supprimez tout sur votre carte SD, sauf les dossiers `emuMMC` (si il existe) et `Nintendo`.
2. Allez prendre le dernier pack se trouvant dans les releases.
3. Une fois téléchargé, mettez le tout le contenu du dossier à la racine de votre carte SD.

### Comment mettre à jour votre switch :
**__Note__ :** Je vous conseille fortement de désactiver les mises à jour automatiques, que ce soit des jeux ou de la 
Switch. De manière générale, si vous le pouvez, mettez toujours à jour Atmosphere ET ENSUITE la switch via Daybreak (via 
Internet n'est pas conseillé si vous avez des jeux crackés).

1. Mettez d'abord à jour Atmosphere avec le pack et le tuto.
2. Allez prendre la dernière version de la switch en suivant [ce] (https://darthsternie.net/switch-firmwares/) lien. La version actuelle conseillée est la `17.0.1`.
3. Avec le Homebrew DBi (présent dans le pack), ou sur Hekate, accédez à votre carte SD. 
4. Une fois sur votre SD, mettez tout les fichiers du .zip dans un dossier à la racine de votre SD.
5. Maintenant que vous avez votre dossier, retournez sur le menu Home, et relancez le Homebrew menu.
6. Trouvez le logiciel nommé `Daybreak`, il devrait déjà être inclus dans le pack.
7. Cliquez sur `Install` .
8. Sélectionnez le dossier que vous venez de créer.
9. Patientez quelques instants le temps que Daybreak vérifie vos fichiers.
10. Cliquez sur le bouton `Continue` qui vient d'apparaître.
11. Cliquez sur `Preserve Settings`.
12. Cliquez sur `Install (FAT32+exFAT)`.
13. Cliquez sur `Continue`.
14. Patientez un peu le temps que l'installation se fait.
15. Cliquez enfin sur `Reboot`, votre console revient sur le menu de Hekate, vous pouvez à nouveau revenir sur votre Switch maintenant à jour.

### Comment mettre à jour HDR :
Si vous avez des problèmes avec le launcher de HDR pour installer la màj, voici ce que vous pouvez faire :
1. Accédez à votre SD en utilisant DBi ou Hekate (tutos dispo plus haut).
2. Supprimez le fichier `hdr-launcher.nro` se trouvant dans le dossier `SD/atmosphere/contents/01006a800016e000/romfs/skyline/plugins/`.
3. Supprimez le dossier `0100000000000013` se trouvant dans le dossier `SD:/atmosphere/contents/`.
4. Supprimez les dossiers `hdr`, `hdr-assets`, ainsi que `hdr-stages` se trouvant dans le dossier `SD:/ultimate/mods/`.
5. Refaites une installation complète en prenant la dernière version du pack, ou en prenant la dernière version sur le [GitHub de HDR] (https://github.com/HDR-Development/HDR-Releases/releases).

# Crédits & remerciements
- La team HDR et le mod HDR : leur [serveur Discord] (https://discord.gg/hdr) & leur [page GitHub] (https://github.com/HDR-Development/HDR-Releases).
- Atmosphere : leur [page GitHub] (https://github.com/Atmosphere-NX/Atmosphere).
- Hekate : leur [page GitHub] (https://github.com/CTCaer/hekate)
- Le serveur Discord de Sblerky, la principale base de ce pack : le [serveur Discord] (https://discord.gg/6DUzJuzHSB) en question
- Aline <3