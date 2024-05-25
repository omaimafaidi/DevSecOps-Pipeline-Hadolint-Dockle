# Installation de Hadolint #
# Téléchargement de la dernière version de Hadolint
curl -fsSL -o hadolint https://github.com/hadolint/hadolint/releases/latest/download/hadolint-Linux-x86_64
# Déplacement de hadolint vers le répertoire bin
sudo mv hadolint /usr/local/bin/
#Donner les droits d'exécution au fichier 'hadolint'
sudo chmod +x /usr/local/bin/hadolint
# Vérification de la version installée de hadolint
hadolint –-version
## Installation de Dockle ##
# Téléchargement de la dernière version de Dockle (v0.4.14) 
sudo wget https://github.com/goodwithtech/dockle/releases/download/v0.4.14/dockle_0.4.14_Linux-64bit.tar.gz 
# Décompression de l'archive 
tar -xvf dockle_0.4.14_Linux-64bit.tar.gz 
# Déplacement de dockle vers le répertoire bin 
sudo mv ./dockle /usr/local/bin/dockle 
#Donner les droits d'exécution au fichier 'dockle'
sudo chmod +x /usr/local/bin/dockle 
# Vérification de la version installée de dockle
dockle --version
