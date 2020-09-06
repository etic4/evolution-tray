# Evolution-tray
Un indicateur d'emails pour la barre système de l'environnement de bureau Gnome. Devrait fonctionner sur d'autres environnements de bureau.


Affiche les emails non lus pour tous les comptes actifs d'Evolution mail.

Testé sur Ubuntu 20.04

## Usage
Installer `requirements.txt`
`pip3 install -r requirements.txt`

Il y a peut-être l'une ou l'autre dépendance système en plus de celles-ci:

`sudo apt install python3-gi python3-gi-cairo gir1.2-gtk-3.0`

Pour lancer l'application:

`python3 ./mail-unread.py`
