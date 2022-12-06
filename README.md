# rar-s-info-m-manager-xavier
JETE TOUS LES FICHIERS DANS LE RUTORRENT AU ROOT
puis

DROIT USER POUR LE REBOOT

nano /etc/sudoers
Puis rajouter a la fin
www-data ALL = NOPASSWD: ALL

LIEN SYMBOLIQUE POUR LE REPERTOIRE FILES MANAGER
LS qui home dans /var/www/rutorrent/files-manager/files

ln -s home var/www/rutorrent/files-manager/files/home

DONNER LES DROIT A TOUS LE HOME POUR POUVOIR EFFACER LES FICHIER DANS LE MANAGER
Puis chmord /www-Data tous le home et le reparer

chown -R www-data:www-data /home/
