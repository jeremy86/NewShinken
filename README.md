NewShinken
==========

**NewShinken** fixe les fails dans le fichier ./install de Shinken

**Version 1** : Fixe pour le lien du plugin Nagios-plugins
=============

./install –p nagios-plugins

procédure d'instalation :
=========================

sudo su

cd /usr/local/shinken

rm install

wget https://raw.github.com/jeremy86/NewShinken/master/install

chmod 777 install