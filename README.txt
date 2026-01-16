README.txt for version 9.1 of Vim: Vi IMproved.



Qu'est ce que vim

Vim est une version grandement améliorée du bon vieux éditeur UNIX Vi.
 De nombreuses nouvelles fonctionnalités ont été ajoutées : annulation
 multiniveau, coloration syntaxique, historique de la ligne de commande
, aide en ligne, correction orthographique, complétion des noms de fichiers
, opérations par blocs, langage de script, etc. Une interface utilisateur
 graphique (GUI) est également disponible. La compatibilité avec Vi est néanmoins
 maintenue ; ceux qui ont Vi « dans les doigts » se sentiront comme chez eux.
 Voir « runtime/doc/vi_diff.txt » pour les différences avec vi.

Cet éditeur est très utile pour éditer des programmes et d'autres fichiers texte brut.
 Toutes les commandes sont données avec des caractères clavier normaux, ce qui permet à
 ceux qui peuvent taper avec dix doigts de travailler très rapidement. De plus, les touches
 de fonction peuvent être associées à des commandes par l'utilisateur, et la souris peut être utilisée.

Vim vise également à fournir une implémentation vi (principalement) compatible POSIX,
 lorsqu'elle est compilée avec un ensemble minimal de fonctionnalités (généralement appelée vim.tiny),
 qui est utilisée par de nombreuses distributions Linux comme éditeur vi par défaut

Vin fonctionne sous MS-Windows (7, 8, 10, 11), macOS, Haiku, VMS et presque toutes les versions d'UNIX.
 Le portage vers d'autres systèmes ne devrait pas être très difficile. Les anciennes versions de Vim
 fonctionnent sous MS-DOS, MS-Windows 95/98/Me/NT/2000/XP/Vista, Amiga DOS, Atari MINT, BEOS, RISC OS
 et 05/2. Elles ne sont plus maintenues..


DISTRIBUTION

Vous pouvez souvent utiliser votre gestionnaire de paquets préféré pour installer Vim.
 Sur Mac et Linux, une petite version de Vim est préinstallée ; vous devez tout de même
 installer Vim si vous souhaitez plus de fonctionnalités.

Il existe des distributions distinctes pour Unix, PC, Amiga et d'autres systèmes.
 Ce fichier README.txt est fourni avec l'archive d'exécution. Il comprend la documentation,
 les fichiers de syntaxe et d'autres fichiers utilisés lors de l'exécution. Pour exécuter Vim,
 vous devez obtenir soit l'une des archives binaires, soit une archive source. Celle dont vous
 avez besoin dépend du système sur lequel vous souhaitez l'exécuter et si vous souhaitez ou devez
 la compiler vous-même. Consultez « https://www.vim.org/download.php » pour un aperçu des distributions
 actuellement disponibles.

Quelques sites populaires pour obtenir la dernière version de Vim :

Consultez le dépôt Git sur GitHub : https://github.com/vim/vim. Obtenez le code source sous forme d'archive :
 https://github.com/vim/vim/tags. Obtenez un exécutable Windows depuis le dépôt vim-win32-installer :
 https://github.com/vim/vim-win32-installer/releases.


COMPILING

If you obtained a binary distribution you don't need to compile Vim.  If you
obtained a source distribution, all the stuff for compiling Vim is in the
"src" directory.  See src/INSTALL for instructions.


INSTALLATION

See one of these files for system-specific instructions.  Either in the
READMEdir directory (in the repository) or the top directory (if you unpack an
archive):

README_ami.txt		Amiga
README_unix.txt		Unix
README_dos.txt		MS-DOS and MS-Windows
README_mac.txt		Macintosh
README_haiku.txt	Haiku
README_vms.txt		VMS

There are other README_*.txt files, depending on the distribution you used.


DOCUMENTATION

The Vim tutor is a one hour training course for beginners.  Often it can be
started as "vimtutor".  See ":help tutor" for more information.

The best is to use ":help" in Vim.  If you don't have an executable yet, read
"runtime/doc/help.txt".  It contains pointers to the other documentation files.
The User Manual reads like a book and is recommended to learn to use Vim.  See
":help user-manual".


COPYING

Vim is Charityware.  You can use and copy it as much as you like, but you are
encouraged to make a donation to help orphans in Uganda.  Please read the file
"runtime/doc/uganda.txt" for details (do ":help uganda" inside Vim).

Summary of the license: There are no restrictions on using or distributing an
unmodified copy of Vim.  Parts of Vim may also be distributed, but the license
text must always be included.  For modified versions, a few restrictions apply.
The license is GPL compatible, you may compile Vim with GPL libraries and
distribute it.


SPONSORING

Fixing bugs and adding new features takes a lot of time and effort.  To show
your appreciation for the work and motivate developers to continue working on
Vim please send a donation.

The money you donated will be mainly used to help children in Uganda.  See
"runtime/doc/uganda.txt".  But at the same time donations increase the
development team motivation to keep working on Vim!

For the most recent information about sponsoring look on the Vim web site:
	https://www.vim.org/sponsor/


CONTRIBUTING

If you would like to help make Vim better, see the CONTRIBUTING.md file.


INFORMATION

If you are on macOS, you can use MacVim: https://macvim.org

The latest news about Vim can be found on the Vim home page:
	https://www.vim.org/

If you have problems, have a look at the Vim documentation or tips:
	https://www.vim.org/docs.php
	https://vim.fandom.com/wiki/Vim_Tips_Wiki

If you still have problems or any other questions, use one of the mailing lists
to discuss them with Vim users and developers:
	https://www.vim.org/maillist.php

If nothing else works, report bugs directly to the vim-dev mailing list:
	<vim-dev@vim.org>


MAIN AUTHOR

Most of Vim was created by Bram Moolenaar <Bram@vim.org>, ":help Bram-Moolenaar"

Send any other comments, patches, flowers and suggestions to the vim-dev
mailing list: <vim-dev@vim.org>
