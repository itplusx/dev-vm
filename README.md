# ITplusX/dev-vm

# Generation of base package


Maybe the virtual box guest addition has not been updated in the used basebox. To be sure we update it manually. Follow the following steps:

1. `vagrant plugin install vagrant-vbguest`
2. `vagrant up`
4. `vagrant package`
5. Create new version of itplusx/dev-vm

# Todo
add documentation
set aliases
install ohmyzsh