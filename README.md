# DGnet_arch_linux_repo

##### By the time being this repo contains a single package - **nocache**
##### The upstream for the **nocache** package is: [DGnet_Program_nocache](https://github.com/andriykutsevol/DGnet_Program_nocache)
##### Go to your PI and do the following:
- download the repo
`git clone https://github.com/andriykutsevol/DGnet_arch_linux_repo`
- go to the repo
`cd ./DGnet_arch_linux_repo`
- go to the package directory
`cd ./nocache`
- to build executables and create a package from them
`makepkg`
- to install resulting package
`sudo pacman -U ./nocache-0.0.1-1-armv7h.pkg.tar.xz --overwrite /usr/local/share/man`