README.txt pour la version 9.2 de Vim : Vi IMproved.


QU'EST-CE QUE VIM ?

Vim est une version grandement améliorée du bon vieil éditeur UNIX Vi.  De
nombreuses fonctionnalités ont été ajoutées : annulation à plusieurs niveaux,
coloration syntaxique, historique de la ligne de commande, aide en ligne,
vérification orthographique, complétion des noms de fichiers, opérations sur
des blocs, langage de script, etc.  Une interface graphique (GUI) est également
disponible.  La compatibilité avec Vi est néanmoins conservée : ceux qui
connaissent Vi sur le bout des doigts se sentiront comme chez eux.
Voir "runtime/doc/vi_diff.txt" [en anglais] pour les différences avec Vi.

Cet éditeur est très utile pour modifier des programmes et d'autres fichiers en
texte brut.  Toutes les commandes sont saisies à l'aide des touches usuelles du
clavier, ce qui permet à ceux qui savent taper avec leurs dix doigts de
travailler très rapidement.  De plus, l'utilisateur peut associer des commandes
aux touches de fonction, et la souris peut être utilisée.

Vim vise également à fournir une implémentation de vi (en grande partie)
compatible POSIX lorsqu'il est compilé avec un jeu minimal de fonctionnalités
(généralement appelé vim.tiny), utilisé par de nombreuses distributions Linux
comme éditeur vi par défaut.

Vim fonctionne sous MS-Windows (7, 8, 10, 11), macOS, Haiku, VMS et presque
toutes les variantes d'UNIX.  Le portage vers d'autres systèmes ne devrait pas
être très difficile.  D'anciennes versions de Vim fonctionnent sous MS-DOS,
MS-Windows 95/98/Me/NT/2000/XP/Vista, Amiga DOS, Atari MiNT, BeOS, RISC OS et
OS/2.  Elles ne sont plus maintenues.


DISTRIBUTION

Vous pouvez la plupart du temps utiliser votre gestionnaire de paquets habituel
pour installer Vim.  Sur Mac et Linux, une version allégée de Vim est
préinstallée ; vous devrez néanmoins installer Vim si vous voulez davantage de
fonctionnalités.

Il existe des distributions distinctes pour Unix, PC, Amiga et certains autres
systèmes.  Ce fichier README.txt accompagne l'archive des fichiers d'exécution
(runtime).  Elle contient la documentation, les fichiers de syntaxe et d'autres
fichiers utilisés lors de l'exécution.  Pour exécuter Vim, vous devez obtenir
soit l'une des archives binaires, soit une archive contenant les sources.  Celle
dont vous avez besoin dépend du système sur lequel vous souhaitez l'exécuter et
de la nécessité ou non de le compiler vous-même.  Consultez
"https://www.vim.org/download.php" pour un aperçu des distributions
actuellement disponibles.

Quelques endroits courants pour obtenir la dernière version de Vim :
* Récupérer le dépôt git depuis GitHub : https://github.com/vim/vim.
* Obtenir le code source sous forme d'archive :
  https://github.com/vim/vim/tags.
* Obtenir un exécutable Windows depuis le dépôt vim-win32-installer :
  https://github.com/vim/vim-win32-installer/releases.


COMPILATION

Si vous avez obtenu une distribution binaire, vous n'avez pas besoin de
compiler Vim.  Si vous avez obtenu une distribution des sources, tout ce qui
est nécessaire pour compiler Vim se trouve dans le répertoire "src".  Voir
src/INSTALL pour les instructions.


INSTALLATION

Consultez l'un des fichiers suivants pour les instructions spécifiques à votre
système.  Ils se trouvent soit dans le répertoire READMEdir (dans le dépôt),
soit dans le répertoire racine (si vous décompressez une archive) :

README_ami.txt		Amiga
README_unix.txt		Unix
README_dos.txt		MS-DOS et MS-Windows
README_mac.txt		Macintosh
README_haiku.txt	Haiku
README_vms.txt		VMS

D'autres fichiers README_*.txt peuvent être présents selon la distribution
utilisée.


DOCUMENTATION

Le tutoriel de Vim (Vim tutor) est une formation d'une heure destinée aux
débutants.  Il peut généralement être lancé avec "vimtutor".  Voir ":help tutor"
pour plus d'informations.

Le mieux est d'utiliser ":help" dans Vim.  Si vous ne disposez pas encore d'un
exécutable, consultez "runtime/doc/help.txt".  Ce fichier renvoie vers les
autres fichiers de documentation.  Le manuel de l'utilisateur se lit comme un
livre et est recommandé pour apprendre à utiliser Vim.
Voir ":help user-manual".


LICENCE

Vim est un "Charityware".  Vous pouvez l'utiliser et le copier autant que vous
le souhaitez, mais vous êtes encouragé à faire un don pour aider des orphelins
en Ouganda.  Veuillez lire le fichier "runtime/doc/uganda.txt" pour plus de
détails (tapez ":help uganda" dans Vim).

Résumé de la licence : il n'y a aucune restriction à l'utilisation ou à la
distribution d'une copie non modifiée de Vim.  Des parties de Vim peuvent
également être distribuées, mais le texte de la licence doit toujours être
inclus.  Quelques restrictions s'appliquent aux versions modifiées.  La licence
est compatible avec la GPL : vous pouvez compiler Vim avec des bibliothèques
sous licence GPL et le distribuer.


PARRAINAGE

Corriger des bugs et ajouter de nouvelles fonctionnalités demande beaucoup de
temps et d'efforts.  Pour montrer votre reconnaissance pour ce travail et
encourager les développeurs à continuer à travailler sur Vim, faites un don.

L'argent que vous donnez servira principalement à aider des enfants en
Ouganda.  Voir "runtime/doc/uganda.txt".  Mais en même temps, les dons
renforcent la motivation de l'équipe de développement à continuer à travailler
sur Vim !

Pour les informations les plus récentes sur le parrainage, consultez le site
web de Vim :
	https://www.vim.org/sponsor/


CONTRIBUER

Si vous souhaitez aider à améliorer Vim, consultez le fichier CONTRIBUTING.md.


INFORMATIONS

Si vous êtes sous macOS, vous pouvez utiliser MacVim : https://macvim.org

Les dernières nouvelles sur Vim se trouvent sur la page d'accueil de Vim :
	https://www.vim.org/

En cas de problème, consultez la documentation ou les astuces Vim :
	https://www.vim.org/docs.php
	https://vim.fandom.com/wiki/Vim_Tips_Wiki

Si vous avez toujours des problèmes ou d'autres questions, utilisez l'une des
listes de diffusion pour en discuter avec les utilisateurs et les développeurs
de Vim :
	https://www.vim.org/maillist.php

Si rien d'autre ne fonctionne, signalez les bugs directement sur la liste de
diffusion vim-dev :
	<vim-dev@vim.org>


AUTEUR PRINCIPAL

L'essentiel de Vim a été créé par Bram Moolenaar <Bram@vim.org>,
":help Bram-Moolenaar"

Envoyez tous vos autres commentaires, correctifs, fleurs et suggestions à la
liste de diffusion vim-dev : <vim-dev@vim.org>
