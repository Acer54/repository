# Debian-Repository of Acer54:

:warning: If you use this repository in your system or download and install any software, 
you are doing this **at your own risk!**. I am not responsible for any damage or harm you, 
your Hard-/Software or your Data may get.

If you still want to use this repository, you can install it to your system following the
installation guide, or simply download and install any Deb-File included in the subfolders.

# Installation & Update
### 1. Add a new source to your system:
    wget https://raw.githubusercontent.com/Acer54/repository/master/release/release.key && sudo apt-key add release.key && rm release.key
    wget "https://raw.githubusercontent.com/Acer54/repository/master/release/acer54_repository.list" && sudo mv acer54_repository.list /etc/apt/sources.list.d/
### 2. Update your sources:
    sudo apt update
### 3. Install webradio-py:
    sudo apt install <the package you want>