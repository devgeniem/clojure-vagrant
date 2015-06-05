# -*- mode: ruby -*-
# vi: set ft=ruby :
# Vagrantfile API/syntax version. Don't touch unless you know what you're doing!

VAGRANTFILE_API_VERSION = "2"

Vagrant.configure(VAGRANTFILE_API_VERSION) do |config|
  
  config.vm.box = "phusion/ubuntu-14.04-amd64"
  
  config.vm.network "private_network", ip: "192.168.34.40"
  
 # config.vm.synced_folder "www", "/var/www", nfs: true
  
 # config.vm.synced_folder "nginx/sites-available", '/etc/nginx/sites-available', nfs: true

#  config.vm.provision :shell, :path => "scripts/init-box.sh", :privileged => false

end
