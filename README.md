NewShinken
==========

**NewShinken** fixe les fails dans le fichier ./install de Shinken

**Version 1** : Fix pour le lien du plugin Nagios-plugins
=============

./install –p nagios-plugins

Procédure d'installation :
=========================

sudo su

cd /usr/local/shinken

rm install

wget https://raw.github.com/jeremy86/NewShinken/master/install

chmod 777 install