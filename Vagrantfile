# -*- mode: ruby -*-
# vi: set ft=ruby :

Vagrant.configure("2") do |config|
  config.vm.box = "ubuntu/xenial64"
  config.vm.network "private_network", type: "dhcp"
  config.vm.synced_folder "./", "/vagrant",
  owner: "www-data", group: "www-data"
  config.vm.provision "shell", path: "provision.sh"
end

